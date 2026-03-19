# Iron Canvas v1 — The Complete Methodology

> **Adaptive Site-Aware Design Enhancement**
> *Make any site the best version of ITSELF.*

---

## Core Philosophy

Iron Canvas is NOT a template. It's a methodology.

Every website has DNA — palette, fonts, imagery style, personality, mood. Iron Canvas reads that DNA first, then enhances within it. The result: three different sites enhanced by Iron Canvas look like three different PREMIUM sites, not three copies of the same dark template.

**The Golden Rule:** Before changing anything — STUDY what's there. Extract. Understand. Then enhance.

---

## The 7-Phase Pipeline

```
STUDY → FEEL → COLLECT → FORGE → GENERATE → COMPOSE → REFINE
  1        2       3        4         5          6        7
```

Each phase has a dedicated guide with step-by-step instructions, checklists, and completion criteria.

---

### Phase 1: STUDY — Read the Site's DNA
📄 **Full guide:** [phases/01-study.md](phases/01-study.md)
📋 **Template:** [templates/site-dna-profile.md](templates/site-dna-profile.md)

Before ANY design work:
1. Screenshot every section (desktop + mobile)
2. Extract CSS custom properties / actual hex codes
3. Identify all fonts and their roles
4. Map every image (position, dimensions, CSS context)
5. Count and name every section
6. Document strengths (preserve these)
7. Document weaknesses (enhance these)

**Output:** A Site DNA Profile with palette, fonts, personality, strengths, weaknesses.

**Completion gate:** Do NOT proceed until the DNA Profile is complete.

---

### Phase 2: FEEL — Discover the Emotional Target
📄 **Full guide:** [phases/02-feel.md](phases/02-feel.md)
📋 **Template:** [templates/feel-profile.md](templates/feel-profile.md)

Understand what the site is TRYING to be emotionally. Don't impose — discover.
1. Read all copy (recurring words, tone, promises, story)
2. Study imagery (temperature, energy, focus, aspiration)
3. Decode palette into emotional signals
4. Synthesize a Feel Profile with 5 components:
   - Primary emotion
   - Secondary emotions
   - Aspirational target
   - Anti-feelings (what it should NEVER evoke)
   - Reference vibe (real-world analogy)

**Output:** A Feel Profile that guides all subsequent decisions.

---

### Phase 3: COLLECT — Find Matching References
📄 **Full guide:** [phases/03-collect.md](phases/03-collect.md)

Find 3-5 reference sites in the same vertical that match THIS site's feel.
1. Identify industry vertical
2. Find best-in-class premium sites in that vertical
3. Screenshot specific elements (not whole pages)
4. Document what to take, why it fits, what adaptation is needed
5. Build a Fit Matrix

**Rule:** Every site gets its OWN references. Never reuse mood boards.

---

### Phase 4: FORGE — Structural Enhancement
📄 **Full guide:** [phases/04-forge.md](phases/04-forge.md)

Upgrade the skeleton. Add universal improvements, adapt to the existing design.

**Always add:**
- Scroll-triggered reveal animations (IntersectionObserver)
- Hover/active/focus states on all interactive elements
- Spring cubic-bezier curves
- Mobile responsive (min-h-[100dvh])
- Grain/noise texture (when appropriate)
- Tinted shadows (using the site's own hues)

**Always adapt (never impose):**
- Typography: enhance the EXISTING fonts
- Colors: use the EXISTING palette
- Layout: enhance the EXISTING structure

---

### Phase 5: GENERATE — Context-Aware Artifact Creation
📄 **Full guide:** [phases/05-generate.md](phases/05-generate.md)
📄 **Prompt guide:** [references/prompt-engineering.md](references/prompt-engineering.md)
📄 **Model guide:** [references/model-selection.md](references/model-selection.md)
📄 **Leonardo guide:** [references/leonardo-blueprints.md](references/leonardo-blueprints.md)

Every artifact is PURPOSE-BUILT for its exact location.

**Before generating any image:** Screenshot the section, document the CSS context, note exact dimensions, study the palette, craft a context-aware prompt.

**Prompt structure:**
```
[Subject] + [Material] + [Colors (hex)] + [Lighting] + [Angle] + [Background] + [Context] + [Negative]
```

**Models:** Nano Banana Pro for stills, Leonardo Blueprints for product workflows, Kling 3/Veo 3 for video, ffmpeg for frame extraction.

**Scroll sequence frames:** Define 8-12 keyframes, use consistency protocol (same base prompt, vary only action), generate 30-60 frames, test 10 before committing all.

**Protocol:** Generate 4 variants → preview all → select best → test in situ → iterate if needed.

---

### Phase 6: COMPOSE — Integration & Scroll Engine
📄 **Full guide:** [phases/06-compose.md](phases/06-compose.md)
📄 **Scroll engine:** [references/scroll-engine.md](references/scroll-engine.md)

**Image integration:** Place → screenshot → evaluate blend → adjust CSS → verify mobile.

**Scroll engine (when applicable):**
- GSAP ScrollTrigger + HTML5 Canvas
- Preload all frames with loading indicator
- Map scroll progress (0→1) to frame index
- Content overlays fade at specific scroll percentages
- Performance: 60fps on M1+, 30fps minimum on older mobile
- Fallback: static hero if frames fail

---

### Phase 7: REFINE — Iterative Polish
📄 **Full guide:** [phases/07-refine.md](phases/07-refine.md)

The loop: **LOOK → REACT → DESCRIBE → FIX → LOOK AGAIN**

Minimum 2 complete passes. Check:
- Identity preservation (still looks like the same brand)
- Visual quality (images blend, typography clear, shadows tinted)
- Interaction quality (hover states, scroll smoothness, touch targets)
- Performance (Lighthouse ≥ 85, LCP < 2.5s)
- Cross-device (desktop, tablet, mobile verified)

---

## Production Branching Protocol

1. **Lock production** before starting (merge to main, deploy)
2. **Work on staging** — all modifications on staging branch only
3. **Visual diff** before promoting (screenshot both side-by-side)
4. **Incremental promotion** — phase by phase, not all at once
5. **Rollback ready** — production must always be deployable

---

## Anti-Patterns
📄 **Full guide:** [references/anti-patterns.md](references/anti-patterns.md)

| # | Don't Do This |
|---|--------------|
| 1 | Cookie-cutter (all sites look the same) |
| 2 | Blind generation (images without context) |
| 3 | Template imposition (forcing a palette) |
| 4 | Batch-and-pray (all images at once) |
| 5 | Identity erasure (unrecognizable result) |
| 6 | Trinket dropping (images that don't integrate) |
| 7 | Video-as-animation (MP4 instead of canvas) |
| 8 | Frame inconsistency (different styles per frame) |

---

## Quick Reference

### Invoke Iron Canvas
📋 **All templates:** [templates/invocation-templates.md](templates/invocation-templates.md)

```
# Full enhancement
"Apply Iron Canvas to [URL]. Start with Phase 1."

# With scroll engine
"Apply Iron Canvas to [URL] with scroll-driven product reveal."

# New site
"Build [project] using Iron Canvas. Start with Phase 2."

# Artifacts only
"Iron Canvas Phase 5 for [site]. Show variants before selecting."
```

### File Structure
```
iron-canvas/
├── README.md                     ← Project overview
├── Iron_Canvas_v1.md             ← THIS FILE (master methodology)
├── CHANGELOG.md                  ← Version history
├── phases/
│   ├── 01-study.md               ← DNA profiling
│   ├── 02-feel.md                ← Emotional target discovery
│   ├── 03-collect.md             ← Reference gathering
│   ├── 04-forge.md               ← Structural enhancement
│   ├── 05-generate.md            ← Artifact creation
│   ├── 06-compose.md             ← Integration + scroll engine
│   └── 07-refine.md              ← Iterative polish
├── references/
│   ├── model-selection.md        ← AI model guide
│   ├── scroll-engine.md          ← GSAP + Canvas deep-dive
│   ├── leonardo-blueprints.md    ← Leonardo AI integration
│   ├── prompt-engineering.md     ← Context-aware prompts
│   └── anti-patterns.md          ← What never to do
└── templates/
    ├── site-dna-profile.md       ← Blank DNA template
    ├── feel-profile.md           ← Blank feel template
    └── invocation-templates.md   ← Copy-paste invocations
```

---

## Origin

Built from production experience at **Island Development Crew** (March 2026):
- **Oakwood AI Hub:** Where uniform templates killed three unique site identities — the lesson that birthed Phase 1
- **Crown Collection:** First full scroll-engine implementation with AI-generated product frames
- **21+ video methodology analysis:** Design engineering, feel-first workflows, iterative screenshot loops
- **Apple AirPods Pro / DJI Mavic 3:** Scroll-driven canvas animation reference implementations

---

*Iron Canvas v1.0 — Island Development Crew*
*"Enhancement means amplifying what's already good, not replacing it with a uniform style."*
