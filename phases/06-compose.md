# Phase 6: COMPOSE — Integration & Scroll Engine

> Place every artifact into the site, verify it blends, and build the scroll engine if the design calls for it.

## The Rule

Integration is not "upload and done." Every artifact must be verified IN CONTEXT. Screenshot. Evaluate. Adjust. Repeat.

## Standard Image Integration

### Process
1. Place artifact into the site (replace placeholder or add to section)
2. **Screenshot the section** with the new artifact in context
3. Evaluate against three questions:
   - Does it **BLEND** with its container? Or does it look dropped in?
   - Does the **lighting** match surrounding elements?
   - Does it **feel** like it was always part of this design?
4. Adjust CSS as needed:
   - Overlay gradients to match surrounding darkness/lightness
   - Opacity tweaks
   - Blend modes (multiply for darker integration, screen for lighter)
   - Tint filters to match palette temperature
5. **Check on mobile** — does it scale properly? Does it crop well?
6. If it doesn't work → go back to Phase 5 → regenerate with adjusted prompt

### CSS Integration Tricks
```css
/* Darken an image to match a dark section */
.hero-image {
  filter: brightness(0.7) saturate(1.2);
}

/* Warm tint to match gold palette */
.product-image {
  filter: sepia(0.1) saturate(1.3);
}

/* Gradient overlay for text readability */
.image-container::after {
  content: '';
  position: absolute;
  inset: 0;
  background: linear-gradient(to right, rgba(0,0,0,0.8) 0%, transparent 60%);
}
```

## Scroll Engine (GSAP ScrollTrigger + HTML5 Canvas)

For scroll-driven image sequence animations — the Apple AirPods / DJI Mavic effect.

### Architecture
```
┌──────────────────────────────────────┐
│  Fixed <canvas> (100vw × 100vh)      │
│  Position: sticky                    │
│  z-index: behind content overlays    │
├──────────────────────────────────────┤
│  Scroll container                    │
│  height: totalFrames × scrollMult    │
│  (typically 5-8× viewport height)    │
├──────────────────────────────────────┤
│  GSAP ScrollTrigger                  │
│  Maps scroll position → frame index  │
│  Uses requestAnimationFrame          │
├──────────────────────────────────────┤
│  Content overlays                    │
│  Text, CTAs, feature callouts        │
│  Fade in/out at scroll progress %    │
└──────────────────────────────────────┘
```

### Core Implementation

```javascript
import { gsap } from 'gsap';
import { ScrollTrigger } from 'gsap/ScrollTrigger';
gsap.registerPlugin(ScrollTrigger);

// Configuration
const TOTAL_FRAMES = 60;
const FRAME_PATH = '/frames/frame_';
const FRAME_EXT = '.webp';

// Preload all frames
const frames = [];
let loadedCount = 0;

function preloadFrames() {
  return new Promise((resolve) => {
    for (let i = 1; i <= TOTAL_FRAMES; i++) {
      const img = new Image();
      const num = String(i).padStart(4, '0');
      img.src = `${FRAME_PATH}${num}${FRAME_EXT}`;
      img.onload = () => {
        loadedCount++;
        updateLoadingProgress(loadedCount / TOTAL_FRAMES);
        if (loadedCount === TOTAL_FRAMES) resolve();
      };
      frames.push(img);
    }
  });
}

// Canvas setup
const canvas = document.getElementById('scroll-canvas');
const ctx = canvas.getContext('2d');

function resizeCanvas() {
  canvas.width = window.innerWidth;
  canvas.height = window.innerHeight;
}
window.addEventListener('resize', resizeCanvas);
resizeCanvas();

// Draw frame
function drawFrame(index) {
  const img = frames[Math.min(index, TOTAL_FRAMES - 1)];
  if (!img) return;
  
  // Cover-fit the image to canvas
  const scale = Math.max(
    canvas.width / img.naturalWidth,
    canvas.height / img.naturalHeight
  );
  const x = (canvas.width - img.naturalWidth * scale) / 2;
  const y = (canvas.height - img.naturalHeight * scale) / 2;
  
  ctx.clearRect(0, 0, canvas.width, canvas.height);
  ctx.drawImage(img, x, y, img.naturalWidth * scale, img.naturalHeight * scale);
}

// Initialize after preload
preloadFrames().then(() => {
  hideLoadingIndicator();
  drawFrame(0); // Draw first frame
  
  // ScrollTrigger animation
  gsap.to({ frame: 0 }, {
    frame: TOTAL_FRAMES - 1,
    snap: 'frame',
    ease: 'none',
    scrollTrigger: {
      trigger: '#scroll-section',
      start: 'top top',
      end: 'bottom bottom',
      scrub: 0.5, // Smooth scrubbing (0.5s lag)
      pin: canvas,
    },
    onUpdate: function() {
      drawFrame(Math.round(this.targets()[0].frame));
    }
  });
  
  // Content overlays synced to scroll
  gsap.to('.overlay-text-1', {
    opacity: 1, y: 0,
    scrollTrigger: {
      trigger: '#scroll-section',
      start: '10% top',
      end: '20% top',
      scrub: true,
    }
  });
  
  gsap.to('.overlay-text-2', {
    opacity: 1, y: 0,
    scrollTrigger: {
      trigger: '#scroll-section',
      start: '35% top',
      end: '45% top',
      scrub: true,
    }
  });
});
```

### HTML Structure
```html
<!-- Loading indicator -->
<div id="loader">
  <div class="loader-bar" style="width: 0%"></div>
  <span>Loading experience...</span>
</div>

<!-- Scroll sequence section -->
<section id="scroll-section" style="height: 500vh;">
  <canvas id="scroll-canvas"></canvas>
  
  <!-- Content overlays -->
  <div class="overlay-text-1" style="opacity: 0; transform: translateY(30px);">
    <h2>Crafted with intention</h2>
    <p>Every ingredient chosen for your skin</p>
  </div>
  
  <div class="overlay-text-2" style="opacity: 0; transform: translateY(30px);">
    <h2>Pure luxury, no compromise</h2>
    <p>Limited batches. When it's gone, it's gone.</p>
  </div>
</section>
```

### CSS
```css
#scroll-section {
  position: relative;
}

#scroll-canvas {
  position: sticky;
  top: 0;
  width: 100vw;
  height: 100vh;
  z-index: 1;
}

.overlay-text-1,
.overlay-text-2 {
  position: absolute;
  z-index: 2;
  color: white;
  text-align: center;
  width: 100%;
  pointer-events: none;
}

.overlay-text-1 { top: 15%; }
.overlay-text-2 { top: 40%; }
```

### Implementation Checklist
- [ ] Preload ALL frames before enabling scroll (show loading %)
- [ ] Use `<canvas>` not `<img>` swapping (GPU-accelerated)
- [ ] Map scroll progress (0→1) to frame index
- [ ] Debounce with `requestAnimationFrame`
- [ ] Mobile: reduce frames (every 2nd) or lower resolution
- [ ] Fallback: static hero if frames fail to load
- [ ] Content sync: text/CTAs fade at scroll % via `scrub: true`
- [ ] Performance: 60fps on M1+, 30fps min on older mobile
- [ ] Scroll height: 5-8× viewport for comfortable pacing
- [ ] Reverse: scrolling up plays backward smoothly
- [ ] Loading: graceful progress indicator, not white screen

### Mobile Optimization
```javascript
// Detect mobile and reduce frame count
const isMobile = window.innerWidth < 768;
const FRAME_STEP = isMobile ? 2 : 1; // Every other frame on mobile
const EFFECTIVE_FRAMES = Math.ceil(TOTAL_FRAMES / FRAME_STEP);
```

## Phase 6 Completion Criteria

- [ ] All artifacts placed and verified in context (screenshot proof)
- [ ] CSS adjustments applied for seamless blending
- [ ] Mobile layout verified at 375px
- [ ] Scroll engine (if applicable) built and functional
- [ ] Frame preloading with loading indicator works
- [ ] Content overlays sync with scroll progress
- [ ] Performance tested (Lighthouse, real device)
- [ ] Fallback states work (no blank screens)

---

*← [Phase 5: GENERATE](05-generate.md) | Back to [Iron_Canvas_v1.md](../Iron_Canvas_v1.md) | Next: [Phase 7: REFINE →](07-refine.md)*
