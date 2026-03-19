# Changelog

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

#### Methodology Advances from Antigravity Pattern Analysis
- Parallel agent dispatch after Design PRD packaging (Prompt 2 adapted)
- Cross-LLM validation before build phase (Prompt 3 adapted)
- Expertise injection before specialized agent execution (Prompt 7 adapted)
- Feature ideation → document packaging → validation → parallel build → verify (complete workflow)
- Narrated scroll experience with WebSocket TTS as first-class use case

---

## v2.0.0 — 2026-03-19

### Major: Animation Architecture + North Star System

Merged two lineages:
- Island Development Crew production pipeline
- Rigorous animation architecture (Brand Personality Matrix, GSAP taxonomy, Awwwards verification)

#### New
- Brand Personality Matrix (6-dimension scoring system governing all downstream decisions)
- Phase 3 SCOUT: AI Reference Intelligence with North Star image generation
- 5-axis Awwwards verification system
- Dashboard Addendum
- Technology decision tree (Minimal / Standard / Elevated / Immersive)
- Gate system with numerical thresholds across 4 checkpoints

---

## v1.0.0 — 2026-03-19

### Initial Release
- Complete 7-phase methodology (STUDY → FEEL → COLLECT → FORGE → GENERATE → COMPOSE → REFINE)
- Phase 1 STUDY: Site DNA profiling (palette, fonts, imagery, personality extraction)
- Phase 2 FEEL: Emotional target discovery from existing site signals
- Phase 3 COLLECT: Industry-matched reference gathering
- Phase 4 FORGE: Structural enhancement with taste skill integration
- Phase 5 GENERATE: Context-aware artifact creation with multi-model support
  - Nano Banana Pro (Gemini 3 Pro Image) integration
  - Leonardo AI Blueprints workflow accelerators
  - Scroll sequence frame generation protocol
  - Prompt engineering for context-aware artifacts
- Phase 6 COMPOSE: Visual verification + GSAP ScrollTrigger + HTML5 Canvas scroll engine
- Phase 7 REFINE: Iterative polish loop with per-site quality checklists
- Production branching protocol (staging → production workflow)
- 8 documented anti-patterns
- Model selection guide (stills, video, rotation, style transfer, relighting)
- Invocation templates for common workflows
- Site DNA profile and feel profile templates
