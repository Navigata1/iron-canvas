# Anti-Patterns & Design Quality Gates — v4.2

> These are the mistakes that turn premium enhancement into generic destruction. Memorize them.
> Section I covers workflow anti-patterns (process failures).
> Section II covers design-level AI tells (output failures).
> Both sections are mandatory reading for ALL agents at EVERY phase start.

---

## SECTION I: WORKFLOW ANTI-PATTERNS

### The 11 Anti-Patterns (v4)

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

---

## SECTION II: DESIGN SLOP — AI TELLS TO ELIMINATE

> These are the CSS patterns, content patterns, and component patterns that make
> AI-generated output look generic ("slop"). Even when the Iron Canvas pipeline
> is followed perfectly, agents can still produce output with these tells.
> Every agent MUST scan their output against this list before committing.

### Visual & CSS Tells

```
❌ Pure #000000 black anywhere
   → Use off-black (#0a0a0a, #111111), Zinc-950, or charcoal
   → True black creates harsh contrast and screams "default"

❌ Neon / outer glow box-shadows
   → Use inner borders or shadows tinted to the background hue
   → Example: box-shadow: 0 8px 24px oklch(from var(--color-accent) l c h / 0.3)

❌ Default Tailwind shadows (shadow-md, shadow-lg, shadow-xl)
   → Always customize. Tint shadows to background. Use diffused, wide-spread shadows
   → Example: shadow-[0_20px_40px_-15px_rgba(0,0,0,0.05)]

❌ Oversaturated accent colors (saturation > 80%)
   → Desaturate accents to blend with neutrals. One accent max per project

❌ Excessive gradient text on large headers
   → Use gradient text ONLY as a focused accent, never on primary display text

❌ h-screen for full-height sections
   → ALWAYS use min-h-[100dvh] to prevent catastrophic iOS Safari viewport jumping

❌ Complex flexbox percentage math: w-[calc(33%-1rem)]
   → ALWAYS use CSS Grid: grid grid-cols-1 md:grid-cols-3 gap-6

❌ Emojis in code, markup, text content, headings, or alt text
   → Replace with high-quality icons (Phosphor, Radix) or clean SVG primitives

❌ Arbitrary z-index values (z-50, z-[9999])
   → Reserve z-indexes strictly for systemic layers: nav, modals, overlays, tooltips

❌ Animating top, left, width, or height
   → Animate exclusively via transform and opacity for GPU acceleration

❌ backdrop-blur on scrolling containers
   → Apply blur ONLY to fixed/sticky elements (nav, overlays). Scrolling blur = GPU meltdown

❌ Grain/noise overlays on scrolling containers
   → Apply noise to fixed, pointer-events-none pseudo-elements only
```

### Typography Tells

```
❌ Inter font for premium or creative contexts
   → Use: Geist, Outfit, Cabinet Grotesk, Satoshi, Clash Display
   → Inter is acceptable ONLY for functional/data UIs where the BPM scores it
   → NOTE: This is a guardrail, not an absolute ban. If Phase 1 DNA extraction
     finds Inter already in use and the brand identity requires it, preserve it.

❌ Oversized H1s that just "scream"
   → Control hierarchy with weight and color, not just massive scale
   → Use tracking-tighter and font-weight contrast, not font-size alone

❌ System fonts as the only choice (Arial, Helvetica, -apple-system alone)
   → Always self-host or use Google/Variable fonts with font-display: swap

❌ Orphan words in headings (single word on last line)
   → Use text-wrap: balance on headings, or &nbsp; between last two words

❌ Only Regular (400) and Bold (700) weights
   → Introduce Medium (500) and SemiBold (600) for subtle hierarchy

❌ All-caps subheaders everywhere
   → Mix lowercase italics, sentence case, or small-caps for variety

❌ Serif fonts in dashboard/software UIs
   → Serif in dashboards is ALWAYS wrong. Use sans-serif + monospace pairing
   → NOTE: Serif is fine for editorial/creative when BPM avant-garde ≥ 6
```

### Layout Tells

```
❌ Centered Hero when BPM Bold ≥ 5
   → Force split screen (50/50), left-aligned content, or asymmetric whitespace
   → NOTE: Centered IS acceptable for brands with Bold < 5 (refined/conservative)

❌ 3-column equal card feature rows
   → Use 2-column zig-zag, asymmetric grid, masonry, or horizontal scroll
   → The "three equal cards horizontally" is the #1 AI layout fingerprint

❌ Cards of equal height forced by flexbox when content varies
   → Allow variable heights or use masonry when content length differs

❌ Uniform border-radius on everything
   → Vary: tighter on inner elements, softer on containers

❌ Symmetrical vertical padding everywhere
   → Bottom padding often needs to be slightly larger for optical balance

❌ No overlap or depth at all
   → Use negative margins to create layering when appropriate

❌ Buttons not bottom-aligned in card groups
   → Pin CTAs to bottom of cards so they form a clean horizontal line

❌ Edge-to-edge layouts with no max-width
   → Contain with max-w-[1400px] mx-auto or max-w-7xl
```

### Content Tells (The "Jane Doe" Effect)

```
❌ Generic names: "John Doe", "Jane Smith", "Sarah Chan", "Jack Su"
   → Use diverse, creative, realistic-sounding names

❌ Startup slop names: "Acme", "Nexus", "SmartFlow", "TechCorp"
   → Invent premium, contextual brand names

❌ Fake round numbers: 99.99%, 50%, $100.00, 1234567
   → Use organic, messy data: 47.2%, $99.00, +1 (312) 847-1928

❌ AI copywriting clichés
   → BANNED: "Elevate", "Seamless", "Unleash", "Next-Gen", "Game-changer",
     "Delve", "Tapestry", "In the world of...", "Revolutionary"
   → Write plain, specific language. Concrete verbs.

❌ Lorem Ipsum anywhere
   → Write real draft copy that fits the brand context

❌ Broken Unsplash links
   → Use: https://picsum.photos/seed/{contextual_name}/800/600
   → Or: SVG UI Avatars for placeholder avatars

❌ Same avatar image for multiple users
   → Every distinct person needs a unique asset

❌ All blog post dates identical
   → Randomize dates to appear realistic

❌ "Oops!" error messages
   → Be direct: "Connection failed. Please try again."

❌ Exclamation marks in success messages
   → Be confident, not loud

❌ Title Case On Every Header
   → Use sentence case instead
```

### Component Tells

```
❌ Generic card look (border + shadow + white bg) as default
   → Cards exist ONLY when elevation communicates hierarchy
   → For high-density: replace with border-t, divide-y, or negative space

❌ Generic circular spinners for loading
   → Use skeletal loaders matching layout dimensions

❌ Always one filled button + one ghost button
   → Add text links or tertiary styles to reduce visual noise

❌ Accordion FAQ sections as default
   → Try side-by-side list, searchable help, or progressive disclosure

❌ 3-card carousel testimonials with dots
   → Use masonry wall, embedded social posts, or single rotating quote

❌ Modals for everything
   → Use inline editing, slide-over panels, or expandable sections for simple actions

❌ Avatar circles exclusively
   → Try squircles or rounded squares for differentiation

❌ shadcn/ui in its generic default state
   → ALWAYS customize radii, colors, and shadows to match the project aesthetic

❌ Standard Lucide/Feather icons exclusively
   → Use Phosphor, Heroicons, or custom sets. Standardize stroke width globally
```

### External Resource Tells

```
❌ Import hallucinations — importing packages not in package.json
   → ALWAYS check package.json before importing. Output install command if missing

❌ Missing favicon
   → Always include a branded favicon

❌ Missing meta tags
   → Add proper <title>, description, og:image, and social sharing meta

❌ Commented-out dead code
   → Remove all debug artifacts before shipping

❌ Div soup
   → Use semantic HTML: <nav>, <main>, <article>, <aside>, <section>

❌ Hardcoded pixel widths for layout
   → Use relative units (%, rem, em, max-width) for flexible layouts
```

### Red Flags for Design Slop

```
🚩 The output could have been generated by any AI without reading the DNA Profile
🚩 You used Inter/Arial/Helvetica without the DNA Profile specifying it
🚩 You wrote "Lorem ipsum" or "Acme Corp" anywhere
🚩 All your card shadows are default Tailwind values
🚩 Your Hero section is centered text over a dark image
🚩 You have 3 equal cards in a row as a "features" section
🚩 Every number in the UI is a round, fake value
🚩 The loading state is a generic circular spinner
🚩 You used h-screen instead of min-h-[100dvh]
🚩 You imported a library without checking package.json
```

---

*Iron Canvas v4.2 — references/anti-patterns.md*
*Design slop rules derived from taste-skill analysis, adapted to Iron Canvas's DNA-first philosophy*
