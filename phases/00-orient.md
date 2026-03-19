# Phase 0: ORIENT — Project Classification & Mode Selection

> First action on every Iron Canvas engagement.
> Takes 5 minutes. Saves hours of misdirected effort.

## The Rule

Before any research, before any screenshots, before anything — classify the project and select the execution mode. Every downstream decision depends on getting these two right.

---

## Step 1: Classify the Project Type

Read the project brief, URL, or client description and assign a type:

| Type | Description | Scroll Engine | 3D Eligible | Default Stack |
|------|-------------|--------------|-------------|---------------|
| **A** | Animated site, campaign, portfolio, creative studio | YES | YES (if bold ≥ 8) | ELEVATED / IMMERSIVE |
| **B** | Marketing/SaaS landing page, startup, product launch | Optional | NO | STANDARD |
| **C** | Dashboard, mission control, analytics, admin UI | NO | NO | STANDARD (dark tokens) |
| **D** | E-commerce, product showcase, luxury brand | YES (product reveal) | NO | STANDARD / ELEVATED |
| **E** | Enhancement of existing live site | Per original type | Per original | Match existing |
| **F** | New site from scratch (no existing design) | Per type | Per type | TBD in Phase 4 |

**Type C (Dashboard) note:** Activate the § DASHBOARD ADDENDUM in SKILL.md. Replace scroll physics with panel reveals and data animation patterns.

**Type E note:** Phase 1 STUDY is NON-NEGOTIABLE and must complete before any other phase. Identity Erasure (Anti-Pattern #5) is highest risk here.

**Type F note:** Start at Phase 2 (FEEL), not Phase 1. Use competitor sites for Phase 1 DNA reference.

---

## Step 2: Select Execution Mode

```
SOLO: One agent. Sequential phases. No parallelism.
      Best for: Quick enhancements, small sites, single developer
      Time: Baseline

SWARM: Orchestrator + 4 parallel Build Agents (A, B, C, D).
       Best for: Standard production, most client projects
       Time: 2-3× faster than SOLO

MISSION: Orchestrator + Research + Validation + 5 Build Agents + QA
         Best for: Complex sites, dashboards, flagship Iron Canvas work
         Time: Fastest with highest quality ceiling
```

**Decision guide:**
- Type A (animated site): SWARM recommended, MISSION for flagship
- Type B (marketing): SWARM or SOLO
- Type C (dashboard): MISSION recommended (data + glass + animation all specialized)
- Type D (e-commerce): SWARM (Agent-D is critical for scroll sequence frames)
- Type E (enhancement): SOLO (Phase 1 requires careful sequential study)
- Type F (new scratch): MISSION for best results

---

## Step 3: Define Phase Emphasis

Based on project type, which phases get maximum attention:

```json
{
  "type_A": ["emphasize: Phase 3 SCOUT", "Phase 6 COMPOSE scroll engine", "Phase 4 motion depth"],
  "type_B": ["emphasize: Phase 2 FEEL", "Phase 4 FORGE interactions", "Phase 7 VERIFY conversions"],
  "type_C": ["emphasize: Phase 1 STUDY data hierarchy", "Phase 3 SCOUT mission control refs", "Phase 4 FORGE bento density"],
  "type_D": ["emphasize: Phase 5 GENERATE artifacts", "Phase 6 COMPOSE scroll sequence"],
  "type_E": ["emphasize: Phase 1 STUDY (non-negotiable)", "Phase 4 FORGE (preserve DNA)"],
  "type_F": ["emphasize: Phase 2 FEEL", "Phase 3 SCOUT (references only, no existing site)"]
}
```

---

## Step 4: Record the ORIENT Decision

Output this before proceeding:

```json
{
  "project_name": "",
  "project_type": "A/B/C/D/E/F",
  "type_description": "1-sentence rationale for the type assignment",
  "execution_mode": "SOLO / SWARM / MISSION",
  "mode_rationale": "1-sentence rationale",
  "phase_emphasis": [],
  "agents_to_spawn": [],
  "tech_stack_default": "MINIMAL / STANDARD / ELEVATED / IMMERSIVE",
  "dashboard_route": true,
  "scroll_engine": true,
  "three_js_eligible": false,
  "start_phase": "1 (or 2 for Type F)"
}
```

---

## Tech Stack Default Selection

```
MINIMAL:   CSS animations + Intersection Observer only
           When: Accessibility-critical, fast LCP required, simple content
           LCP: < 1.5s

STANDARD:  GSAP + ScrollTrigger + Lenis + CSS
           When: Most professional sites, SaaS, corporate
           LCP: < 2s

ELEVATED:  GSAP + ScrollTrigger + Lenis + SplitText + Barba.js
           When: Agency sites, portfolios, Awwwards-caliber ambitions
           LCP: < 2.5s

IMMERSIVE: GSAP + Three.js + Lenis + Custom GLSL + Barba.js
           When: Creative studios, campaigns, bold ≥ 8, avant-garde ≥ 8
           LCP: < 3s acceptable (heavy investment payoff)
```

---

## Phase 0 Completion Criteria

- [ ] Project type assigned with rationale
- [ ] Execution mode selected with rationale
- [ ] Phase emphasis defined
- [ ] Tech stack default selected
- [ ] ORIENT decision JSON recorded

**Only proceed to Phase 1 (or Phase 2 for Type F) when complete.**

---
*← Back to [SKILL.md](../SKILL.md) | Next: [Phase 1: STUDY →](01-study.md)*
