# Anti-Patterns — What Iron Canvas Must NEVER Do

> These are the mistakes that turn premium enhancement into generic destruction. Memorize them.

## The 11 Anti-Patterns (v4)

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
**How to prevent:** Use the Consistency Protocol from Phase 5: SAME base prompt, only vary the action/angle. Or use Keyframe Interpolation (v4): 2 stills → Google Flow → extract frames.

### 9. One-Shot Prompting ★v4
**What it looks like:** Opening a coding editor and typing "build me a SaaS dashboard" then prompting linearly, fixing errors, fighting linters, rewriting components, wondering why the UI keeps drifting.
**Why it happens:** Treating AI coding agents as junior developers who can guess your stack, layout logic, and standards.
**How to prevent:** Iron Canvas's entire pipeline. Discovery Interview (Phase 0) injects business logic. Design PRD (Phase 3.9) is the immutable source of truth. The skill repo IS persistent context that eliminates guessing.

### 10. Skipping Asset Pipeline ★v4
**What it looks like:** Dropping raw video files directly into the page as scroll-driven animation. Files are too heavy, can't control playback with scroll, performance collapses.
**Why it happens:** Not understanding the difference between looping background video and scroll-tied frame sequences.
**How to prevent:** EVERY asset gets classified: scroll-tied → frames at 15fps, looping background → autoplay video, static → optimized image. Never hand raw video to a scroll engine. Classify → optimize → THEN integrate.

### 11. Context Drift ★v4
**What it looks like:** AI agents guess your tech stack, design system, and business logic because you never defined the rules. Each prompt gets further from the original intent. UI drifts over time.
**Why it happens:** No persistent context injection. One-shot prompting without a source of truth.
**How to prevent:** The skill repo is the "universal repository." Discovery Interview captures intent. Design PRD locks in decisions. All agents reference the same tokens and the same PRD. Context drift is structurally impossible when the pipeline is followed.

## Red Flags During Work

If you notice any of these, STOP and reassess:

- 🚩 You haven't looked at the existing site's CSS yet
- 🚩 You're about to use a hex code that isn't in the DNA Profile
- 🚩 You're generating an image without knowing its exact container dimensions
- 🚩 You're applying the same technique you used on the last project
- 🚩 The enhanced version looks "better" but doesn't feel like the same brand
- 🚩 You're about to embed a `<video>` tag for a scroll-synced animation
- 🚩 Your scroll sequence frames were generated with different base prompts
- 🚩 You're prompting "fix the bug" instead of referencing the Design PRD ★v4
- 🚩 You dropped a video file directly into the page without classifying it ★v4
- 🚩 The agent is guessing your intent instead of reading the interview output ★v4

## Craft Wisdom (v4 — from Samir's Applied AI Engineering)

### Feature Discovery Post-Build
After the initial build is stable, ask the agent: "What other features can we add
to make this more appealing?" This often surfaces sound design, custom cursor
refinements, and micro-interactions that weren't in the original scope. These
get implemented in Agent-C's Polish Pass.

### Post-Build Micro-Interaction Pass
Sound design, custom cursors, and micro-interactions are added AFTER the main
build, not during. This prevents scope creep during core development. Agent-C
runs two sweeps: Core Pass (components, layout) → Polish Pass (cursor, hover,
sound, transitions).
