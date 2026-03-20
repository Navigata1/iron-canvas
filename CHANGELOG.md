# Changelog

## v4.0.0 — 2026-03-20

### Major: Video Integration + Full v3.1 Wiring + New Asset Engines

Iron Canvas v4 integrates insights from Samir's Applied AI Engineering series,
wires all v3.1 gap-closure reference files into SKILL.md, and adds two new
asset generation engines (Google Whisk + Google Flow).

#### Video Integration (from Samir's 3-video series)
- **Google Whisk** added to Phase 3 SCOUT + Phase 5 GENERATE engine registry
  - Subject image → prompt → cleaned reference → animate → cinematic video loop
- **Google Flow** added to Phase 5 GENERATE for keyframe interpolation
  - Start frame + end frame → interpolated motion video (scroll sequence source)
- **Asset Classification Taxonomy** — every generated asset categorized as:
  - Scroll-tied → extract to JPEG frames at 15fps
  - Looping background → keep as MP4 with autoplay/loop/muted
  - Static → optimized image (WebP/AVIF)
- **Discovery Interview Protocol** added to Phase 0 ORIENT
  - 5-7 structured questions before any code (data origin, priority hierarchy,
    interaction level, responsiveness, competitive positioning, asset inventory,
    performance tier)
- **Screen Recording as Phase 1 Input** — optional input type capturing motion
  timing, scroll behavior, and interaction patterns that screenshots miss
- **Two-Sweep UI Pattern** for Agent-C:
  - Core pass: components, layout, responsive behavior
  - Polish pass: cursor effects, hover states, sound design, loading transitions
- **Enhancement Discovery** added to Phase 7 REFINE — Agent-E suggests additive
  features based on BPM scores and competitive analysis beyond bug fixes
- **BPM-to-Asset-Style Mapping** — Brand Personality Matrix now directly maps to
  asset generation approach (Whisk cinematic vs Flow interpolation vs static)
- 3 new anti-patterns: #9 One-Shot Prompting, #10 Skipping Asset Pipeline,
  #11 Context Drift
- 2 new craft details: Feature Discovery Post-Build, Post-Build Micro-Interaction Pass
- **Agent Autonomy + Self-Provisioning Protocol** (`references/agent-autonomy.md`):
  3-tier system (Supervised / Guided / Autonomous) governing how agents handle
  missing tools, accounts, and API access. Includes stack scanning, dependency
  evaluation, provisioning log, self-improving stack capabilities, and a
  **persistence policy** with retry budgets per complexity class (Simple 3-5,
  Moderate 3-15, Complex 3-unlimited), escalation/reroute protocols, and
  Dead End declaration for genuinely impossible dependencies.

#### v3.1 Reference Wiring (Gap Closure)
All 10 reference files from STRATEGIC_SYNTHESIS.md now wired into SKILL.md:
- `references/typography-system.md` → Phase 2 FEEL output (type_personality field)
- `references/color-system.md` → Phase 2 FEEL output (oklch palette field)
- `references/motion-budget.md` → Phase 2 FEEL output (motion tier field)
- `references/grid-rhythm.md` → Phase 4 FORGE (Agent-A spatial system)
- `references/performance-budget.md` → Phase 0 ORIENT output (performance tier)
- `references/interaction-library.md` → Phase 4/6 (Agent-C state library)
- `references/seo-conversion.md` → Phase 1 + Phase 5 + Phase 7 (OG image + conversion)
- `phases/08-handoff.md` → Pipeline routing in SKILL.md (optional final phase)
- `references/video-integration-protocol.md` → 7 hooks fully populated from transcripts

#### Updated Files (v4)
- `SKILL.md` — Complete v4 rewrite with all wiring + video integration
- `ROUTING.md` — v4 engine registry, Discovery Interview routing, asset taxonomy
- `phases/00-orient.md` — Discovery Interview + performance tier
- `phases/01-study.md` — Screen recording input type
- `phases/02-feel.md` — Typography/color/motion profile output sections
- `phases/03-scout.md` — Whisk + Flow in engine registry
- `phases/05-generate.md` — Keyframe interpolation, asset classification, OG image always
- `phases/06-compose.md` — 15fps frame extraction protocol, asset pipeline verification
- `agent-prompts/orchestrator.md` — Discovery Interview dispatch
- `agent-prompts/agent-c-ui.md` — Two-sweep pattern
- `agent-prompts/agent-d-artifacts.md` — Asset classification + Whisk/Flow
- `agent-prompts/agent-e-qa.md` — Enhancement Discovery + MCP QA path
- `templates/design-prd.md` — Asset Manifest + Framework Config sections
- `templates/invocation-templates.md` — v4 invocation syntax
- `references/anti-patterns.md` — 3 new anti-patterns
- `references/model-selection.md` — Whisk + Flow added
- `references/video-integration-protocol.md` — 7 hooks populated from transcripts

---

## v3.0.0 — 2026-03-19

### Major: Multi-Agent Orchestration System

Iron Canvas is now a full multi-agent design orchestration system, not just a sequential methodology.

#### New Architecture
- **Three execution modes:** SOLO (1 agent sequential), SWARM (parallel build agents), MISSION (full 8-agent team)
- **Phase 3.5 — Cross-LLM Technical Validation:** Dedicated validation agent verifies every planned feature for technical feasibility before any build agent executes. Prevents architecture failures discovered mid-build.
- **Phase 3.9 — Design PRD Packaging:** Orchestrator converts all research into one unified Design PRD consumed by all parallel build agents simultaneously
- **5 specialized Build Agents** with individual system prompts and clearly defined non-overlapping domains (Foundation, Motion, UI/UX, Artifacts, QA)
- **Orchestrator Agent:** New governing role — runs Phases 0-3.9, dispatches PRD, reviews outputs, never writes implementation code directly

#### New Phases
- `00-orient.md` — Project classification and execution mode selection
- `03.5-validate.md` — Cross-LLM technical validation (from Antigravity prompt pattern)
- `03.9-package.md` — Design PRD packaging for agent dispatch

#### New Files
- `agent-prompts/` — Complete system prompts for all 6 agents (Orchestrator + A-E)
- `references/expertise-injection.md` — Domain expertise injection protocol for any API/library
- `templates/design-prd.md` — Complete Design PRD template
- `templates/technical-validation-report.md` — Validation report template

#### Enhanced
- Phase 3 SCOUT: Now generates a North Star image using Nano Banana Pro / Grok Imagine / GPT Image 1.5 as the single visual anchor before any code is written
- Phase 7 VERIFY: Now the full 5-axis Awwwards-grade audit (Design / Animation / Taste / Performance / Brand DNA) with numerical thresholds and exact remediation routing
- Dashboard Addendum: Expanded with bento grid system, glassmorphism card signatures, data animation patterns, and dashboard-specific North Star scout queries

---

## v2.0.0 — 2026-03-19

### Major: Animation Architecture + North Star System

Merged two lineages:
- Island Development Crew production pipeline
- Rigorous animation architecture (Brand Personality Matrix, GSAP taxonomy, Awwwards verification)

---

## v1.0.0 — 2026-03-19

### Initial Release
- Complete 7-phase methodology (STUDY → FEEL → COLLECT → FORGE → GENERATE → COMPOSE → REFINE)
- Production branching protocol (staging → production workflow)
- 8 documented anti-patterns
- Model selection guide
- Invocation templates

---

*Iron Canvas — Island Development Crew*
