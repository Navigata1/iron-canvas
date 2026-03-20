---
name: iron-canvas-master
version: 4.0
description: >
  Iron Canvas is an adaptive, site-aware, multi-agent design enhancement and
  creation methodology. It is not a template — it is an orchestration system.

  Three lineages fused into one definitive methodology:
  (A) Island Development Crew production pipeline — 7-phase battle-tested system
      from real projects: Oakwood AI Hub, Crown Collection, Iron Canvas Studio site.
  (B) Rigorous animation architecture — Brand Personality Matrix, GSAP motion taxonomy,
      Awwwards 5-axis verification, AI Reference Scout with North Star image generation.
  (C) Antigravity multi-agent orchestration pattern — parallel Build Agents, Cross-LLM
      Technical Validation, Design PRD Packaging, Expertise Injection Protocol.

  v4 additions from Samir's Applied AI Engineering series:
  (D) Google Whisk + Google Flow asset engines for motion-first generation.
  (E) Discovery Interview protocol before any code.
  (F) Asset classification taxonomy (scroll-tied / looping / static).
  (G) Keyframe interpolation pipeline (start frame + end frame → video → frames).
  (H) Two-sweep UI polish pattern (core + polish passes).
  (I) Enhancement Discovery in QA phase.
  (J) Full wiring of v3.1 gap-closure reference files.

  Three modes:
    SOLO:    One agent, full pipeline, sequential execution.
    SWARM:   Orchestrator + up to 5 parallel Build Agents.
    MISSION: Full team — Orchestrator + Research + Validation + 5 Build Agents + QA.

  Trigger for ANY digital design task: websites, dashboards, apps, scroll animations,
  mission controls, landing pages, or brand experiences.
  Runs natively in: OpenClaw, Antigravity Agent Manager, Claude Code, any agentic AI.

author: Iron Canvas — Island Development Crew
origin: >
  "Where there is no vision, the people perish." — Proverbs 29:18 (KJV)
---

# ⚡ IRON CANVAS v4
## *The Multi-Agent Design Orchestration System*

> **The Golden Rule:** Before changing anything — STUDY what's there.
> Extract. Understand. Then enhance.
>
> "Your coding agents are only as good as the instructions and the
> assets you feed them." — Samir (Applied AI Engineering)
>
> "Enhancement means amplifying what's already good, not replacing it
> with a uniform style."


---

## ═══════════════════════════════════════════════════
## THE COMPLETE PIPELINE — ALL THREE MODES
## ═══════════════════════════════════════════════════

### SOLO MODE (1 agent, sequential)
```
ORIENT(0)→STUDY(1)→FEEL(2)→SCOUT(3)→VALIDATE(3.5)→PACKAGE(3.9)→FORGE(4)→GENERATE(5)→COMPOSE(6)→VERIFY(7)→HANDOFF(8)
```

### SWARM MODE (1 orchestrator + parallel build agents)
```
                    ┌─ ORCHESTRATOR ─────────────────────────────────────────────┐
                    │                                                             │
ORIENT(0)→INTERVIEW→STUDY(1)→FEEL(2)→SCOUT(3)→VALIDATE(3.5)→PACKAGE(3.9)      │
                    │           ↓ Design PRD dispatched to all agents simultaneously  │
                    │  ┌─────────────────────────────────────────────────────┐   │
                    │  │  AGENT-A       AGENT-B       AGENT-C       AGENT-D  │   │
                    │  │  Foundation    Motion        UI/UX         Artifacts │   │
                    │  │  (tokens +     (GSAP +       (components   (image    │   │
                    │  │   structure)    scroll)       + cursor)     gen)     │   │
                    │  └──────┬──────────┬─────────────┬────────────┬────────┘   │
                    │         └──────────┴─────────────┴────────────┘            │
                    │                           ↓ MERGE                          │
                    │                    COMPOSE(6) + VERIFY(7) + HANDOFF(8)     │
                    └────────────────────────────────────────────────────────────┘
```

### MISSION MODE (full team, maximum power)
```
┌─ ORCHESTRATOR (Claude Opus) ─────────────────────────────────────────────────────┐
│                                                                                    │
│  [DISCOVERY INTERVIEW] → Client/project discovery (5-7 questions) ─────────┐    │
│                                                                              │    │
│  [RESEARCH AGENT]──STUDY(1)──FEEL(2)──SCOUT(3)──────────────────────────┐  │    │
│                                                                           │  │    │
│  [VALIDATION AGENT]──Cross-LLM Technical Check───────────────────────┐  │  │    │
│                                                                        │  │  │    │
│  ──────── PACKAGE(3.9): Design PRD issued to all Build Agents ───────┘  │  │    │
│                                                                          │  │    │
│  ┌──AGENT-A──┐  ┌──AGENT-B──┐  ┌──AGENT-C──┐  ┌──AGENT-D──┐  ┌─AGENT-E─┐    │
│  │Foundation  │  │  Motion   │  │  UI/UX    │  │ Artifacts  │  │ A11y +  │    │
│  │Tokens+HTML │  │GSAP+3D+   │  │Core Pass  │  │Whisk+Flow+ │  │Perf+QA  │    │
│  │Structure   │  │ScrollEng  │  │Polish Pass│  │Scroll Seq  │  │Enhance  │    │
│  └─────┬──────┘  └─────┬─────┘  └─────┬─────┘  └─────┬──────┘  └────┬────┘    │
│        └───────────────┴───────────────┴──────────────┴──────────────┘          │
│                                         ↓                                        │
│                           [MERGE + VERIFY + HANDOFF]                             │
│                           COMPOSE(6) + 5-AXIS AUDIT(7) + HANDOFF(8)             │
└──────────────────────────────────────────────────────────────────────────────────┘
```

---

## ═══════════════════════════════════════════════════
## SECTION 1: ORCHESTRATOR AGENT
## ═══════════════════════════════════════════════════
### *The Architect — Never Writes Code, Only Governs*

The Orchestrator is the master agent. It is the Mission Controller. Its job:
1. Run the Discovery Interview (v4 — before Phase 1)
2. Run Phases 0-3.9 (research + feel + scout + validation + packaging)
3. Issue the Design PRD to specialized Build Agents
4. Monitor Build Agent progress and resolve conflicts
5. Run Phase 7 verification across all agent outputs
6. Run Phase 8 handoff for client deliverables
7. Deliver the final product

**Orchestrator system prompt:**
```markdown
You are the Iron Canvas Orchestrator. You are an expert design engineer and
creative director for the Iron Canvas design studio. Your role is to:

1. Run Discovery Interview (5-7 structured questions before any code)
2. Run Phases 0-3.9 (ORIENT through PACKAGE)
3. Produce: site-dna.json, feel-profile.json, north-star.png,
   validation-report.md, design-prd.md
4. Dispatch Design PRD to Build Agents simultaneously
5. Review outputs, resolve integration conflicts, compose final deliverable
6. RUN Phase 5 Artifact Assessment Gate — MANDATORY, never skip
7. RUN Phase 6 integration — MANDATORY, never skip
8. Run Phase 7: 5-axis Awwwards-grade verification + Enhancement Discovery
9. Run Phase 8: Client handoff (when client_handoff: true)

You NEVER write implementation code yourself — you architect, design, and judge.
Model recommendation: Claude Opus / Gemini 3 Pro Deep Think (highest reasoning)
```

---

## ═══════════════════════════════════════════════════
## SECTION 2: PHASE 0 — ORIENT + DISCOVERY INTERVIEW
## ═══════════════════════════════════════════════════
### *Project Classification, Mode Selection, Performance Tier*

**v4 ADDITION: DISCOVERY INTERVIEW**
Before any code, the Orchestrator conducts a 5-7 question structured interview:

```
Q1: DATA ORIGIN — Where does content come from? (CMS, static, API, manual)
Q2: PRIORITY HIERARCHY — What are the top 3 things a visitor must see/do?
Q3: INTERACTION LEVEL — Passive consumption vs. active engagement?
Q4: RESPONSIVENESS — Mobile-first? Desktop-dominant? Parity?
Q5: COMPETITIVE POSITIONING — What should this feel better than?
Q6: ASSET INVENTORY — What visual assets exist? What must be generated?
Q7: PERFORMANCE TIER — Speed-critical? Motion-heavy? Balanced?
```

The interview output feeds directly into the Site DNA Profile and orient-decision.json.

**ORIENT OUTPUT (v4):**
```json
{
  "project_type": "A/B/C/D/E/F",
  "execution_mode": "SOLO / SWARM / MISSION",
  "phase_emphasis": [],
  "agent_team": [],
  "tech_stack_default": "MINIMAL / STANDARD / ELEVATED / IMMERSIVE",
  "client_handoff": false,
  "interview_summary": {
    "data_origin": "",
    "priority_hierarchy": [],
    "interaction_level": "",
    "responsiveness": "",
    "competitive_positioning": "",
    "asset_inventory": "",
    "performance_tier": ""
  },
  "performance": {
    "tier": "1 | 2 | 3",
    "lcp_target": "2.5s",
    "font_strategy": "self-hosted | variable | google",
    "three_js_allowed": false,
    "scroll_sequence_format": "webp-frames | video | none",
    "bundle_budget_kb": 150
  },
  "agent_autonomy": {
    "tier": "1 | 2 | 3",
    "tier_label": "SUPERVISED | GUIDED | AUTONOMOUS",
    "set_date": "2026-03-20",
    "operator_note": "",
    "persistence": {
      "class_a_budget": 5,
      "class_b_budget": "8 | 15",
      "class_c_budget": "12 | unlimited",
      "class_c_mode": "escalate | resolve_or_dead_end"
    }
  }
}
```

**PROJECT TYPE ROUTING:**
```
A  Animated site / campaign / portfolio   → SWARM recommended
B  Marketing / SaaS landing page          → SWARM or SOLO
C  Dashboard / Mission Control / App UI   → MISSION recommended (see § DASHBOARD)
D  E-commerce / product showcase          → SWARM (GENERATE agent critical)
E  Enhancement of existing site          → SOLO (Phase 1 non-negotiable first)
F  New site from scratch                 → MISSION
```

**AGENT AUTONOMY TIER (v4 — from references/agent-autonomy.md):**
```
TIER 1 — SUPERVISED: Ask before any account creation, installation, or payment.
TIER 2 — GUIDED:     Self-provision free tools/accounts. Ask before anything paid.
TIER 3 — AUTONOMOUS: Use judgment. Sign up, install, configure as needed. Log everything.
```
Each tier has a **persistence policy** — retry budgets based on blocker complexity:
- Class A (simple): 3-5 attempts then escalate or reroute
- Class B (moderate): 3-15 attempts depending on tier
- Class C (complex): 3-12 attempts (Tier 1-2) or unlimited (Tier 3, with Dead End protocol)

Each retry must be a **meaningfully different approach**, not the same command repeated.
The build is NEVER fully blocked — there is always a fallback path.
Set once per operator. Stored in orient-decision.json → agent_autonomy field.
All agents run a STACK SCAN at phase start — checking installed tools, API keys,
and credentials against what the Design PRD requires. Gaps are resolved per tier.
→ READ: references/agent-autonomy.md for full provisioning protocol.

**PERFORMANCE TIER SELECTION (v4 — from references/performance-budget.md):**
```
TIER 1 — MARKETING (LCP < 2.5s, max 150KB JS, no Three.js)
TIER 2 — ANIMATED (LCP < 3.5s, max 300KB JS, Three.js if avant-garde ≥ 8)
TIER 3 — IMMERSIVE (LCP < 4.0s, progressive enhancement, WebGL scenes)
```

Performance tier gates ALL downstream agent decisions.
→ READ: references/performance-budget.md for full specs.

---

## ═══════════════════════════════════════════════════
## SECTION 3: PHASES 1-3 — THE RESEARCH TRIAD
## ═══════════════════════════════════════════════════

### PHASE 1: STUDY — Read the Site's DNA

> **Do NOT touch anything until this phase is complete.**

**v4 ADDITION: SCREEN RECORDING INPUT**
When enhancing an existing site, an optional screen recording of the target
captures motion timing, scroll behavior, and interaction patterns that
screenshots miss. When provided, extract:
- Scroll-to-animation timing relationships
- Transition durations and easing curves
- Interaction trigger points
- Content reveal sequences

**v4 ADDITION: CONVERSION QUESTIONS (from references/seo-conversion.md)**
After DNA extraction, answer these 5 conversion questions:
```
Q1: What is the PRIMARY conversion? (one answer only)
Q2: What is the SECONDARY conversion?
Q3: What is the value proposition in 6 words or less?
Q4: What are the 3 trust signals?
Q5: What is the friction? (count clicks to primary conversion)
```

Full Phase 1 protocol: → phases/01-study.md
DNA output template: → templates/site-dna-profile.md

---

### PHASE 2: FEEL — Discover the Emotional Target + Design Systems

> The emotional target comes FROM the site. You are a detective, not an art director.

**Brand Personality Matrix (6 axes, scored 1-10):**
```
minimal ←──────────→ maximal          → animation intensity
serious ←──────────→ playful          → interaction playfulness
classic ←──────────→ avant-garde      → technique selection + 3D threshold
digital ←──────────→ organic          → texture/grain decisions
quiet   ←──────────→ bold             → cursor + WebGL threshold
fast    ←──────────→ contemplative    → animation timing
```

**v4: FEEL PROFILE now includes 4 system outputs:**

```json
{
  "feel": { "primary_emotion": "", "anti_feelings": [], "reference_vibe": "" },
  "brand_personality_matrix": { "minimal_vs_maximal": 5, "...": 5 },
  "typography": {
    "personality": "EXPRESSIVE | EDITORIAL | COMMANDING | REFINED | FUNCTIONAL",
    "display_font": "", "body_font": "", "accent_font": "",
    "display_entry_animation": "char-stagger | word-fade | block-fade | none",
    "heading_tracking": "-0.03em", "body_line_height": "1.7"
  },
  "color": {
    "primary_oklch": "oklch(0.55 0.18 260)",
    "harmony": "analogous | complementary | monochromatic",
    "gradient_mesh": true, "mesh_intensity": "deep | vibrant | light | none",
    "grain_overlay": true, "grain_opacity": 0.04,
    "shadow_tint": true, "dark_mode": false
  },
  "motion": {
    "tier": "1 | 2 | 3 | 4",
    "hero_animation": "fade | type-reveal | full-choreography | immersive",
    "scroll_sequences": false, "magnetic_cursor": false,
    "three_js": false, "page_transitions": false
  },
  "layout": {
    "spacing_scale": "8pt | modular | golden | freeform",
    "column_system": "12-col | asymmetric | sidebar | bento",
    "container_max": "1280px", "section_rhythm": "standard | contrast-heavy | editorial"
  }
}
```

**v4: BPM-TO-ASSET-STYLE MAPPING (from video integration):**
```
Bold 8-10 + Avant-garde 8-10 → Custom 3D, WebGL, Whisk cinematic loops
Bold 5-7 + Refined 6-10      → Flow interpolation, subtle parallax frames
Bold 1-4 + Classic 7-10      → Static hero images, minimal motion
Playful 7-10                  → Animated illustrations, GIF-style loops
Serious 8-10 + Technical 7-10 → Data visualization, clean transitions
```

→ READ: references/typography-system.md, references/color-system.md,
         references/motion-budget.md, references/grid-rhythm.md

---

### PHASE 3: SCOUT — AI Reference Intelligence + North Star

> ONE AI-generated image that synthesizes the design target before coding.

**v4: AI ENGINE REGISTRY (expanded with Whisk + Flow):**

| Engine | Type | Best For | Phase |
|--------|------|----------|-------|
| Nano Banana Pro | Image | Product shots, UI mockups, brand imagery | 3, 5 |
| Leonardo Kino XL | Image + Video | Blueprint workflows, product spins | 5 |
| Grok Imagine | Image | Conceptual, abstract, bold/expressive | 3 |
| GPT Image 1.5 | Image | Photorealistic, detailed layouts | 3, 5 |
| **Google Whisk** | Image → Video | Reference cleanup, cinematic loops, animate stills | **3, 5** |
| **Google Flow** | Video (interpolation) | Scroll transitions, keyframe morphs | **5** |
| Kling 3 | Video | Motion sequences | 5 |
| Veo 3 | Video | Alternative motion | 5 |

**v4: KEYFRAME INTERPOLATION METHOD (from video integration)**
```
1. Generate START FRAME (Whisk/Nano Banana — the "before" state)
2. Generate END FRAME (Whisk/Nano Banana — the "after" state)
3. Feed both to Google Flow → "Frames to Video" mode
4. Flow interpolates smooth motion between the two states
5. Extract frames from interpolated video at 15fps
6. Result: scroll sequence source material from just 2 AI images
```

This is the most efficient path to scroll-sequence source material.
It replaces generating 60 individual frames with prompts.

Full Phase 3 protocol: → phases/03-scout.md

---

## ═══════════════════════════════════════════════════
## SECTION 4: PHASE 3.5 — CROSS-LLM TECHNICAL VALIDATION
## ═══════════════════════════════════════════════════

*(Unchanged from v3 — see phases/03.5-validate.md)*
No Build Agent executes until the Validation Agent signs off.

---

## ═══════════════════════════════════════════════════
## SECTION 5: PHASE 3.9 — DESIGN PRD PACKAGING
## ═══════════════════════════════════════════════════

*(Core unchanged from v3 — see phases/03.9-package.md)*

**v4 ADDITIONS to PRD Template (templates/design-prd.md):**

**NEW: Section 6a — Asset Manifest**
```markdown
## SECTION 6a: ASSET MANIFEST
Every video, image sequence, and static asset with exact paths:

| Asset | Type | Path | Optimization | Category |
|-------|------|------|-------------|----------|
| hero-loop.mp4 | Video | /public/videos/ | autoplay+loop+muted | Looping background |
| product-scroll/ | Frames | /public/sequences/ | 15fps JPEG extraction | Scroll-tied |
| hero-product.webp | Image | /public/images/ | WebP optimized | Static |
```

**NEW: Section 6b — Framework Configuration**
```markdown
## SECTION 6b: FRAMEWORK CONFIGURATION
- Framework: Next.js 14 / Vanilla / React
- Tailwind: v4 config specifics (if applicable)
- Build tool: Vite / Webpack / Turbopack
- Deploy target: Vercel / Netlify / Static
- CSS approach: Global tokens + component scoped
```

---

## ═══════════════════════════════════════════════════
## SECTION 6: THE BUILD AGENTS — PARALLEL EXECUTION
## ═══════════════════════════════════════════════════
### *Dispatched simultaneously. Each receives the full Design PRD.*

---

### AGENT-A: FOUNDATION
*Tokens, HTML Architecture, Structural Skeleton*
*(Core unchanged from v3 — see agent-prompts/agent-a-foundation.md)*

**v4: Agent-A also reads:**
- references/grid-rhythm.md → spacing scale + column system
- references/color-system.md → oklch palette + gradient mesh
- references/typography-system.md → font loading protocol
- feel-profile.json → typography, color, motion, layout fields

**v4: Dark mode generation trigger:**
When feel-profile.json → color.dark_mode: true OR Brand Personality bold ≥ 6:
Agent-A generates `tokens-dark.css` alongside `tokens.css`.

---

### AGENT-B: MOTION
*GSAP Animation System, Scroll Engine, Load Sequence, Page Transitions*
*(Core unchanged from v3 — see agent-prompts/agent-b-motion.md)*

**v4: Agent-B reads motion tier from feel-profile.json BEFORE writing any GSAP:**
- Tier 1: CSS transitions + Intersection Observer only
- Tier 2: GSAP + ScrollTrigger + selective animation (3-4 moments per page)
- Tier 3: Full GSAP + scroll engine + cursor + page transitions
- Tier 4: Everything in Tier 3 + Three.js + GLSL + audio

→ READ: references/motion-budget.md for full tier specs

---

### AGENT-C: UI/UX — v4 TWO-SWEEP PATTERN
*Components, Cursor, Navigation, Micro-interactions, Typography*

**v4 CHANGE: Agent-C runs TWO passes, not one:**

```
SWEEP 1 — CORE PASS:
  Components, layout, responsive behavior, 3-state interactions,
  navigation, form states, empty states, loading states.
  → Output: components.css, interactions.js, typography.js

SWEEP 2 — POLISH PASS (after core is stable):
  Cursor effects, hover refinements, sound design, loading transitions,
  micro-interaction tuning, animation timing polish, toast patterns.
  → Output: polish.css, polish.js (additive, never overrides core)
```

This prevents scope creep during core development. The polish pass
happens AFTER the main build is stable, not interleaved with it.

→ READ: references/interaction-library.md for all state patterns

---

### AGENT-D: ARTIFACTS — v4 ASSET CLASSIFICATION
*AI Image Generation, Scroll Frame Sequences, Video Loops*

**v4: Agent-D must classify EVERY generated asset into one of three categories:**

```
CATEGORY 1: SCROLL-TIED
  → Convert source video to individual JPEG frames at 15fps
  → 15fps is the sweet spot (smooth without file bloat — from Samir's workflow)
  → Storage: /public/sequences/{sequence-name}/frame-001.jpg
  → Canvas component draws frames tied to ScrollTrigger progress

CATEGORY 2: LOOPING BACKGROUND
  → Keep as MP4 video, browser handles playback
  → Attributes: autoplay + loop + muted + playsinline
  → z-index behind content, CSS opacity filters for readability
  → Each section gets its own contextual background asset (not just hero)

CATEGORY 3: STATIC
  → Optimized image (WebP/AVIF)
  → loading="lazy" for below-fold, "eager" for hero
  → Responsive srcset for different viewports
```

**v4: New generation engines:**

```
Google Whisk:
  Input: subject image + text prompt → cleaned reference OR animated video loop
  Access: Google Whisk in browser
  Best for: Cleaning reference images, generating cinematic looping backgrounds
  Phase 3: North Star cleanup (remove text from Pinterest refs)
  Phase 5: Background loops (oscilloscope, matrix rain, particle systems)

Google Flow:
  Input: start frame image + end frame image → interpolated video
  Access: Google Flow in browser, "Frames to Video" mode
  Best for: Scroll transition source material from just 2 AI stills
  Phase 5: The most efficient path to scroll sequences
  Workflow: Generate 2 keyframes → Flow interpolation → extract at 15fps
```

**v4: Agent-D also generates section-specific background assets:**
"A great hero section is not enough — the entire site must breathe the same DNA."
Every section gets its own contextual background asset when motion tier ≥ 2.

→ READ: agent-prompts/agent-d-artifacts.md for full v4 prompt

---

### AGENT-E: QA + ACCESSIBILITY — v4 ENHANCEMENT DISCOVERY
*Performance Audit, Cross-Browser Check, Accessibility + Enhancement Suggestions*

**v4 ADDITION: Enhancement Discovery**
After completing the standard QA audit, Agent-E runs an Enhancement Discovery pass:

```
ENHANCEMENT DISCOVERY PROTOCOL:
1. Read the Brand Personality Matrix scores
2. Read the competitive analysis from Phase 3
3. Ask: "What additive features would elevate this beyond the current build?"
4. Suggest 3-5 enhancements with effort/impact scores:
   - Sound design (ambient audio, interaction sounds)
   - Custom cursor refinements
   - Micro-interaction additions
   - Additional scroll-triggered moments
   - Loading experience polish
5. Orchestrator decides which to implement in the Polish Pass
```

This turns QA from a gate into a creative amplifier — beyond just bug fixes.

**v4: MCP-Based QA Tooling (optional)**
When available (e.g., TestSprite MCP server):
1. Feed the Design PRD from Phase 3.9 as test context
2. Auto-generate test cases from requirements
3. Run automated accessibility, performance, and visual regression tests
4. Generate fix report → route back to relevant Build Agent

---

## ═══════════════════════════════════════════════════
## SECTION 7: PHASE 5 — GENERATE (ARTIFACT ASSESSMENT GATE)
## ═══════════════════════════════════════════════════

> ⚠️ THIS PHASE IS NEVER OPTIONAL.

**v4: OG Image is ALWAYS generated regardless of Assessment Gate score.**
```
OG Image: 1200×630px, brand-matched social share image.
Engine: Nano Banana Pro or GPT Image 1.5
Every Iron Canvas build produces an OG image. No exceptions.
```

**v4: Keyframe Interpolation added as generation method:**
```
METHOD 1: Individual frame prompting (v3 — one prompt per frame)
METHOD 2: Video extraction (v3 — Product Spin Video → ffmpeg)
METHOD 3: Keyframe Interpolation (v4 — 2 stills → Google Flow → 15fps extraction)
```

Method 3 is the recommended default for scroll sequences in v4.
It produces more natural motion than individual prompts and is faster.

Full Phase 5 protocol: → phases/05-generate.md

---

## ═══════════════════════════════════════════════════
## SECTION 8: PHASE 6 — COMPOSE (MERGE + INTEGRATE)
## ═══════════════════════════════════════════════════

> ⚠️ THIS PHASE IS NEVER OPTIONAL.

**v4: FRAME EXTRACTION PROTOCOL**
```
SOURCE VIDEO → FRAMES:
1. Source: Whisk animate output, Flow interpolation, or existing footage
2. Tool: ffmpeg or browser-based converter (e.g., EasyGIF)
3. Frame rate: 15fps (NOT 30fps — half the file count, visually identical on web)
4. Format: JPEG for scroll sequences (smaller than WebP for individual frames)
5. Naming: {sequence-name}-{NNN}.jpg (zero-padded 3 digits)
6. Storage: /public/sequences/{sequence-name}/
7. Preloading: First 10 frames eager, remainder lazy ±8 from position
8. Canvas binding: GSAP ScrollTrigger → frame index = Math.floor(progress * totalFrames)

ffmpeg command:
  ffmpeg -i source.mp4 -vf "fps=15,scale=1920:1080" frames/frame_%03d.jpg
  ffmpeg -i source.mp4 -vf "fps=15,scale=960:540" frames-mobile/frame_%03d.jpg
```

**v4: ASSET PIPELINE VERIFICATION (Agent-A runs before scaffolding):**
Before any agent writes code:
1. Verify all generated assets exist in `/public/`
2. Confirm sequence folders are numbered correctly
3. Validate video files have correct codec/format for web
4. Create asset manifest JSON listing all resources and their categories

Full Phase 6 protocol: → phases/06-compose.md

---

## ═══════════════════════════════════════════════════
## SECTION 9: PHASE 7 — VERIFY
## ═══════════════════════════════════════════════════
### *5-Axis Awwwards-Grade Audit + Enhancement Discovery*

*(5-axis audit unchanged from v3 — see SKILL.md v3 Section 8)*

**v4 ADDITION: After 5-axis verification, run Enhancement Discovery (Agent-E).**
Agent-E suggests 3-5 additive features. Orchestrator decides which enter the Polish Pass.

**FINAL SIGN-OFF:**
```
╔══════════════════════════════════════════════════════════════════════╗
║              IRON CANVAS v4 — FINAL SIGN-OFF                         ║
╠══════════════════════════════════════════════════════════════════════╣
║  Axis 1 — Awwwards Design:        __ /10   (need ≥ 7.5)              ║
║  Axis 2 — Animation Quality:      __ /10   (need ≥ 7 checks)         ║
║  Axis 3 — Taste Test:             __ /7    (need 7/7, no exceptions)  ║
║  Axis 4 — Performance:            __ /12   (need ≥ 10)               ║
║  Axis 5 — Brand DNA Match:        __ /7    (need ≥ 5)                ║
╠══════════════════════════════════════════════════════════════════════╣
║  Enhancement Discovery:           __ suggestions (Orchestrator decides)║
╠══════════════════════════════════════════════════════════════════════╣
║  ALL PASS:  ✅ DELIVER — Awwwards-grade, production-ready             ║
║  ANY FAIL:  🔄 ROUTE to remediation                                   ║
╚══════════════════════════════════════════════════════════════════════╝
```

---

## ═══════════════════════════════════════════════════
## SECTION 10: PHASE 8 — HANDOFF (v4 WIRED)
## ═══════════════════════════════════════════════════
### *Optional Phase — Triggered for Client Deliverables*

**TRIGGER:** orient-decision.json → client_handoff: true

Phase 8 generates:
1. `/HANDOFF.md` — Non-technical documentation for the client
2. CMS recommendation (none / lightweight / full headless / e-commerce)
3. Component annotation map
4. CHANGELOG entry
5. Annotated screenshots (MISSION mode only)

Full Phase 8 protocol: → phases/08-handoff.md

---

## ═══════════════════════════════════════════════════
## SECTION 11: § ANTI-PATTERNS (v4 EXPANDED)
## ═══════════════════════════════════════════════════

| # | Anti-Pattern | Root Cause | Prevention |
|---|-------------|-----------|-----------|
| 1 | **Cookie-Cutter** | Skipping Phase 1 | Complete DNA Profile first |
| 2 | **Blind Generation** | No pre-gen checklist | Screenshot context first |
| 3 | **Template Imposition** | Aesthetic preference applied universally | Adapt to site DNA |
| 4 | **Batch-and-Pray** | All images at once | 4 variants → select → test → iterate |
| 5 | **Identity Erasure** | Over-enhancing | "Same site but better?" test |
| 6 | **Trinket Dropping** | Images not integrated | CSS verified in situ |
| 7 | **Video-as-Animation** | MP4 for scroll | Canvas + frames + ScrollTrigger |
| 8 | **Frame Inconsistency** | Different prompts per frame | Same base prompt, vary action only |
| 9 | **One-Shot Prompting** ★v4 | Linear prompting without context | Discovery Interview + Design PRD |
| 10 | **Skipping Asset Pipeline** ★v4 | Raw video on scroll engine | Classify → optimize → then integrate |
| 11 | **Context Drift** ★v4 | AI guesses stack/standards | Persistent skill repo + interview + PRD |

**Anti-Pattern #9: ONE-SHOT PROMPTING (v4)**
"Most people open a coding editor and start typing 'build me a dashboard.'
They keep prompting linearly — fixing errors, fighting linters, rewriting
components, wondering why the UI keeps drifting."
Prevention: Iron Canvas's 8-phase pipeline with persistent context injection.

**Anti-Pattern #10: SKIPPING ASSET PIPELINE (v4)**
"You can't just put video files directly onto a website. They're too heavy.
But more importantly, you can't control their playback with the scroll bar."
Prevention: Classify every asset (scroll-tied → frames, looping → video, static → image).
Optimize BEFORE integration.

**Anti-Pattern #11: CONTEXT DRIFT (v4)**
"That approach forces the AI to guess your stack, layout logic, and standards."
Prevention: The skill repo IS the persistent context. Discovery Interview (Phase 0) +
Design PRD (Phase 3.9) eliminate guessing.

---

## ═══════════════════════════════════════════════════
## SECTION 12: § EXPERTISE INJECTION PROTOCOL
## ═══════════════════════════════════════════════════

*(Core injections unchanged from v3 — see references/expertise-injection.md)*

**v4: NEW INJECTIONS**

**Agent-D (Google Whisk):**
```markdown
You are now an expert in Google Whisk for visual asset generation.

Whisk workflow:
1. Upload subject image OR paste reference screenshot
2. Write text prompt describing desired output
3. Click Generate → receive cleaned/styled image
4. Click Animate → receive cinematic looping video

Best practices:
• Use for cleaning Pinterest/reference images (remove text overlays)
• Use animate for background loop generation (oscilloscope, matrix rain, particles)
• Generated video loops: classify as LOOPING BACKGROUND → autoplay+loop+muted
• All prompts available at aurascenes.com for free
```

**Agent-D (Google Flow):**
```markdown
You are now an expert in Google Flow for keyframe interpolation.

Flow workflow:
1. Set type to "Frames to Video"
2. Upload start frame (the "before" state)
3. Upload end frame (the "after" state)
4. Write motion prompt (optional — describe the transition)
5. Generate → receive interpolated video

Best practices:
• This is the fastest path to scroll sequence source material
• Generate start/end frames with Whisk or Nano Banana Pro first
• Flow output → extract at 15fps for scroll-tied sequences
• Result is naturally smooth because it's interpolated, not prompted per-frame
```

---

## ═══════════════════════════════════════════════════
## SECTION 13: § DASHBOARD ADDENDUM
## ═══════════════════════════════════════════════════

*(Unchanged from v3 — see SKILL.md v3 Section 10)*

---

## ═══════════════════════════════════════════════════
## SECTION 14: § INVOCATIONS (v4)
## ═══════════════════════════════════════════════════

```
# MISSION MODE — Full team
Iron Canvas v4 MISSION MODE for [project].
Full team. Discovery Interview first. Phases 0-8.
Target: Awwwards Site of the Day quality.

# SWARM MODE — Standard production
Iron Canvas v4 SWARM MODE for [URL/project].
Phases 0-3.9 sequential. Then parallel agents. Merge and verify.

# SOLO MODE — Quick enhancement
Iron Canvas v4 SOLO for [URL].
Phase 1 FIRST — no changes before DNA profile.

# DASHBOARD BUILD
Iron Canvas v4 MISSION MODE — DASHBOARD ROUTE for [name].
Type C project. Bento + glass + data animation.

# SCROLL SEQUENCE — Keyframe Interpolation (v4)
Iron Canvas v4 Phase 5 scroll sequence for [site].
Method: Keyframe Interpolation (Whisk/Nano Banana start+end → Flow → 15fps extraction).
Product: [description]. Section: [where, dimensions].

# HANDOFF
Iron Canvas v4 Phase 8 HANDOFF for [project]. Generate HANDOFF.md.
```

---

## ═══════════════════════════════════════════════════
## SECTION 15: § TASTE DOCTRINE
## ═══════════════════════════════════════════════════

**1. RESTRAINT IS A SUPERPOWER** — 3 animations that wow > 30 that tire.
**2. TYPOGRAPHY IS THE DESIGN** — Fix type before adding any effect.
**3. COLOR TELLS THE EMOTIONAL STORY** — Palette communicates before words.
**4. ANIMATION REVEALS QUALITY** — Get the static version right, THEN animate.
**5. THE ONE UNFORGETTABLE THING** — Design for the moment people screenshot.
**6. COPY TECHNIQUE, NOT STYLE** — Same GSAP technique OK. Same visual language not OK.
**7. THE 15-SECOND SCROLL** — Best moments visible in first scroll pass.
**8. MOBILE IS NOT A DOWNGRADE** — Preserve ONE signature animation. Never zero.

---

## ═══════════════════════════════════════════════════
## SECTION 16: § PRODUCTION BRANCHING PROTOCOL
## ═══════════════════════════════════════════════════

```bash
# ALL Iron Canvas runs target staging branch first
git checkout -b iron-canvas-[project-name]

# Visual diff before merge — screenshot staging vs. production
# Never auto-merge to main. Never.

# After approval:
git checkout main
git merge iron-canvas-[project-name]
vercel --prod
```

---

## § REFERENCE FILE ROUTING (v4 COMPLETE)

```
PHASE 0:  references/performance-budget.md
          references/agent-autonomy.md (set tier + stack scan)
PHASE 1:  references/seo-conversion.md (conversion questions)
PHASE 2:  references/typography-system.md
          references/color-system.md
          references/motion-budget.md
PHASE 3:  references/model-selection.md (Whisk + Flow added in v4)
PHASE 3.5: phases/03.5-validate.md
PHASE 3.9: templates/design-prd.md
PHASE 4:  references/grid-rhythm.md
          references/interaction-library.md
PHASE 5:  references/prompt-engineering.md
          references/leonardo-blueprints.md
          references/scroll-engine.md
          references/video-integration-protocol.md
PHASE 6:  references/scroll-engine.md
          references/expertise-injection.md
PHASE 7:  references/anti-patterns.md
          references/seo-conversion.md (above-fold checklist)
PHASE 8:  phases/08-handoff.md
ALWAYS:   references/anti-patterns.md (check at every phase start)
          references/structural-policy.md (when structural changes planned)
          references/agent-autonomy.md (stack scan at every phase start)
```

---

## § OUTPUT ARTIFACTS (v4)

```
iron_canvas_output/
├── orient-decision.json              ← Phase 0 (+ Discovery Interview + Performance Tier)
├── site-dna-profile.json             ← Phase 1 (+ Conversion Questions)
├── feel-profile.json                 ← Phase 2 (+ typography + color + motion + layout)
├── north-star-reference.png          ← Phase 3
├── scout-report.json                 ← Phase 3
├── technical-validation-report.md    ← Phase 3.5
├── design-prd.md                     ← Phase 3.9 (+ Asset Manifest + Framework Config)
├── artifact-assessment.json          ← Phase 5 GATE
├── og-image.jpg                      ← Phase 5 (ALWAYS generated)
├── provisioning-log.md               ← Agent Autonomy (tools/accounts provisioned)
│
├── agent-outputs/
│   ├── agent-a/ (tokens.css, tokens-dark.css, index.html, base.css)
│   ├── agent-b/ (scroll.js, load-sequence.js, scroll-engine.js, transitions.js, webgl.js)
│   ├── agent-c/ (components.css, interactions.js, typography.js, polish.css, polish.js)
│   ├── agent-d/ (artifact-prompts.md, artifact-css.css, frames/, frames-mobile/, videos/)
│   └── agent-e/ (audits, qa-fixes.md, enhancement-discovery.md)
│
├── implementation/                   ← Phase 6 merged output
└── verification-report.json          ← Phase 7
    ├── HANDOFF.md                    ← Phase 8 (if client_handoff: true)
```

---

*Iron Canvas Master Skill v4.0 — Island Development Crew*
*"Enhancement means amplifying what's already good, not replacing it with a uniform style."*
*"Your coding agents are only as good as the instructions and the assets you feed them."*
*"Where there is no vision, the people perish." — Proverbs 29:18 (KJV)*
