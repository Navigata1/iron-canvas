# Changelog

## v4.2.0 — 2026-03-29

### Major: Design Quality Gates + Output Enforcement + Taste-Skill Integration

Iron Canvas v4.2 absorbs best practices from the taste-skill ecosystem (5.5K stars),
adding CSS-level anti-slop enforcement, output completeness rules, and responsive
hardening that prevent agents from producing generic-looking output.

#### Gap 1: Design Slop Anti-Patterns (CRITICAL)
- `references/anti-patterns.md` expanded from workflow-only to dual-section:
  - Section I: 11 workflow anti-patterns (unchanged from v4)
  - Section II: Design-level AI tells — visual/CSS, typography, layout, content,
    component, and external resource patterns that make output look generic
- All agents now load Section II at every phase start

#### Gap 2: Output Enforcement Protocol
- NEW `references/output-enforcement.md` — prevents lazy AI code generation
- Bans: `// ...`, `// TODO`, `// rest of code`, skeleton outputs, "for brevity"
- Agent-specific enforcement rules for Agents A through E
- Token limit handling: clean breakpoints with PAUSED protocol

#### Gap 3: Interactive State Mandate
- Agent-C upgraded to require ALL 5 states on every element (default/hover/focus/active/disabled)
- Loading, empty, and error states are now REQUIRED deliverables (not optional)
- No circular spinners. No "Oops!" messages. No dead-end empty states.

#### Gap 4: High-End Component Patterns
- `references/interaction-library.md` expanded with:
  - Double-Bezel ("Doppelrand") card architecture
  - Button-in-Button trailing icon pattern
  - Liquid Glass refraction panel
  - Fluid Island navigation with hamburger morph
  - Eyebrow tags (section preheaders)

#### Gap 5: Dependency Verification
- Agent-A now MUST check package.json before importing any library
- Tailwind version lock (v3 vs v4 syntax check)
- RSC safety rules for Next.js projects

#### Gap 6: Responsive Hardening
- `references/grid-rhythm.md` Step 7 added with non-negotiable mobile rules
- 44px touch targets, single-column collapse below 768px, clamp() typography
- Container constraints, no horizontal overflow, image behavior on mobile

#### Gap 7: React/Next.js Motion Rules
- `references/motion-budget.md` expanded with React-specific performance rules
- GSAP vs Framer Motion separation (never mixed in same component tree)
- useMotionValue/useTransform for continuous animations (not useState)
- Perpetual motion isolation in React.memo components
- Mandatory useEffect cleanup with gsap.context()

#### Gap 8: Creative Arsenal Named Patterns
- `references/interaction-library.md` expanded with 30+ named patterns
- Organized by category: Navigation, Layout, Cards, Scroll, Gallery, Typography, Micro
- Each pattern has a minimum motion tier requirement
- Agents can reference patterns by name during Phase 5/6

#### Gap 9: Bento Motion Engine Card Archetypes
- Dashboard Addendum in SKILL.md expanded with 5 specific card archetypes:
  - The Intelligent List, The Command Input, The Live Status,
    The Wide Data Stream, The Contextual UI
- Performance rules for perpetual dashboard animations

#### Gap 10: Design Quality Gate in Phase 7
- `phases/07-refine.md` expanded with comprehensive anti-slop audit checklist
- Typography, Color, Layout, Content, Component, Code Quality, Strategic checks
- Runs AFTER refinement loop, BEFORE promotion to production
- Agent-E now runs this gate as final check before Orchestrator verification

#### Agent Prompt Updates
- All 6 agent prompts updated to v4.2 with new READ references
- Orchestrator: loads anti-patterns + output-enforcement at pipeline start
- Agent-A: dependency verification, responsive hardening, design quality gates
- Agent-B: React/Next.js motion rules
- Agent-C: 5-state mandate, Double-Bezel/Button-in-Button patterns, state completeness
- Agent-D: output enforcement references
- Agent-E: Design Quality Gate as final audit step

#### Files Modified (13)
- `SKILL.md` — Design slop + output enforcement + dependency verification + responsive
  hardening + state mandate + bento archetypes added inline (self-containment rule)
- `ROUTING.md` — New file references added
- `CHANGELOG.md` — This entry
- `references/anti-patterns.md` — Section II added (design slop AI tells)
- `references/interaction-library.md` — High-end patterns + creative arsenal
- `references/grid-rhythm.md` — Step 7 responsive hardening
- `references/motion-budget.md` — React/Next.js motion rules
- `phases/07-refine.md` — Design Quality Gate checklist
- `agent-prompts/orchestrator.md` — v4.2 with new mandatory loads
- `agent-prompts/agent-a-foundation.md` — dependency verification + responsive
- `agent-prompts/agent-b-motion.md` — React motion rules
- `agent-prompts/agent-c-ui.md` — state mandate + high-end patterns
- `agent-prompts/agent-d-artifacts.md` — output enforcement
- `agent-prompts/agent-e-qa.md` — Design Quality Gate

#### Files Created (1)
- `references/output-enforcement.md` — NEW

---

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
