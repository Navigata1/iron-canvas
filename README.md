# ⚡ IRON CANVAS — Agent Quick Reference
## *Master Web Experience Skill System v1.0*

---

## SKILL STRUCTURE

```
IRON_CANVAS/
├── SKILL.md                      ← MASTER SKILL (read this first, always)
├── README.md                     ← This file (agent quick reference)
└── sub-skills/
    ├── 01-PERCEPTION.md          ← Protocol 1: Design DNA Extraction
    ├── 02-MOTION-ARCHITECTURE.md ← Protocol 2: Animation Blueprint
    ├── 03-FORGE.md               ← Protocol 3: Production Code Generation
    └── 04-VERIFY.md              ← Protocol 4: 5-Axis Quality Audit
```

---

## AGENT EXECUTION ORDER

**ALWAYS: Read SKILL.md first.**

Then execute sub-skills in sequence:

```
1. 01-PERCEPTION.md   → produces: design_brief.json
   ↓ GATE 1 (7/7 checks)
2. 02-MOTION-ARCHITECTURE.md → produces: motion_blueprint.json
   ↓ GATE 2 (7/7 checks)
3. 03-FORGE.md        → produces: implementation/ (HTML/CSS/JS)
   ↓ GATE 3 (≥48/60 score)
4. 04-VERIFY.md       → produces: verification_report.json
   ↓ GATE 4 (all 5 axes pass)
   → FINAL DELIVERABLE
```

---

## WHEN TO USE WHICH SUB-SKILL

| Situation | Start Here |
|-----------|------------|
| Starting from scratch with video/brief | 01-PERCEPTION |
| Enhancing an existing site | 01-PERCEPTION (analyze existing) |
| DNA extracted, need animation plan | 02-MOTION-ARCHITECTURE |
| Blueprint ready, need to code | 03-FORGE |
| Code complete, need quality check | 04-VERIFY |
| Something failed verification | See remediation table in 04-VERIFY |

---

## TECHNOLOGY QUICK SELECT

```
MINIMAL POLISH NEEDED:
  CSS transitions + Intersection Observer

STANDARD PRODUCTION (most sites):
  GSAP + ScrollTrigger + Lenis + CSS

ELEVATED (agency/portfolio quality):
  GSAP + ScrollTrigger + Lenis + SplitText + Barba.js

IMMERSIVE (WebGL, 3D, award-winning):
  GSAP + Three.js + Lenis + Custom GLSL + Barba.js
```

---

## NON-NEGOTIABLES (Never Skip)

1. **Design tokens first** — Never hardcode colors, spacing, or timing values
2. **Reduced-motion fallback** — Always implement `prefers-reduced-motion`
3. **3-state micro-interactions** — Every button: default, hover, active
4. **Semantic HTML** — Animations never break screen reader experience
5. **Gate checks** — Never proceed past a failed gate without remediation
6. **Typography first** — If the type isn't right, no animation will save it
7. **Performance budget** — LCP < 2.5s, CLS < 0.1, 60fps animations

---

## TASTE DOCTRINE (The 8 Rules)

1. Restraint > Excess — 3 wow animations > 30 mediocre ones
2. Typography IS the design — fix it before adding effects
3. Color tells the emotional story — palette = emotional direction
4. Animation reveals quality, doesn't create it — static must work first
5. Design for ONE unforgettable moment
6. Copy technique, not style — separate method from aesthetic
7. Design for the 15-second scroll — best moments must be visible
8. Mobile is not a downgrade — preserve ONE signature animation on mobile

---

## OUTPUT ARTIFACTS CHECKLIST

Before final delivery, confirm all outputs exist:
- [ ] `design_brief.json`
- [ ] `motion_blueprint.json`
- [ ] `implementation/` (complete, working code)
- [ ] `verification_report.json` (all 5 axes PASS)

---

*Iron Canvas Master Skill v1.0 — Jon's Open Claw Agent*
*Supersedes: frontend-design, canvas-design, algorithmic-art, UX/UI tools, Taste skills*
