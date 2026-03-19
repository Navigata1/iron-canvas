# Anti-Patterns — What Iron Canvas Must NEVER Do

> These are the mistakes that turn premium enhancement into generic destruction. Memorize them.

## The 8 Anti-Patterns

### 1. Cookie-Cutter
**What it looks like:** All sites end up with the same palette, fonts, and layout.
**Why it happens:** Skipping Phase 1 (STUDY) and applying a default "nice-looking" template.
**How to prevent:** Complete the DNA Profile before touching anything. The palette comes FROM the site.

### 2. Blind Generation
**What it looks like:** AI-generated images that don't fit their container, clash with the palette, or float on mismatched backgrounds.
**Why it happens:** Generating images without studying where they'll go.
**How to prevent:** Complete the Pre-Generation Checklist in Phase 5. Screenshot the target section. Document the CSS context. THEN generate.

### 3. Template Imposition
**What it looks like:** Forcing navy/gold, dark mode, or any specific aesthetic regardless of the existing design.
**Why it happens:** Having a "taste" preference and applying it universally.
**How to prevent:** Phase 4 (FORGE) explicitly says: adapt to the site, never impose.

### 4. Batch-and-Pray
**What it looks like:** Generating all images at once, dropping them all in, hoping they work.
**Why it happens:** Time pressure, laziness, or overconfidence.
**How to prevent:** Phase 5 Generation Protocol: generate → preview → select → test in situ → iterate. One at a time.

### 5. Identity Erasure
**What it looks like:** The enhanced site is unrecognizable from the original. The owner says "that's not my brand."
**Why it happens:** Over-enhancing. Changing too many things at once. Losing sight of the original DNA.
**How to prevent:** Phase 7 checklist: "Is this recognizably the SAME site but better?" If not, pull back.

### 6. Trinket Dropping
**What it looks like:** Small AI-generated images scattered around that don't integrate with the page's CSS, gradients, or layout.
**Why it happens:** Treating image placement as "upload and done" instead of composing with CSS context.
**How to prevent:** Phase 6 (COMPOSE) — every image must be verified in context with screenshot proof.

### 7. Video-as-Animation
**What it looks like:** Playing an MP4 video where a scroll-driven canvas animation should be.
**Why it happens:** Videos are easier to implement than canvas frame sequences.
**Why it's wrong:** Videos can't scrub with scroll, can't reverse, can't sync content overlays, have autoplay restrictions on mobile.
**How to prevent:** Use the scroll engine architecture from Phase 6. Canvas + frames + ScrollTrigger.

### 8. Frame Inconsistency
**What it looks like:** Scroll sequence frames with wildly different lighting, angles, materials, or styles. The "animation" looks like a slideshow of different photos.
**Why it happens:** Generating frames with different prompts or insufficient consistency constraints.
**How to prevent:** Use the Consistency Protocol from Phase 5: SAME base prompt, only vary the action/angle.

## Red Flags During Work

If you notice any of these, STOP and reassess:

- 🚩 You haven't looked at the existing site's CSS yet
- 🚩 You're about to use a hex code that isn't in the DNA Profile
- 🚩 You're generating an image without knowing its exact container dimensions
- 🚩 You're applying the same technique you used on the last project
- 🚩 The enhanced version looks "better" but doesn't feel like the same brand
- 🚩 You're about to embed a `<video>` tag for a scroll-synced animation
- 🚩 Your scroll sequence frames were generated with different base prompts
