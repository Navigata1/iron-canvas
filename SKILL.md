---
name: iron-canvas-master
version: 4.1
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

# ⚡ IRON CANVAS v4.1
## *The Multi-Agent Design Orchestration System*

> **The Golden Rule:** Before changing anything — STUDY what's there.
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

**PERFORMANCE TIER SELECTION (v4 — from references/performance-budget.md):**
```
TIER 1 — MARKETING (LCP < 2.5s, max 150KB JS, no Three.js)
TIER 2 — ANIMATED (LCP < 3.5s, max 300KB JS, Three.js if avant-garde ≥ 8)
TIER 3 — IMMERSIVE (LCP < 4.0s, progressive enhancement, WebGL scenes)
```

Performance tier gates ALL downstream agent decisions.
→ READ: references/performance-budget.md for full specs.

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

**Orient-decision.json also includes:**
```json
{
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

---

## ═══════════════════════════════════════════════════
## SECTION 3: PHASES 1-3 — THE RESEARCH TRIAD
## ═══════════════════════════════════════════════════
### *(Run by Research Agent or Orchestrator in Solo mode)*

### PHASE 1: STUDY — Read the Site's DNA

> **Do NOT touch anything until this phase is complete.**
> No CSS. No images. No "quick improvements." The Oakwood disaster began
> here — uniform templates killed three unique site identities because
> no one studied what existed before changing it.

**1.1 — SCREENSHOT ACQUISITION**
- [ ] Full page desktop (1440px)
- [ ] Full page mobile (375px)
- [ ] Individual section crops

**v4 ADDITION: SCREEN RECORDING INPUT**
When enhancing an existing site, an optional screen recording of the target
captures motion timing, scroll behavior, and interaction patterns that
screenshots miss. When provided, extract:
- Scroll-to-animation timing relationships
- Transition durations and easing curves
- Interaction trigger points
- Content reveal sequences

- [ ] All interactive states (hover, active, open menus)
- [ ] Any existing scroll animations (describe each)

**Browser extraction:**
```javascript
// Get all computed custom properties from :root
const style = getComputedStyle(document.documentElement);
const variables = {};
Array.from(document.styleSheets).forEach(sheet => {
  try {
    Array.from(sheet.cssRules).forEach(rule => {
      if (rule.selectorText === ':root') {
        rule.style.cssText.split(';').forEach(decl => {
          if (decl.trim().startsWith('--')) {
            const [prop, val] = decl.split(':');
            variables[prop.trim()] = val.trim();
          }
        });
      }
    });
  } catch(e) {}
});
console.log(JSON.stringify(variables, null, 2));
```

**1.2 — DNA EXTRACTION (output: site-dna-profile.json)**
```json
{
  "color_dna": {
    "dominant": "#hex", "secondary": "#hex",
    "text_primary": "#hex", "text_secondary": "#hex",
    "accent_primary": "#hex", "accent_secondary": "#hex",
    "gradient_start": "#hex", "gradient_end": "#hex",
    "border_color": "rgba()",
    "emotion": "What feeling does this palette create?",
    "contrast_wcag": "AA / AAA / FAIL",
    "temperature": "warm / cool / neutral",
    "saturation": "muted / vivid / earthy / neon"
  },
  "typography_dna": {
    "display_font": "Name", "body_font": "Name",
    "accent_font": "Name or null", "mono_font": "Name or null",
    "scale_ratio": "1.25/1.333/1.5/custom",
    "weight_range": "e.g. 300-800",
    "letter_spacing_hero": "value",
    "line_height_body": "value",
    "text_personality": "editorial/technical/humanist/geometric/expressive",
    "flag": "GENERIC → TYPE_GAP if Inter/Roboto/Arial on creative site"
  },
  "spatial_dna": {
    "base_unit": "8px", "max_width": "px",
    "grid_columns": 12, "section_padding": "current",
    "layout_personality": "centered/asymmetric/edge-to-edge/grid-breaking",
    "density": "airy/balanced/dense"
  },
  "motion_dna": {
    "existing_animations": [],
    "easing_character": "springy/mechanical/smooth/dramatic/absent",
    "duration_base": "ms", "scroll_behavior": "snap/smooth/native/none",
    "motion_gaps": []
  },
  "imagery_census": [
    {
      "name": "", "location": "", "rendered_size": "",
      "container_css": "", "blend_mode": "", "purpose": "", "quality": ""

**v4 ADDITION: CONVERSION QUESTIONS (from references/seo-conversion.md)**
After DNA extraction, answer these 5 conversion questions:
```
Q1: What is the PRIMARY conversion? (one answer only)
Q2: What is the SECONDARY conversion?
Q3: What is the value proposition in 6 words or less?
Q4: What are the 3 trust signals?
Q5: What is the friction? (count clicks to primary conversion)
```

→ READ: references/seo-conversion.md for full SEO + conversion architecture.

    }
  ],
  "strengths": [],
  "gaps": [
    {
      "type": "MOTION_GAP/COLOR_GAP/TYPE_GAP/SPATIAL_GAP/INTERACTION_GAP/3D_GAP/TRANSITION_GAP/ARTIFACT_GAP",
      "description": "", "priority": "HIGH/MEDIUM/LOW", "leverage": ""
    }
  ]
}
```

**GATE 1 — 7/7 required to proceed:**
```
□ Color DNA: 8+ values with actual hex codes
□ Typography: all fonts identified with roles
□ Spatial: grid + base unit + max-width
□ Motion: existing animations catalogued
□ Imagery: all images mapped
□ Strengths: at least 3 documented
□ Gaps: at least 3 categorized and typed
```

---

### PHASE 2: FEEL — Discover the Emotional Target

> The emotional target comes FROM the site. You are a detective, not an art director.

**2.1 — COPY ANALYSIS:** Read all copy. Identify recurring words, tone, promises, story.

**2.2 — IMAGERY ANALYSIS:** Temperature, energy, focus, quality, aspiration level.

**2.3 — PALETTE EMOTIONAL DECODE:**
```
Black + Gold         → Luxury, exclusivity, premium
Deep OLED + glow    → Ethereal glass, tech-luxury
Earth tones          → Natural, organic, grounded
Maroon + Gold        → Warm heritage, trusted institution
Navy + White         → Professional, reliable
Neon + dark          → Bold, modern, disruptive
Obsidian + metals   → Iron Canvas territory — craft, precision, warmth
```

**2.4 — BRAND PERSONALITY MATRIX (governs ALL downstream decisions):**
```json
{
  "brand_personality_matrix": {
    "minimal_vs_maximal":     "__/10 → animation intensity",
    "serious_vs_playful":     "__/10 → interaction playfulness",
    "classic_vs_avant_garde": "__/10 → technique selection + 3D threshold",
    "digital_vs_organic":     "__/10 → texture + grain decisions",
    "quiet_vs_bold":          "__/10 → cursor type + WebGL decision",
    "fast_vs_contemplative":  "__/10 → animation duration + pacing",
    "summary": "2-sentence brand character description"
  }
}
```

**Matrix thresholds:**
- Bold 1-4: No custom cursor | CSS animations only
- Bold 5-7: Trailing cursor | GSAP standard stack
- Bold 8-10: Magnetic cursor + WebGL | full GSAP + Three.js eligible
- Avant-garde ≥ 8: Three.js eligible, GLSL shaders viable

**2.5 — FEEL PROFILE (output: feel-profile.json):**
```json
{
  "primary_emotion": "What users feel FIRST, within 3 seconds",
  "secondary_emotions": ["What sustains the experience"],
  "aspirational_target": "What they feel AFTER — the transformation",
  "anti_feelings": ["Hard rule — ANY decision evoking these is VETOED"],
  "reference_vibe": "'Walking into a ______' — real-world analogy",
  "brand_personality_matrix": { "...": "..." }
}
```

---

### PHASE 3: SCOUT — AI Reference Intelligence

> **The North Star Image is Iron Canvas's secret weapon.**
> One AI-generated image that synthesizes the design target before a line
> of code is written. Not 50 Pinterest screenshots — one precision image.

**3.1 — REFERENCE SOURCE ROUTING BY PROJECT TYPE:**
```
TYPE A (animated site):
  awwwards.com/websites/animation | godly.website | madewithgsap.com | tympanus.net
  Search: "[industry] awwwards site of the day 2024 2025"
          "[industry] scroll animation GSAP dark premium"

TYPE B (marketing/SaaS):
  lapa.ninja | godly.website | saaslandingpage.com
  Search: "[product type] landing page premium animated 2025"

TYPE C (dashboard/mission control):
  muz.li/blog/top-dashboard-design-examples | dribbble.com/tags/dark-dashboard
  behance.net (search "mission control UI") | awwwards.com (app/dashboard)
  Real-world refs: SpaceX Dragon capsule UI, NASA mission control, Bloomberg Terminal

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

  Search: "mission control UI dark dashboard premium 2024"
          "dark analytics dashboard bento grid inspiration"

TYPE D (e-commerce/product):
  apple.com scroll patterns | dji.com product pages | codrops product sequences
  Search: "luxury product scroll animation canvas sequence"

TYPE E/F:
  Competitor analysis first, then Type A/B/C/D based on their vertical
```

**3.2 — REFERENCE COLLECTION:**

Find 3-5 sites matching the Feel Profile. Screenshot SPECIFIC elements:
- A hover state at the exact right intensity for your Brand Personality Matrix
- A scroll animation at the correct depth/drama level
- A typography treatment matching your weight/personality
- A layout density matching your brand matrix score

Document each:
```json
{
  "url": "...", "what_to_take": "...",
  "why_it_fits": "maps to feel profile because...",
  "adaptation_needed": "change X to match our DNA"
}
```

**3.3 — NORTH STAR IMAGE GENERATION**

**AI engine selection:**
```
Nano Banana Pro (Gemini 3 Pro Image):
  Best for: Photorealistic UI mockups, dark premium interfaces, product shots
  Command: uv run {baseDir}/scripts/generate_image.py
           --prompt "..." --filename "north-star.png"
           --resolution 2K --aspect-ratio 16:9

Grok Imagine:
  Best for: Bold expressive concepts, dramatic visual energy

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


OpenAI Image 1.5:
  Best for: Detailed UI layouts with multiple specific components

Leonardo.ai Kino XL:
  Best for: Cinematic luxury atmosphere references
```

**North Star prompt formula:**
```
[Style descriptor] + [Interface type] + [Palette hex codes] + [Mood/emotion] +
[Key visual elements] + [Layout approach] + [Negative constraints]
```

**North Star examples by type:**

*Animated website (dark luxury):*
```
Award-winning creative studio website hero section, editorial asymmetric layout,
massive display typography left-aligned (Outfit 900), orbital animation element
right panel, OLED black (#0a0e14), single warm gold accent (#c9a84c),
film grain texture overlay, radial mesh gradient ambient glow, Awwwards SOTD quality,
no stock photography, no centered layout, no three-column cards,
photorealistic browser screenshot, 16:9
```

*Dashboard / Mission Control:*
```
Premium dark analytics mission control interface, OLED black (#0a0e14),
warm gold data accent (#c9a84c), glassmorphism cards with obsidian surfaces,
radial mesh gradient background, bento grid 4-6 cards varying sizes,
3D chart center panel, real-time data stream sidebar, subtle gold border glow,
Outfit 700 typography, cinematic rim lighting, no purple, no cold blue,
photorealistic UI mockup, 16:9
```

*E-commerce product page:*
```
Premium luxury product scroll sequence hero, [product] centered on deep black (#0a0e14),
warm studio lighting with gold rim highlights (#c9a84c), floating particle elements,
minimal UI chrome, editorial large typography, Apple.com-level restraint and polish,
scroll progress indicator, 2K photorealistic quality, no clutter, no banners
```

**3.4 — NORTH STAR VALIDATION (4/5 required):**
```
□ Evokes primary emotion from feel-profile.json?
□ Avoids ALL anti-feelings?
□ Palette within ±15% temperature of DNA hex codes?
□ Layout density matches Brand Personality Matrix scores?
□ Client would lean forward and say "YES — THAT"?
```

---

## ═══════════════════════════════════════════════════
## SECTION 4: PHASE 3.5 — CROSS-LLM TECHNICAL VALIDATION
## ═══════════════════════════════════════════════════
### *(The Antigravity Pattern — Prompt 3 Adapted for Design)*

> This phase is drawn directly from the Antigravity video workflow.
> Before dispatching to Build Agents, a dedicated Validation Agent
> checks technical feasibility across ALL planned features.
> Catching an impossible architecture here costs minutes.
> Catching it in Phase 6 costs days.

**VALIDATION AGENT system prompt:**
```markdown
You are the Iron Canvas Technical Validation Agent.

You have received:
- site-dna-profile.json (from Phase 1)
- feel-profile.json + Brand Personality Matrix (from Phase 2)
- north-star-reference.png (from Phase 3)
- Planned tech stack (from Phase 0)

Your job: Validate ALL planned features for technical feasibility BEFORE build agents execute.

Cross-reference against:
1. The site's current tech stack (React / Next.js / Vanilla / etc.)
2. Browser compatibility for all planned animation APIs
3. Mobile performance budget for planned scroll sequences
4. Three.js/WebGL requirements vs. device GPU targets
5. Canvas frame count vs. file size vs. load time budget
6. GSAP license requirements for planned plugins
7. Any API integrations (TTS, WebSocket, etc.) for feasibility in browser environment

For EACH planned feature, output:
  FEATURE: [name]
  FEASIBLE: YES / NO / CONDITIONAL
  BROWSER_SUPPORT: [any gaps]
  PERFORMANCE_RISK: LOW / MEDIUM / HIGH
  CONSTRAINT: [any limitations found]
  RECOMMENDATION: [proceed / modify / replace with alternative]

If feasible overall, generate: technical-validation-report.md
If critical issues found: STOP and report to Orchestrator before proceeding.

Model recommendation: Gemini 3 Pro (access to live API docs) or Claude Opus
```

**Validation checklist topics:**
```
SCROLL ENGINE:
  □ Canvas frame animation feasible in this framework?
  □ Frame count × file size within 5MB load budget?
  □ GSAP ScrollTrigger browser support verified?
  □ Mobile performance acceptable (30fps minimum)?

WEBGL / THREE.JS (if planned):
  □ GPU budget appropriate for target audience devices?
  □ Mobile fallback designed?
  □ renderer.dispose() cleanup planned?
  □ Avant-garde score ≥ 8 justified this decision?

PAGE TRANSITIONS:
  □ Barba.js compatible with current routing?
  □ Next.js App Router — use AnimatePresence instead?
  □ SPA vs. multi-page confirmed?

CURSOR SYSTEM:
  □ Touch detection handled?
  □ Pointer Events API support verified?
  □ Performance impact of lerp loop assessed?

AUDIO / TTS (if planned, e.g. narrated scroll):
  □ WebSocket streaming feasible in browser environment?
  □ AudioContext requires user gesture — handled?
  □ Scroll-sync timing achievable with latency budget?

TYPOGRAPHY:
  □ SplitText license confirmed if GSAP SplitText used?
  □ Font loading strategy planned (preload, font-display)?
  □ Variable font support for target browsers?
```

**Output:** `technical-validation-report.md` with FEASIBLE/CONDITIONAL/BLOCKED per feature.

---

## ═══════════════════════════════════════════════════
## SECTION 5: PHASE 3.9 — DESIGN PRD PACKAGING
## ═══════════════════════════════════════════════════
### *(The Antigravity Pattern — Prompt 2 Adapted)*

> All research is complete. All validation is done.
> Now the Orchestrator packages everything into the Design PRD —
> the single document that all parallel Build Agents consume.
>
> This is the most important document in the entire pipeline.
> A weak PRD produces conflicting agent outputs.
> A precise PRD produces a coherent, unified product.

**DESIGN PRD TEMPLATE (design-prd.md):**

```markdown
# IRON CANVAS DESIGN PRD
## Project: [Name] | Type: [A/B/C/D/E/F] | Mode: [SOLO/SWARM/MISSION]
## Date: [YYYY-MM-DD] | North Star: [path/to/north-star.png]

---

## 1. DESIGN DNA SUMMARY
Dominant palette: [hex] | Accent: [hex] | Fonts: [display] / [body]
Base unit: [px] | Max width: [px] | Grid: [columns]
Brand Personality: Minimal[__] Serious[__] Classic[__] Digital[__] Quiet[__] Fast[__]

## 2. EMOTIONAL TARGET
Primary: [emotion] | Anti-feelings: [list — HARD VETO on any decision evoking these]
Reference vibe: "[walking into a ___]"

## 3. DESIGN TOKEN SYSTEM
[Complete CSS custom properties block — copy directly from site-dna-profile.json]
[AGENT-A executes this]

## 4. MOTION ARCHITECTURE
Easing vocabulary: { heroIn: "...", textIn: "...", spring: "...", brand: "..." }
Load sequence: Phase 0→5 timing [ms values]
Section-by-section choreography:
  Hero: [technique + scroll behavior]
  [Section N]: [technique + emotion target]
Cursor: [none / trailing / magnetic] based on Bold score [value]
Page transitions: [curtain / fade / none] — [justification]
[AGENT-B executes this]

## 5. COMPONENT SYSTEM
Interactive elements requiring 3-state implementation:
  [list every button, card, link, input]
Navigation behavior: [fixed/sticky + scroll-change behavior]
Typography treatments: [which elements get SplitText / scramble / counter]
[AGENT-C executes this]

## 6. ARTIFACT REQUIREMENTS
[Per artifact, fill this for EACH image/visual needed:]
  Name: [artifact name]
  Section: [where it lives]
  Container: [dimensions + CSS context]
  Palette: [hex codes from DNA]
  Prompt elements: [subject, material, lighting, angle, background, negative]
  Engine: [Nano Banana / Leonardo / Grok / GPT Image]
Scroll sequence: [YES/NO] — if YES: [keyframe count, frame specs, section height]
[AGENT-D executes this]

## 7. PERFORMANCE + ACCESSIBILITY CONSTRAINTS
LCP target: [<2s / <2.5s / <3s]
JS budget: [KB]
Reduced-motion: [how to handle — what stays, what simplifies]
WCAG level: [AA / AAA]
Mobile strategy: [which animations survive at 375px]
[AGENT-E executes this audit]

## 8. TECHNICAL VALIDATION SUMMARY
[Copy FEASIBLE/CONDITIONAL/BLOCKED results from Phase 3.5]
Any CONDITIONAL features: [what modifications are required]

## 9. AGENT ASSIGNMENTS
Agent-A: Foundation (tokens + HTML structure + semantic scaffold)
Agent-B: Motion (GSAP + scroll engine + load sequence + page transitions)
Agent-C: UI Components (interactive elements + cursor + nav + typography)
Agent-D: Artifacts (AI image generation + integration + scroll sequence)
Agent-E: QA (accessibility audit + performance check + cross-browser)

## 10. INTEGRATION NOTES
Naming conventions: [component prefixes, file structure]
Style scoping: [CSS modules / global / BEM]
Asset paths: [where artifacts land, how components reference them]
Merge sequence: A → B → C → D → E (in this order when integrating)

## 11. ANTI-PATTERNS — ACTIVE VETO LIST FOR THIS PROJECT
[Copy the 8 universal anti-patterns + any project-specific additions]
Red flags specific to THIS project: [list based on Phase 1 gaps]
```

---


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

## ═══════════════════════════════════════════════════
## SECTION 7: THE BUILD AGENTS — PARALLEL EXECUTION
## ═══════════════════════════════════════════════════
### *Dispatched simultaneously. Each receives the full Design PRD.*

---

### AGENT-A: FOUNDATION
*Tokens, HTML Architecture, Structural Skeleton*

**Agent-A system prompt:**
```markdown
You are Iron Canvas Agent-A: Foundation Specialist.

You have received the Design PRD. Your deliverables are:
1. tokens.css — Complete CSS custom properties from the Design PRD token system
2. index.html — Full semantic HTML scaffold with correct ARIA, skip links, roles
3. base.css — Reset, body, typography base, grain overlay, container system

Rules:
- NO animation code (Agent-B handles this)
- NO component logic (Agent-C handles this)  
- NO images (Agent-D handles this)
- ONLY: tokens, structure, semantics, accessibility scaffold

Token system must be 100% complete — Agent-B and Agent-C depend on your variables.
Every interactive element must have data-magnetic, .reveal, or appropriate data attrs
so Agent-B and Agent-C can target them without touching your HTML.

Output: /agent-a/ folder with tokens.css, index.html, base.css
```

**Agent-A deliverables:**

```css
/* tokens.css — the foundation everything else references */
:root {
  /* COLORS — exact from site-dna-profile.json */
  --color-bg:           #______;
  --color-bg-2:         #______;
  --color-text:         #______;
  --color-text-muted:   #______;
  --color-accent:       #______;
  --color-accent-2:     #______;
  --color-border:       rgba(var(--color-text-rgb), 0.12);

  /* TYPOGRAPHY */
  --font-display: '[display]', serif;
  --font-body:    '[body]', sans-serif;

  /* FLUID SCALE */
  --text-hero:  clamp(3.5rem, 9vw, 8rem);
  --text-3xl:   clamp(2rem, 5vw, 3rem);
  --text-2xl:   clamp(1.5rem, 4vw, 2rem);
  --text-xl:    clamp(1.25rem, 3.5vw, 1.5rem);
  --text-lg:    clamp(1.125rem, 3vw, 1.25rem);
  --text-base:  clamp(1rem, 2.5vw, 1.125rem);
  --text-sm:    clamp(0.875rem, 2vw, 1rem);

  /* SPACING */
  --space-section: clamp(5rem, 12vw, 10rem);
  --space-32: 8rem; --space-16: 4rem; --space-8: 2rem;
  --space-4: 1rem;  --space-2: 0.5rem; --space-1: 0.25rem;

  /* MOTION — TINTED TO SITE'S OWN ACCENT COLOR */
  --spring:      cubic-bezier(0.34, 1.56, 0.64, 1);
  --spring-slow: cubic-bezier(0.16, 1, 0.3, 1);
  --smooth:      cubic-bezier(0.4, 0, 0.2, 1);
  --dur-fast:    150ms; --dur-normal: 300ms;
  --dur-slow:    600ms; --dur-hero:   1000ms;

  /* DEPTH — tinted shadows using site's own accent */
  --shadow-sm: 0 2px 8px rgba(var(--accent-rgb), 0.08);
  --shadow-md: 0 8px 32px rgba(var(--accent-rgb), 0.12);
  --shadow-lg: 0 20px 60px rgba(var(--accent-rgb), 0.18);
  --shadow-xl: 0 40px 100px rgba(var(--accent-rgb), 0.24);

  /* LAYERS */
  --z-raised: 10; --z-sticky: 200;
  --z-modal: 300; --z-cursor: 9999;
}
```

```html
<!-- index.html scaffold (Agent-A) -->
<body data-scroll-container>
  <a href="#main" class="skip-link">Skip to main content</a>

  <!-- Canvas/WebGL layer (if Agent-B requires it) -->
  <canvas id="webgl-canvas" aria-hidden="true"></canvas>

  <!-- Cursor (Agent-C populates, Agent-B animates) -->
  <div class="cursor" aria-hidden="true">
    <div class="cursor__dot"></div>
    <div class="cursor__ring"></div>
  </div>

  <!-- Page transition overlay (Agent-B animates) -->
  <div class="transition-overlay" aria-hidden="true"></div>

  <!-- Navigation -->
  <header class="nav" role="banner" aria-label="Primary navigation">
    <!-- Agent-C populates -->
  </header>

  <main id="main">
    <!-- Sections — Agent-A scaffolds, others populate content + animation -->
    <section class="hero" data-scroll-section aria-label="Hero">
      <div class="hero__bg" aria-hidden="true"></div>
      <!-- data-magnetic on CTAs for Agent-B magnetic cursor -->
      <!-- .reveal on all below-fold elements for Agent-B scroll reveals -->
    </section>
    <!-- Additional sections per Design PRD -->
  </main>

  <footer role="contentinfo"><!-- Agent-C populates --></footer>
</body>
```

---

**v4: Agent-A also reads:**
- references/grid-rhythm.md → spacing scale + column system
- references/color-system.md → oklch palette + gradient mesh
- references/typography-system.md → font loading protocol
- feel-profile.json → typography, color, motion, layout fields

**v4: Dark mode generation trigger:**
When feel-profile.json → color.dark_mode: true OR Brand Personality bold ≥ 6:
Agent-A generates `tokens-dark.css` alongside `tokens.css`.


### AGENT-B: MOTION
*GSAP Animation System, Scroll Engine, Load Sequence, Page Transitions*

**Agent-B system prompt:**
```markdown
You are Iron Canvas Agent-B: Motion Specialist.

You receive: Design PRD + Agent-A's tokens.css and HTML scaffold.

Your deliverables:
1. scroll.js — Lenis smooth scroll + GSAP ScrollTrigger setup + all section animations
2. load-sequence.js — Page load choreography (Phases 0-5 from PRD timing)
3. scroll-engine.js — Canvas frame sequence (if PRD specifies scroll engine)
4. transitions.js — Barba.js page transitions (if PRD specifies)
5. webgl.js — Three.js scene (if PRD specifies and Avant-garde score ≥ 8)

Rules:
- Reference ONLY token variables — never hardcode hex codes or px values
- ALWAYS implement @media (prefers-reduced-motion: reduce) fallback
- ALWAYS cap Three.js devicePixelRatio at 2
- ALWAYS use transform + opacity only (no layout-triggering properties)
- ALWAYS apply will-change before animation, clearProps after
- Canvas scroll engine ALWAYS preloads before enabling (show loading progress)
- Page transitions ALWAYS call runLoadSequence() on new page entry

Model recommendation: Claude Sonnet / Gemini 3 Flash (fast code generation)
```

**Agent-B key implementations:**

```javascript
// scroll.js — Agent-B
import gsap from 'gsap';
import { ScrollTrigger } from 'gsap/ScrollTrigger';
import { SplitText } from 'gsap/SplitText';
import Lenis from '@studio-freight/lenis';
gsap.registerPlugin(ScrollTrigger, SplitText);

// REDUCED MOTION CHECK — always first
const prefersReducedMotion = window.matchMedia('(prefers-reduced-motion: reduce)').matches;

// SMOOTH SCROLL INIT
const lenis = new Lenis({ duration: 1.4, smoothWheel: true });
gsap.ticker.add((time) => lenis.raf(time * 1000));
gsap.ticker.lagSmoothing(0);

// LOAD SEQUENCE (follows Design PRD timing)
export const runLoadSequence = () => {
  if (prefersReducedMotion) {
    gsap.to('[data-load]', { autoAlpha: 1, duration: 0.3, stagger: 0.05 });
    return;
  }
  // Phase 0: bg, Phase 1: visual, Phase 2: headline, Phase 3: sub, Phase 4: cta, Phase 5: nav
  // [Agent-B fills from PRD timing values]
};

// SCROLL REVEALS — universal
gsap.utils.toArray('.reveal').forEach((el, i) => {
  gsap.from(el, {
    y: 50, autoAlpha: 0, duration: 0.8,
    ease: 'power2.out',
    scrollTrigger: {
      trigger: el, start: 'top 85%',
      toggleActions: 'play none none reverse'
    }
  });
});

// SCROLL ENGINE (Canvas frame sequence — if PRD specifies)
// [see full implementation in § SCROLL ENGINE REFERENCE]
```

---

### AGENT-C: UI/UX
*Components, Cursor, Navigation, Micro-interactions, Typography*

**Agent-C system prompt:**
```markdown
You are Iron Canvas Agent-C: UI/UX Specialist.

You receive: Design PRD + Agent-A's scaffold (tokens + HTML).

Your deliverables:
1. components.css — All component styles (buttons, cards, nav, forms, badges)
2. interactions.js — Cursor system (if Bold ≥ 5), nav scroll behavior, all hover states
3. typography.js — SplitText instances (if planned), counter animations, text effects
4. navigation.html partial — Complete nav markup with correct aria + links

Rules:
- 3 states MANDATORY on every interactive element: default + hover + active
- Focus-visible states required on every clickable/focusable element
- Cursor: Touch detection before initialization — skip cursor on touch devices
- Color: only reference token variables, never hardcode
- All micro-interactions: use var(--spring) or var(--spring-slow) easing
- NO animation timing longer than 500ms for micro-interactions
- Tinted shadows: ALWAYS use var(--shadow-md) or var(--shadow-lg) from tokens
- Grain overlay: apply if personality is creative/luxury (NOT corporate/medical)
```

**Agent-C key implementations:**

```css
/* components.css — Agent-C */
/* BUTTON — 3 states, no exceptions */
.btn {
  display: inline-flex; align-items: center; gap: 0.5rem;
  font-family: var(--font-display); font-weight: 700;
  border-radius: var(--radius-md);
  transition: all var(--dur-normal) var(--spring);
  cursor: pointer; border: none;
}
.btn:hover  { transform: translateY(-2px); box-shadow: var(--shadow-md); }
.btn:active { transform: translateY(0) scale(0.98); box-shadow: none; }
.btn:focus-visible { outline: 2px solid var(--color-accent); outline-offset: 3px; }

/* CARD — lift on hover with tinted shadow */
.card {
  transition: transform var(--dur-normal) var(--spring),
              border-color var(--dur-normal), box-shadow var(--dur-normal);
}
.card:hover {
  transform: translateY(-4px);
  border-color: rgba(var(--accent-rgb), 0.4);

**v4: Agent-B reads motion tier from feel-profile.json BEFORE writing any GSAP:**
- Tier 1: CSS transitions + Intersection Observer only
- Tier 2: GSAP + ScrollTrigger + selective animation (3-4 moments per page)
- Tier 3: Full GSAP + scroll engine + cursor + page transitions
- Tier 4: Everything in Tier 3 + Three.js + GLSL + audio

→ READ: references/motion-budget.md for full tier specs

  box-shadow: var(--shadow-lg);
}
.card:active { transform: translateY(-2px); }

/* REVEAL ANIMATION — Agent-C declares, Agent-B triggers */
.reveal {
  opacity: 0; transform: translateY(32px);
  transition: opacity 0.8s var(--spring-slow), transform 0.8s var(--spring-slow);
}
.reveal.in-view { opacity: 1; transform: translateY(0); }
.reveal-delay-1 { transition-delay: 0.1s; }
.reveal-delay-2 { transition-delay: 0.2s; }
.reveal-delay-3 { transition-delay: 0.3s; }

/* GRAIN OVERLAY — luxury/creative only */
body.has-grain::before {
  content: ''; position: fixed; inset: 0; z-index: 9999;
  pointer-events: none; opacity: 0.032;
  background-image: url("data:image/svg+xml,%3Csvg viewBox='0 0 512 512' xmlns='http://www.w3.org/2000/svg'%3E%3Cfilter id='n'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='0.85' numOctaves='4' stitchTiles='stitch'/%3E%3C/filter%3E%3Crect width='100%25' height='100%25' filter='url(%23n)'/%3E%3C/svg%3E");
  background-size: 200px 200px;
}
```

```javascript
// interactions.js — Agent-C: Cursor system
class IronCursor {
  constructor() {
    if ('ontouchstart' in window) return; // Never on touch
    this.dot   = document.querySelector('.cursor__dot');
    this.ring  = document.querySelector('.cursor__ring');
    this.mouse = { x: 0, y: 0 };
    this.pos   = { x: 0, y: 0 };
    this.init();
  }
  init() {
    window.addEventListener('mousemove', ({ clientX: x, clientY: y }) => {
      this.mouse = { x, y };
    });
    document.querySelectorAll('[data-magnetic]').forEach(el => {
      el.addEventListener('mouseenter', () =>
        gsap.to(this.ring, { scale: 2.5, duration: 0.3 }));
      el.addEventListener('mousemove', (e) => {
        const r = el.getBoundingClientRect();
        gsap.to(el, {
          x: (e.clientX - r.left - r.width/2) * 0.3,
          y: (e.clientY - r.top  - r.height/2) * 0.3,
          duration: 0.3
        });
      });
      el.addEventListener('mouseleave', () => {
        gsap.to(el, { x: 0, y: 0, duration: 0.5, ease: 'elastic.out(1,0.3)' });
        gsap.to(this.ring, { scale: 1, duration: 0.3 });
      });
    });
    this.render();
  }
  render() {
    this.pos.x += (this.mouse.x - this.pos.x) * 0.12;
    this.pos.y += (this.mouse.y - this.pos.y) * 0.12;
    gsap.set(this.ring, { x: this.pos.x, y: this.pos.y });
    gsap.set(this.dot,  { x: this.mouse.x, y: this.mouse.y });
    requestAnimationFrame(() => this.render());
  }
}
// Only initialize on bold score ≥ 5 (check PRD)
if (BRAND_BOLD_SCORE >= 5) new IronCursor();
```

---

### AGENT-D: ARTIFACTS
*AI Image Generation, Context-Aware Prompting, Scroll Frame Sequences*

**Agent-D system prompt:**
```markdown
You are Iron Canvas Agent-D: Artifacts Specialist.

You receive: Design PRD artifact requirements section.

Your deliverables:
1. artifact-prompts.md — Complete, context-aware prompts for EVERY artifact
2. artifact-integration.css — CSS for each artifact's container and blending
3. scroll-frames/ — For scroll sequence: consistent frame prompts + frame extraction instructions
4. Generated artifacts (if you have API access to Nano Banana / Leonardo / GPT Image)

MANDATORY PRE-GENERATION CHECKLIST before any prompt:
□ Exact section documented (screenshot reviewed)
□ Container dimensions recorded
□ CSS context: bg color, overlay gradients, blend mode, opacity, border-radius
□ Palette hex codes from site-dna-profile.json
□ Emotional target from feel-profile.json
□ Aspect ratio confirmed

PROMPT FORMULA:
[Subject] + [Material/Style] + [Palette hex] + [Lighting] + [Camera angle] +
[Background] + [CSS context usage] + [Negative constraints]

GENERATION PROTOCOL:
1. Generate 4 variants per artifact
2. Preview all 4 before selecting

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

3. Test best variant in situ (composite into page screenshot)
4. Evaluate: blend / lighting match / feels native
5. If doesn't blend → adjust prompt → regenerate → retest
NEVER force-fit. NEVER skip the in-situ test.

SCROLL SEQUENCE CONSISTENCY PROTOCOL:
- Establish ONE base prompt (product + material + palette + lighting + background + style)
- Vary ONLY the action/angle descriptor per frame
- Test 10 frames first. If scrub feels smooth → generate full set.
```

**Agent-D AI engine routing:**
```
Photorealistic product/UI: Nano Banana Pro (Gemini 3 Pro Image)
Expressive/bold concepts:  Grok Imagine
Detailed layouts:          OpenAI Image 1.5
Cinematic luxury:          Leonardo Kino XL / Phoenix
Product 360°:              Leonardo Product Spin Video → ffmpeg frame extract
Style matching:            Leonardo Style Transfer
Scene placement:           Leonardo Product In Scene
Cross-frame lighting:      Leonardo Custom Relight
Image expansion:           Leonardo Instant Outpaint
Background swap:           Leonardo Background Change
```

**Frame extraction (from video):**
```bash
# WebP frames at 24fps (sweet spot)
ffmpeg -i product_spin.mp4 -vf "fps=24,scale=1920:1080" frames/frame_%04d.webp

# Mobile set (half resolution)
ffmpeg -i product_spin.mp4 -vf "fps=24,scale=960:540" frames-mobile/frame_%04d.webp

# Optimize all frames
for f in frames/*.webp; do cwebp -q 80 "$f" -o "$f"; done
```

---

### AGENT-E: QA + ACCESSIBILITY

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

*Performance Audit, Cross-Browser Check, Accessibility Compliance*

**Agent-E system prompt:**
```markdown
You are Iron Canvas Agent-E: Quality & Accessibility Specialist.

You receive: All outputs from Agents A, B, C, D plus the Design PRD.

Your deliverables:
1. accessibility-audit.md — Full WCAG AA compliance review
2. performance-checklist.md — All performance items verified
3. cross-browser-report.md — Any compatibility issues found
4. qa-fixes.md — Actionable fix list for Orchestrator to implement

Review against:
PERFORMANCE:
  □ Only transform + opacity animated (no layout triggers)?
  □ will-change applied before, clearProps after?
  □ Images: WebP, loading="lazy", width+height set?
  □ Fonts: preloaded, font-display: swap?
  □ Canvas frames: loading progress indicator works?
  □ Three.js: renderer.dispose() on unmount?
  □ JS: dynamic imports for non-critical features?

ACCESSIBILITY:
  □ All images: alt text or aria-hidden on decorative?
  □ All interactive: keyboard accessible?
  □ Focus-visible states: visible and styled?
  □ @media (prefers-reduced-motion): tested?
  □ Color contrast: all text passes WCAG AA (4.5:1)?
  □ Skip link: present and functional?
  □ ARIA roles: nav, main, header, footer present?
  □ Form labels: visible (not just placeholder)?

CROSS-BROWSER:
  □ Chrome (latest 2) ✓/✗
  □ Firefox (latest 2) ✓/✗
  □ Safari (latest 2) ✓/✗
  □ Edge (latest 2) ✓/✗
  □ Mobile Safari (iOS 15+) ✓/✗
  □ Chrome Android ✓/✗

MOBILE (375px viewport):
  □ No horizontal scroll?
  □ Touch targets ≥ 44px?
  □ Scroll animations work with touch?
  □ min-height: 100dvh (not 100vh)?
  □ Signature animation preserved on mobile?
```

---


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


## ═══════════════════════════════════════════════════
## SECTION 8: PHASE 5 — GENERATE (ARTIFACT ASSESSMENT GATE)
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
Assessment Gate details: → ROUTING.md § ARTIFACT ASSESSMENT GATE

## ═══════════════════════════════════════════════════
## SECTION 9: PHASE 6 — COMPOSE (MERGE + INTEGRATE)
## ═══════════════════════════════════════════════════
### *Orchestrator merges all agent outputs into one coherent product*

**Merge sequence:**
```
1. Agent-A foundation (tokens + HTML) — base layer
2. Agent-B motion layers applied (scripts added, data-attrs wired)
3. Agent-C component styles + interaction logic layered on
4. Agent-D artifacts placed, CSS integration applied
5. Agent-E fixes implemented
6. Full integration test (screenshot every section)
```

**Scroll sequence integration (if built by Agent-D/B):**

```javascript
// Full Canvas scroll engine — ALWAYS use Canvas, NEVER <video>
// WHY: Canvas = bidirectional scrub + per-frame content sync + mobile reliable
//      video = unidirectional + no scroll scrub + mobile autoplay restrictions

const TOTAL_FRAMES = 60;
const frames = [];
let loadedCount = 0;

async function preloadFrames() {
  return new Promise((resolve) => {
    for (let i = 1; i <= TOTAL_FRAMES; i++) {
      const img = new Image();
      img.src = `/frames/frame_${String(i).padStart(4,'0')}.webp`;
      img.onload = () => {
        loadedCount++;
        document.querySelector('.loader-progress').style.width =
          `${(loadedCount/TOTAL_FRAMES)*100}%`;
        if (loadedCount === TOTAL_FRAMES) resolve();
      };
      frames.push(img);
    }
  });
}

const canvas = document.getElementById('scroll-canvas');
const ctx = canvas.getContext('2d');

function drawFrame(index) {
  const img = frames[Math.min(index, TOTAL_FRAMES-1)];
  if (!img) return;
  const scale = Math.max(canvas.width/img.naturalWidth, canvas.height/img.naturalHeight);
  const x = (canvas.width - img.naturalWidth*scale) / 2;
  const y = (canvas.height - img.naturalHeight*scale) / 2;
  ctx.clearRect(0, 0, canvas.width, canvas.height);
  ctx.drawImage(img, x, y, img.naturalWidth*scale, img.naturalHeight*scale);
}

preloadFrames().then(() => {
  document.querySelector('#frame-loader').style.display = 'none';
  drawFrame(0);

  gsap.to({ frame: 0 }, {
    frame: TOTAL_FRAMES - 1, snap: 'frame', ease: 'none',
    scrollTrigger: {
      trigger: '#scroll-section',
      start: 'top top', end: 'bottom bottom',
      scrub: 0.5, pin: canvas
    },
    onUpdate: function() {
      drawFrame(Math.round(this.targets()[0].frame));
    }
  });

  // Content overlays synced per-frame to scroll (from Design PRD overlay timing)
  gsap.fromTo('.overlay-1', { opacity: 0, y: 40 }, {
    opacity: 1, y: 0, scrollTrigger: {
      trigger: '#scroll-section', start: '10% top', end: '20% top', scrub: true
    }
  });
});
```

**Page transitions (if specified in PRD):**

```javascript
// transitions.js — Barba.js Iron Curtain
import barba from '@barba/core';

barba.init({
  transitions: [{
    name: 'iron-curtain',
    async leave() {
      await gsap.to('.transition-overlay', {
        scaleY: 1, transformOrigin: 'bottom center',
        duration: 0.55, ease: 'power3.inOut'
      });
    },
    async enter(data) {
      gsap.set(data.next.container, { autoAlpha: 1 });
      await gsap.to('.transition-overlay', {
        scaleY: 0, transformOrigin: 'top center',
        duration: 0.55, ease: 'power3.inOut', delay: 0.1
      });
      runLoadSequence();
    }
  }]
});
```

---


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

## ═══════════════════════════════════════════════════
## SECTION 10: PHASE 7 — VERIFY
## ═══════════════════════════════════════════════════
### *5-Axis Awwwards-Grade Audit + Iterative REFINE Loop*

**THE REFINE LOOP (minimum 2 complete passes before verification):**
```
LOOK    → Screenshot desktop + mobile + each section individually
REACT   → Gut reaction first. What feels off?
DESCRIBE → Articulate WHY specifically: "Hero text contrast too low"
FIX     → One thing at a time
LOOK    → Screenshot again. Did it work?
→ REPEAT until passing all 5 axes
```

### AXIS 1: AWWWARDS DESIGN SCORE

```
DESIGN:     Visual impact + uniqueness  __/10
            Color + type sophistication __/10
            Spatial composition         __/10
            Aesthetic coherence         __/10
            AVERAGE:                   __/10

USABILITY:  Navigation clarity          __/10
            Content hierarchy           __/10
            Mobile experience           __/10
            Performance feel            __/10
            AVERAGE:                   __/10

CREATIVITY: Originality                 __/10
            Interaction innovation      __/10
            Memorable moments           __/10
            Unexpected details          __/10
            AVERAGE:                   __/10

TOTAL:     __/10  →  ≥ 7.5 PASS | < 7.5 REFINE
```

### AXIS 2: ANIMATION QUALITY (need ≥ 7 checks)

```
□ Every animation has PURPOSE (not decoration)?
□ Easing CONSISTENT (same family throughout)?
□ Timing CALIBRATED (nothing too fast/slow)?
□ Scroll FEELS PHYSICAL (weight + momentum)?
□ Load completes by 1.5s?
□ Motion MATCHES Brand Personality Matrix intensity?
□ No JANK (layout shifts, frame drops)?
□ SMOOTH on mobile (60fps or graceful degradation)?
□ Satisfying HIERARCHY of moments (big + small)?
□ Makes you WANT TO SCROLL MORE?
```

### AXIS 3: TASTE TEST (all 7 must pass — no exceptions)

**T1 — FONT CHOICE:** Designed or defaulted?
```FAIL: Inter/Roboto/Arial on creative/luxury site
PASS: Distinctive, intentional, designed pairing```

**T2 — COLOR DRAMA:** Tension and character?
```FAIL: All neutrals, no accent that pops
PASS: Emotional register clear before words are read```

**T3 — UNEXPECTED DETAIL:** At least one surprise?
```FAIL: Everything behaves exactly as expected
PASS: Something makes them say "show me that again"```

**T4 — SLOW SCROLL TEST:** Every section intentional?
```FAIL: Any section feels leftover or half-finished
PASS: Nothing could be removed without loss```

**T5 — SCREENSHOT TEST:** Would you post this?
```FAIL: Embarrassment at the quality level
PASS: Awwwards/Dribbble ready```

**T6 — COMPETITOR TEST:** Better than top 3 in this space?
```FAIL: Equal or worse on 3+ dimensions
PASS: Wins on at least 1, equal+ on rest```

**T7 — 5-SECOND TEST:** Purpose + emotion in 5 seconds?
```FAIL: Confusion about what this is
PASS: Crystal clear + right emotional register```

### AXIS 4: PERFORMANCE (need ≥ 10/12)

```
□ Lighthouse Performance ≥ 85?
□ LCP < 2.5s?
□ CLS < 0.1?
□ No console errors?
□ Chrome + Firefox + Safari + Edge verified?
□ Mobile 375px verified?
□ Images: WebP + lazy + width/height?
□ Fonts: preloaded + font-display: swap?
□ Only transform + opacity animated?
□ will-change cleared after animation?
□ Canvas/Three.js properly disposed?
□ Frame preload with loading indicator works?
```

### AXIS 5: BRAND DNA MATCH (need ≥ 5/7)

```
□ Every color used correctly per site-dna-profile.json?
□ Fonts at correct weights + sizes?
□ Spacing consistent with base unit?
□ Motion easing matches motion_personality?
□ Animation intensity matches Brand Personality Matrix?
□ Target audience would respond correctly?
□ Primary emotion from feel-profile.json comes through?
```

### FINAL SIGN-OFF

```
╔══════════════════════════════════════════════════════════════════════╗
║              IRON CANVAS v3 — FINAL SIGN-OFF                         ║
╠══════════════════════════════════════════════════════════════════════╣
║  Axis 1 — Awwwards Design:        __ /10   (need ≥ 7.5)              ║
║  Axis 2 — Animation Quality:      __ /10   (need ≥ 7 checks)         ║
║  Axis 3 — Taste Test:             __ /7    (need 7/7, no exceptions)  ║
║  Axis 4 — Performance:            __ /12   (need ≥ 10)               ║
║  Axis 5 — Brand DNA Match:        __ /7    (need ≥ 5)                ║
╠══════════════════════════════════════════════════════════════════════╣
║  ALL PASS:  ✅ DELIVER — Awwwards-grade, production-ready             ║
║  ANY FAIL:  🔄 ROUTE to remediation (table below)                     ║
╚══════════════════════════════════════════════════════════════════════╝
```

| Fail | Return To |
|------|-----------|
| Axis 1 Design low | Agent-A tokens + Agent-C components |
| Axis 1 Creativity low | Phase 3 Scout → Agent-B add technique |
| Axis 2 animation | Agent-B specific animation |
| Axis 3 T1 fonts | Agent-A tokens.css → font variables |
| Axis 3 T2 color | Agent-A tokens.css → accent strength |
| Axis 3 T3-7 taste | Agent-B/C targeted polish |
| Axis 4 performance | Agent-E fixes + Agent-D image optimization |
| Axis 5 DNA drift | Phase 1 re-run → Agent-A token correction |

---


**v4 ADDITION: After 5-axis verification, run Enhancement Discovery (Agent-E).**
Agent-E suggests 3-5 additive features. Orchestrator decides which enter the Polish Pass.

**UPDATED FINAL SIGN-OFF (v4):**
```
╔══════════════════════════════════════════════════════════════════════╗
║              IRON CANVAS v4.1 — FINAL SIGN-OFF                       ║
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


## ═══════════════════════════════════════════════════
## SECTION 11: PHASE 8 — HANDOFF (v4 WIRED)
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

## ═══════════════════════════════════════════════════
## SECTION 12: § EXPERTISE INJECTION PROTOCOL
## ═══════════════════════════════════════════════════
### *(The Antigravity Pattern — Prompt 7 Adapted)*

> Before any specialized agent begins work that involves a specific API,
> library, or technical domain — inject domain expertise.
> This transforms a general-purpose agent into a specialist.
> Identical to how Prompt 7 in the video made the agent an "expert in Murf Falcon."

**Injection template:**
```markdown
You are now an expert in [technology/API/library].

Load and internalize the following:
[PASTE: official documentation excerpt / API cookbook / key specs]

Understand specifically:
• [Critical concept 1]
• [Critical concept 2]
• [Integration constraint / gotcha]

All future code in this session must strictly follow [technology] best practices.
Verify all implementations against these specs before outputting.
```

**Iron Canvas expertise injections by agent:**

*Agent-B (GSAP):*
```markdown
You are now an expert in GSAP 3 + ScrollTrigger + Lenis.

Key constraints:
• ScrollTrigger requires ScrollTrigger.refresh() after dynamic content loads
• Lenis must sync with GSAP ticker: gsap.ticker.add((time) => lenis.raf(time*1000))
• gsap.ticker.lagSmoothing(0) required for smooth Lenis+GSAP sync
• SplitText: always store split instance, call revert() on resize
• Flip: always use Flip.getState() before DOM changes
• will-change: apply immediately before tween, clearProps: "will-change" in onComplete
• Never animate: top, left, width, height, margin, padding (layout triggers)
• Always animate: transform (translate/scale/rotate), opacity
```

*Agent-B (Three.js/WebGL):*
```markdown
You are now an expert in Three.js r128 + GSAP integration.

Key constraints:
• setPixelRatio: Math.min(window.devicePixelRatio, 2) — never exceed 2x
• renderer.dispose() + geometry.dispose() + material.dispose() on unmount
• Texture cache: use THREE.TextureLoader with cache management
• Camera position changes via GSAP, not direct assignment (for ScrollTrigger sync)
• powerPreference: 'high-performance' in WebGLRenderer options
• WEBGL_lose_context for hot reload cleanup in development
• OrbitControls: not in Three.js r128 CDN bundle — use alternative or import separately
```

*Agent-D (Nano Banana Pro / Gemini Image):*
```markdown
You are now an expert in Nano Banana Pro (Gemini 3 Pro Image Generation).

Command syntax:
uv run {baseDir}/scripts/generate_image.py
  --prompt "..."
  --filename "output.png"
  --resolution [1K/2K/4K]
  --aspect-ratio [1:1/2:3/3:2/3:4/4:3/4:5/5:4/9:16/16:9/21:9]

For edits of existing images:
  -i [input-file]
  --prompt "modification instructions"

Best practices:
• Always include exact hex codes from site-dna-profile.json
• Always include negative constraints (no cold blue, no purple, no flat illustration)
• Generate 4 variants minimum, select best
• 2K resolution for hero/featured images, 1K for secondary
• WebP conversion after generation for performance
```

*Agent-D (Leonardo Blueprints):*
```markdown
You are now an expert in Leonardo AI Blueprints.

Available Blueprints:
Product Studio Photoshoot → professional studio angles from product photo
Product In Scene → lifestyle environment placement
Product Spin Video → 360° rotation → extract with ffmpeg fps=24
Style Transfer → apply site DNA visual identity to any image
Custom Relight → match lighting across frame sets (CRITICAL for sequences)
Background Change → section-specific background matching
Instant Outpaint → expand images for wider containers

API pattern:
POST https://cloud.leonardo.ai/api/rest/v1/blueprints/{id}/run
{ "nodeInputs": { "imageUrl": "...", "prompt": "..." } }
GET https://cloud.leonardo.ai/api/rest/v1/generations/{generationId}

Best practices for scroll sequences:
• Generate keyframes first (8-12 moments), then interpolate with Custom Relight
• Same base prompt for ALL frames — vary action only
• Test 10 frames before committing to full 60
```

---


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

## ═══════════════════════════════════════════════════
## SECTION 13: § DASHBOARD ADDENDUM
## ═══════════════════════════════════════════════════
### *Mission Control, Analytics, Admin UI — Special Route*

Dashboards are a completely different discipline. The rules change entirely.
Scroll physics → panel reveals. Hero sections → bento grids. Cursor trails → data pulses.

**Core principles:**
```
DENSITY IS DESIGN — More information per viewport = more professional
HIERARCHY THROUGH SIZE — Primary metric largest, secondary supporting, tertiary labels
COLOR CARRIES MEANING — One accent = action/key metric. Green/red = status ONLY.
MOTION IS FUNCTIONAL — Counters animate to draw attention. Charts animate on load.
                        NO scroll-pinned heroes. NO WebGL backgrounds. NO cursor trails.
DARK IS DEFAULT — OLED black (#0a0e14), gold accent (#c9a84c) = Iron Canvas signature.
```

**Bento grid system:**
```css
.bento {
  display: grid;
  grid-template-columns: repeat(12, 1fr);
  gap: 1.25rem;
}
.card-hero    { grid-column: span 8; grid-row: span 2; } /* Primary KPI */
.card-medium  { grid-column: span 4; }
.card-small   { grid-column: span 3; }
.card-wide    { grid-column: span 12; }
.card-sidebar { grid-column: span 4; grid-row: span 3; }

@media (max-width: 1023px) {
  .card-hero, .card-medium, .card-sidebar { grid-column: span 6; }
}
@media (max-width: 767px) {
  [class^="card-"] { grid-column: span 12; }
}
```

**Glass card (Iron Canvas dashboard signature):**
```css
.glass-card {
  background: rgba(255, 255, 255, 0.03);
  backdrop-filter: blur(20px);
  -webkit-backdrop-filter: blur(20px);
  border: 1px solid rgba(var(--accent-rgb), 0.12);
  border-radius: 14px;
  position: relative;
}
.glass-card::after {
  content: ''; position: absolute; inset: 1px;
  border-radius: 13px;
  border: 1px solid rgba(255,255,255,0.04);
  pointer-events: none;
}
.glass-card:hover {
  border-color: rgba(var(--accent-rgb), 0.35);
  box-shadow: 0 16px 48px rgba(var(--accent-rgb), 0.1);
  transform: translateY(-2px);
}
```

**Data animation patterns:**
```javascript
// Counter animation (KPI focus draw)
gsap.utils.toArray('[data-counter]').forEach(el => {
  const target = parseInt(el.dataset.counter);
  gsap.from(el, {
    scrollTrigger: { trigger: el, start: 'top 85%' },
    textContent: 0, duration: 2.5, ease: 'power2.out',
    snap: { textContent: 1 },
    onUpdate() {
      el.textContent = (el.dataset.prefix||'') + 
                       Math.round(this.targets()[0].textContent) + 
                       (el.dataset.suffix||'');
    }
  });
});

// Chart bar animation (data entry)
gsap.from('.chart-bar', {
  scaleY: 0, transformOrigin: 'bottom center',
  duration: 0.8, ease: 'power2.out', stagger: 0.08,
  scrollTrigger: { trigger: '.chart', start: 'top 80%' }
});

// Live data pulse
@keyframes data-pulse {
  0%, 100% { opacity: 1; transform: scale(1); }
  50%       { opacity: 0.5; transform: scale(0.85); }
}
.live-indicator { animation: data-pulse 2s ease-in-out infinite; }
```

**THE 5 BENTO CARD ARCHETYPES (v4.2 — Motion Engine):**

Every dashboard bento grid should draw from these archetypes for perpetual micro-motion.
Spring physics (`stiffness: 100, damping: 20`) on all interactive elements — no linear easing.
Each card contains a "perpetual state" that loops infinitely to keep the dashboard feeling alive.

```
ARCHETYPE 1: THE INTELLIGENT LIST
  → Vertical stack of items with infinite auto-sorting loop
  → Items swap positions using layoutId (Framer) or GSAP Flip
  → Simulates AI prioritizing tasks in real-time
  → Sort animation: spring physics, 0.5s duration
  → Sort interval: every 4-6 seconds

ARCHETYPE 2: THE COMMAND INPUT
  → Search/AI bar with multi-step Typewriter Effect
  → Cycles through 3-5 complex prompts with blinking cursor
  → Includes "processing" state: shimmering loading gradient
  → Typewriter speed: 40ms/char, pause: 2s between prompts
  → Uses GSAP or CSS animation — NEVER useState for typing state

ARCHETYPE 3: THE LIVE STATUS
  → Scheduling interface with "breathing" status indicators
  → Pop-up notification badge: overshoot spring effect
  → Badge appears with back.out(2) ease, stays 3s, fades with power2.in
  → Breathing dots: scale 1→1.15→1 infinite loop, 2s duration
  → Status colors: oklch-based green/amber/red tokens

ARCHETYPE 4: THE WIDE DATA STREAM
  → Horizontal infinite carousel of data cards or metrics
  → Seamless loop: x: ["0%", "-100%"] with duplicated content
  → Speed: 30s for full cycle (feels effortless, not frantic)
  → Pause on hover. Resume on leave.
  → Use will-change: transform and translateZ(0) for GPU

ARCHETYPE 5: THE CONTEXTUAL UI (FOCUS MODE)
  → Document view that animates staggered text highlight
  → Followed by "float-in" of a floating action toolbar
  → Toolbar contains micro-icons (edit, share, annotate)
  → Highlight: background-color transition with 0.3s stagger
  → Toolbar: y:10 opacity:0 → y:0 opacity:1, back.out(1.5) ease
```

**Bento archetype performance rules:**
- Each perpetual animation lives in its own isolated component
- React: wrapped in React.memo, uses useMotionValue (not useState)
- Vanilla: wrapped in requestAnimationFrame, uses transform only
- Test: dashboard must maintain 60fps with ALL archetypes running simultaneously
```

**Dashboard North Star scout searches:**
```
"mission control UI dark dashboard premium 2024"
"dark analytics dashboard bento grid inspiration"
"SpaceX Dragon capsule UI design reference"
"NASA mission control modern interface redesign"
"Bloomberg terminal dark UI concept premium"
"glassmorphism data visualization dark gold"
```

---

## ═══════════════════════════════════════════════════
## SECTION 14: § ANTI-PATTERNS
## ═══════════════════════════════════════════════════

| # | Anti-Pattern | Root Cause | Prevention |
|---|-------------|-----------|-----------|
| 1 | **Cookie-Cutter** — all sites identical | Skipping Phase 1 | Complete DNA Profile. Palette comes FROM the site. |
| 2 | **Blind Generation** — artifacts on wrong backgrounds | No pre-gen checklist | Screenshot context first. Always. |
| 3 | **Template Imposition** — forcing a style | Aesthetic preference applied universally | Phase 4: adapt to site, never impose. |
| 4 | **Batch-and-Pray** — all images at once | Time pressure | 4 variants → select → test → iterate. One at a time. |
| 5 | **Identity Erasure** — unrecognizable from original | Over-enhancing | "Same site but better?" If no, pull back. |
| 6 | **Trinket Dropping** — images not integrated | Upload and done | Every artifact: CSS verified in situ. |
| 7 | **Video-as-Animation** — MP4 for scroll | Videos are easier | NEVER `<video>`. Always Canvas + frames + ScrollTrigger. |
| 8 | **Frame Inconsistency** — scroll sequence looks like slideshow | Different prompts | SAME base prompt, vary action only. |

---


### 9. One-Shot Prompting ★v4
**What it looks like:** Opening a coding editor and typing "build me a dashboard" then prompting linearly — fixing errors, fighting linters, rewriting components, wondering why the UI keeps drifting.
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

**Craft Wisdom (v4 — from Samir's Applied AI Engineering):**

**Feature Discovery Post-Build:**
After the initial build is stable, ask the agent: "What other features can we add
to make this more appealing?" This often surfaces sound design, custom cursor
refinements, and micro-interactions that weren't in the original scope.

**Post-Build Micro-Interaction Pass:**
Sound design, custom cursors, and micro-interactions are added AFTER the main
build, not during. Agent-C runs two sweeps: Core Pass → Polish Pass.

### § DESIGN SLOP — AI TELLS TO ELIMINATE (v4.2)

> These are CSS/content patterns that make AI output look generic.
> ALL agents scan output against this list before committing.
> Full list with examples: references/anti-patterns.md Section II.

**Visual/CSS Tells — NEVER produce:**
- Pure #000000 → use off-black (#0a0a0a, #111111)
- Neon/outer glow box-shadows → tint shadows to background hue
- Default Tailwind shadows (shadow-md/lg/xl) → customize and tint
- Oversaturated accents (saturation > 80%) → desaturate
- h-screen → ALWAYS min-h-[100dvh] (iOS Safari)
- Flexbox percentage math → CSS Grid
- Emojis in markup/text/alt → icons or SVG
- Animating top/left/width/height → transform + opacity only

**Typography Tells — NEVER produce:**
- Inter font for premium/creative (unless DNA Profile specifies it)
- Oversized H1s (use weight/color for hierarchy, not just size)
- System fonts as only choice → self-host with font-display: swap
- Orphan words in headings → text-wrap: balance
- Serif in dashboard/software UIs → sans-serif + monospace only

**Layout Tells — NEVER produce:**
- Centered Hero when BPM Bold ≥ 5 → split/asymmetric
- 3-column equal card feature rows → zig-zag, asymmetric, masonry
- No max-width container → max-w-[1400px] mx-auto
- Cards everywhere → only when elevation communicates hierarchy

**Content Tells — NEVER produce:**
- Generic names: "John Doe", "Jane Smith", "Acme Corp"
- Fake numbers: 99.99%, 50%, $100.00 → use organic data: 47.2%, $99.00
- AI clichés: "Elevate", "Seamless", "Unleash", "Next-Gen", "Game-changer", "Delve"
- Lorem Ipsum → real draft copy
- Broken Unsplash links → picsum.photos/seed/{name}/800/600
- Same avatar for multiple users → unique per person
- "Oops!" error messages → direct: "Connection failed. Please try again."

### § OUTPUT ENFORCEMENT (v4.2)

> A partial output is a broken output. No agent produces lazy code.
> Full protocol: references/output-enforcement.md

**BANNED in code blocks:**
`// ...`, `// rest of code`, `// TODO`, `// similar to above`, `// continue pattern`, `// add more as needed`, bare `...`

**BANNED in prose:**
"Let me know if you want me to continue", "For brevity...", "The rest follows the same pattern", "And so on"

**BANNED structural shortcuts:**
Skeleton when full implementation requested. First+last section skipping middle. One example + description replacing repeated logic.

**On token limit:** Write at full quality to a clean breakpoint, then:
`[PAUSED — X of Y complete. Send "continue" to resume from: {next section}]`
No compression. No skipping ahead. No summary.

### § DEPENDENCY VERIFICATION (v4.2)

Before importing ANY 3rd-party library:
1. CHECK package.json — is it installed?
2. If MISSING → output install command FIRST
3. NEVER assume a library exists

Tailwind: check v3 vs v4 before using syntax.
Next.js: interactive components must be 'use client' leaf components.

### § RESPONSIVE HARDENING (v4.2)

Non-negotiable mobile rules:
- ALL multi-column layouts → single column below 768px. No exceptions.
- Touch targets ≥ 44px on ALL interactive elements
- Display type: clamp(2.5rem, 7vw, 5rem) — never overflows
- Body text minimum: 1rem (16px)
- Horizontal overflow on mobile = critical failure
- Content constrained: max-w-[1400px] mx-auto
- Full rules: references/grid-rhythm.md Step 7

### § STATE COMPLETENESS MANDATE (v4.2)

Every interactive element: Default → Hover → Focus-Visible → Active → Disabled
Every view: Loading state (skeleton) + Empty state (CTA) + Error state (inline)
No circular spinners. No "Oops!" messages. No dead-end empty states.

## ═══════════════════════════════════════════════════
## SECTION 15: § INVOCATIONS (v4)
## ═══════════════════════════════════════════════════

```
# MISSION MODE — Full team
Iron Canvas v4.2 MISSION MODE for [project].
Full team. Discovery Interview first. Phases 0-8.
Target: Awwwards Site of the Day quality.

# SWARM MODE — Standard production
Iron Canvas v4.2 SWARM MODE for [URL/project].
Phases 0-3.9 sequential. Then parallel agents. Merge and verify.

# SOLO MODE — Quick enhancement
Iron Canvas v4.2 SOLO for [URL].
Phase 1 FIRST — no changes before DNA profile.

# DASHBOARD BUILD
Iron Canvas v4.2 MISSION MODE — DASHBOARD ROUTE for [name].
Type C project. Bento + glass + data animation.

# SCROLL SEQUENCE — Keyframe Interpolation (v4)
Iron Canvas v4.2 Phase 5 scroll sequence for [site].
Method: Keyframe Interpolation (Whisk/Nano Banana start+end → Flow → 15fps extraction).
Product: [description]. Section: [where, dimensions].

# HANDOFF
Iron Canvas v4.2 Phase 8 HANDOFF for [project]. Generate HANDOFF.md.
```

---

## ═══════════════════════════════════════════════════
## SECTION 16: § TASTE DOCTRINE
## ═══════════════════════════════════════════════════

**1. RESTRAINT IS A SUPERPOWER**
3 animations that wow > 30 that tire.

**2. TYPOGRAPHY IS THE DESIGN**
Fix type before adding any effect. If it can't survive as text-only, the problem is the type.

**3. COLOR TELLS THE EMOTIONAL STORY**
Palette communicates before the first word is read. Design it to feel right in 3 seconds.

**4. ANIMATION REVEALS QUALITY, DOESN'T CREATE IT**
Get the static version right. THEN animate. A bad design animated is a bad design moving.

**5. THE ONE UNFORGETTABLE THING**
Design for the single moment people screenshot. Everything else is context leading to it.

**6. COPY TECHNIQUE, NOT STYLE**
Acceptable: same GSAP technique as an Awwwards winner.
Not acceptable: copying their visual language.

**7. THE 15-SECOND SCROLL**
Users scroll your site in 15 seconds on first pass. Best moments must be visible in that window.

**8. MOBILE IS NOT A DOWNGRADE**
Different canvas, different physics, different constraints.
Preserve ONE signature animation. Never zero.

---

## ═══════════════════════════════════════════════════
## SECTION 17: § PRODUCTION BRANCHING PROTOCOL
## ═══════════════════════════════════════════════════

```bash
# 1. Lock production before starting
git checkout main && vercel --prod  # confirm live

# 2. All work on staging branch
git checkout -b iron-canvas-[project-name]

# 3. Visual diff before merge
# Screenshot staging at identical viewports to production
# Present side-by-side for approval

# 4. Incremental promotion
# Merge phase by phase — never all at once

# 5. After approval
git checkout main
git merge iron-canvas-[project-name]
vercel --prod  # Deploy and verify live
```

---


## § REFERENCE FILE ROUTING (v4.1 COMPLETE)

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

## § OUTPUT ARTIFACTS (v4.1)

```
iron_canvas_output/
├── orient-decision.json              ← Phase 0 (+ Discovery Interview + Performance Tier + Autonomy)
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

*Iron Canvas Master Skill v4.1 — Island Development Crew*
*"Enhancement means amplifying what's already good, not replacing it with a uniform style."*
*"Your coding agents are only as good as the instructions and the assets you feed them."*
*"Where there is no vision, the people perish." — Proverbs 29:18 (KJV)*
