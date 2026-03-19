# IRON CANVAS v2 — Agent Quick Reference

## THE PIPELINE

```
ORIENT(0) → STUDY(1) → FEEL(2) → SCOUT(3) → FORGE(4) → GENERATE(5) → COMPOSE(6) → VERIFY(7)
            ↑ GATE 1          ↑ GATE 2               ↑ GATE 3      ↑ GATE 4
```

## PROJECT TYPE ROUTING (Phase 0)

| Type | Emphasis | Scroll Engine | Cursor | Key Stack |
|------|----------|---------------|--------|-----------|
| A: Animated site | SCOUT + COMPOSE | YES | Magnetic | GSAP + Three.js + Lenis + Barba |
| B: Marketing/SaaS | FEEL + FORGE | Optional | Trailing | GSAP + ScrollTrigger + Lenis |
| C: Dashboard | STUDY + SCOUT | NO | None | CSS tokens + micro-interactions |
| D: E-commerce | GENERATE + COMPOSE | YES | Optional | GSAP + Canvas + Leonardo |
| E: Enhancement | STUDY first | Per type | Per type | Match existing |
| F: New scratch | Start at FEEL | Per type | Per type | Determine in Phase 4 |

## PHASE OUTPUTS & GATE SCORES

| Phase | Output | Gate | Pass Threshold |
|-------|--------|------|----------------|
| 1 STUDY | site-dna-profile.json | Gate 1 | 7/7 criteria |
| 2 FEEL | feel-profile.json | — | N/A |
| 3 SCOUT | north-star-reference.png + scout-report.json | Gate 2 | 4/4 |
| 4 FORGE | motion-blueprint.json + tokens.css | Gate 3 | 7/7 |
| 5 GENERATE | artifact set | — | N/A |
| 6 COMPOSE | implementation/ | Gate 4 | ≥ 48/60 |
| 7 VERIFY | verification-report.json | Final | All 5 axes pass |

## THE NORTH STAR IMAGE (Phase 3 Innovation)

Purpose: Generate ONE AI image that synthesizes the design target BEFORE coding.

```
TOOL SELECTION:
- Nano Banana Pro (Gemini 3 Pro): default for UI mockups
- Grok Imagine: bold/expressive concepts
- OpenAI Image 1.5: detailed multi-element layouts
- Leonardo Kino XL: cinematic luxury atmospheres

PROMPT FORMULA:
[Style descriptor] + [Interface type] + [Palette hex] + [Mood] +
[Key visual elements] + [Layout] + [Negative constraints]

VALIDATION (4/5 required):
□ Evokes primary emotion?
□ Avoids all anti-feelings?
□ Palette within ±15% temperature of DNA colors?
□ Density matches brand personality matrix?
□ Client would say "YES, THAT"?
```

## BRAND PERSONALITY MATRIX (Phase 2)

Score 1-10 on each axis — governs everything downstream:

```
minimal ←──────────→ maximal          → animation intensity
serious ←──────────→ playful          → interaction playfulness
classic ←──────────→ avant-garde      → technique selection
digital ←──────────→ organic          → texture/grain decisions
quiet   ←──────────→ bold             → cursor + 3D threshold
fast    ←──────────→ contemplative    → animation timing
```

**Bold axis thresholds:**
- 1-4: No custom cursor | subtle CSS animations
- 5-7: Trailing cursor | GSAP standard stack
- 8-10: Magnetic cursor + WebGL | full GSAP + Three.js

## AI ENGINE QUICK SELECT

| Task | Primary | Alternative |
|------|---------|-------------|
| Product stills / UI mockups | Nano Banana Pro | GPT Image 1.5 |
| North Star (expressive) | Grok Imagine | Nano Banana Pro |
| Video/motion | Kling 3 | Veo 3 |
| Product 360° | Leonardo Product Spin | — |
| Style matching | Leonardo Style Transfer | — |
| Scene lifestyle | Leonardo Product In Scene | — |
| Cross-frame lighting | Leonardo Custom Relight | — |
| Image expansion | Leonardo Instant Outpaint | — |

## SCROLL ENGINE DECISION

```
USE Canvas + ScrollTrigger when:
  - Product showcase with multiple features to reveal
  - Story-driven scroll (ingredients, process, journey)
  - Apple/DJI pattern requested

NEVER use <video> for scroll-driven animation:
  - Can't scrub bidirectionally
  - Can't sync content overlays per-frame
  - Autoplay restrictions on mobile

Frame specs:
  Format: WebP (not PNG — 30-50% smaller)
  Count: 40-60 frames (sweet spot)
  Size: 1920×1080 desktop | 960×540 mobile
  Budget: 50-80KB per frame
  ALWAYS: test 10 frames first before full set
```

## 8 ANTI-PATTERNS (MEMORIZE)

1. Cookie-Cutter — all sites look the same (skip Phase 1 = this)
2. Blind Generation — artifacts without CSS context
3. Template Imposition — forcing a palette/style
4. Batch-and-Pray — all images at once without review
5. Identity Erasure — unrecognizable from original brand
6. Trinket Dropping — images not integrated with CSS
7. Video-as-Animation — MP4 instead of Canvas frames
8. Frame Inconsistency — different prompts per scroll frame

## TASTE DOCTRINE (8 RULES)

1. 3 wow animations > 30 mediocre ones
2. Fix type before adding effects
3. Palette = emotional direction system
4. Animation reveals quality, doesn't create it
5. Design for ONE unforgettable moment
6. Copy technique, not style
7. Best moments must be visible in the 15-second scroll
8. Preserve ONE signature animation on mobile

## FINAL SIGN-OFF AXES

```
Axis 1: Awwwards score     ≥ 7.5/10
Axis 2: Animation quality  ≥ 7/10 checks
Axis 3: Taste Test         7/7 (all must pass)
Axis 4: Performance        ≥ 10/12 checks
Axis 5: Brand DNA match    ≥ 5/7
```

---
*Iron Canvas v2 — Island Development Crew*
