# Phase 5: GENERATE — Context-Aware Artifact Creation

> Every generated artifact must be PURPOSE-BUILT for its exact location on the site. No generic images. No "hope it fits." No trinket dropping.

## The Rule

Before generating ANY image, you must know EXACTLY where it goes, how the CSS treats it, and what the surrounding context looks like. Generate for the context, not for the prompt.

## Pre-Generation Checklist (Per Artifact)

Before writing a single prompt:

1. ☐ Screenshot the exact section where this image will live
2. ☐ Document the CSS context:
   - Container dimensions (natural + rendered)
   - Background color/gradient behind it
   - Overlay gradients on top of it
   - Blend mode (normal, multiply, overlay, etc.)
   - Opacity
   - Border radius
3. ☐ Note the site palette (from Phase 1 DNA Profile)
4. ☐ Note the emotional target (from Phase 2 Feel Profile)
5. ☐ Determine aspect ratio needed

## Prompt Engineering for Context-Aware Artifacts

### Always Include
- **The site's actual hex colors**: "warm gold (#D4AF37) and deep black (#0A0A0A) tones"
- **Usage context**: "displayed at 1128×375px with a dark gradient overlay from the left side"
- **Style match**: "photorealistic product photography, soft studio lighting"
- **Negative constraints**: "no cold blue tones, no purple, no neon, no flat illustration"
- **Material specificity**: "matte black glass jar, brushed gold metal lid, embossed logo"

### Prompt Structure
```
[Subject] + [Material/Style] + [Colors (hex)] + [Lighting] + [Camera Angle] + [Background] + [Negative]
```

**Example:**
```
"Luxury body butter in a matte black glass jar with brushed gold lid, 
Crown Collection logo embossed on front, warm studio lighting from upper-left,
shot from 30-degree angle, deep black background (#0A0A0A) with subtle 
gold (#D4AF37) rim light, photorealistic product photography, 
no cold tones, no blue, no flat illustration"
```

## Model Selection

| Need | Best Tool | Notes |
|------|-----------|-------|
| Product stills, hero images | **Nano Banana Pro** (Gemini 3 Pro Image) | Best for photorealistic product shots |
| Alternative stills | GPT Image 1.5, Grok Imagine | Different aesthetic options |
| Video / Animation | Kling 3, Veo 3 | For motion sequences |
| Start/End keyframes | Stitch | Frame interpolation |
| Product rotations | Leonardo AI Product Spin Video | 360° sequences |
| Style matching | Leonardo AI Style Transfer | Apply site identity to any image |
| Scene placement | Leonardo AI Product In Scene | Lifestyle product shots |
| Relighting | Leonardo AI Custom Relight | Match lighting across frames |
| Background swap | Leonardo AI Background Change | Context-match backgrounds |
| Canvas expansion | Leonardo AI Instant Outpaint | Fill wider containers |

### Leonardo AI Blueprints
When Leonardo AI access is available, use Blueprints as one-click workflow accelerators:
- **Product Studio Photoshoot** → Upload photo → professional studio angles
- **Product In Scene** → Product in lifestyle environments
- **Product Spin Video** → 360° rotation → extract frames for scroll sequences:
  ```bash
  ffmpeg -i spin.mp4 -vf "fps=30" frame_%04d.png
  ```
- **Style Transfer** → Apply site's visual identity to generated images
- **Custom Relight** → Consistent lighting across all frames
- **Background Change** → Match backgrounds to site sections
- **Instant Outpaint** → Expand images for wider containers

## Scroll Sequence Frame Generation

For Apple-style scroll-driven product reveals:

### Step 1: Define Keyframe Moments (8-12)
```
Frame 1:  Product centered, lid closed, hero pose
Frame 2:  Subtle glow begins around edges
Frame 3:  Lid lifts 15 degrees, golden light escaping
Frame 4:  Lid floating above, cream surface visible
Frame 5:  Ingredients begin emerging (shea butter wisps, cocoa particles)
Frame 6:  Full ingredient explosion — botanicals orbiting the jar
Frame 7:  Ingredients settling back
Frame 8:  Cream texture extreme close-up
Frame 9:  Lid descending
Frame 10: Product reassembled, slight rotation from original
Frame 11: Final hero pose with subtle glow
```

### Step 2: Consistency Protocol
Use the SAME base prompt with only the action/angle changing:
```
BASE: "luxury body butter jar, matte black container, brushed gold lid,
Crown Collection embossed logo, soft studio lighting from upper-left,
black background (#0A0A0A), gold accent (#D4AF37), photorealistic"

FRAME 1: [BASE] + "jar centered, lid closed, front angle, slight shadow beneath"
FRAME 2: [BASE] + "jar centered, subtle golden aura glowing from edges"
FRAME 3: [BASE] + "lid slightly lifted 15 degrees, warm golden light escaping gap"
...
```

### Step 3: Interpolation Strategy
- Generate 30-60 carefully chosen frames (NOT 200 unique AI frames)
- Canvas transitions handle smooth interpolation between them
- More frames at critical moments (lid opening, ingredient explosion)
- Fewer frames during slow transitions (subtle glow, settling)

### Step 4: Video-to-Frames Fallback
If still-frame consistency is hard to maintain:
```bash
# Generate video with Kling 3 / Veo 3 / Leonardo Product Spin
# Then extract:
ffmpeg -i product_reveal.mp4 -vf "fps=24,scale=1920:1080" frames/frame_%04d.webp
```

### Step 5: Frame Optimization
- **Format**: WebP (smaller than PNG, transparency support)
- **Target**: 50-80KB per frame
- **Resolution**: 1920×1080 for desktop, generate 960×540 set for mobile
- **Naming**: `frame_0001.webp` through `frame_0060.webp`

### Step 6: Test Before Committing
Build a 10-frame prototype first. Test scroll scrubbing. If it's smooth, generate the full set.

## Generation Protocol

1. Generate **4 variants** of each artifact
2. **Preview ALL** — show to user or evaluate against site context
3. **Select** the best match
4. **Test in situ** — place in actual page, screenshot, evaluate
5. If it doesn't blend → adjust prompt → regenerate. **Never force-fit.**

## Phase 5 Completion Criteria

- [ ] Every artifact has a documented placement context (section, dimensions, CSS)
- [ ] Prompts include site palette hex codes and negative constraints
- [ ] 4 variants generated per artifact, best selected
- [ ] Each artifact tested in situ with screenshot verification
- [ ] Scroll sequence frames (if applicable) tested in 10-frame prototype
- [ ] All artifacts blend naturally — no "dropped in" look

---

*← [Phase 4: FORGE](04-forge.md) | Back to [Iron_Canvas_v1.md](../Iron_Canvas_v1.md) | Next: [Phase 6: COMPOSE →](06-compose.md)*
