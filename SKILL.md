---
name: iron-canvas-master
version: 3.0
description: >
  Iron Canvas is an adaptive, site-aware, multi-agent design enhancement and
  creation methodology. It is not a template — it is an orchestration system.

  Three lineages fused into one definitive methodology:
  (A) Island Development Crew production pipeline — 7-phase battle-tested system
      from real projects: Oakwood AI Hub, Crown Collection, Iron Canvas Studio site.
      Failure taught Phase 1 (uniform templates killed site identity). Success encoded everything else.
  (B) Rigorous animation architecture — Brand Personality Matrix, GSAP motion taxonomy,
      Awwwards 5-axis verification, AI Reference Scout with North Star image generation.
  (C) Antigravity multi-agent orchestration pattern — parallel Build Agents, Cross-LLM
      Technical Validation, Design PRD Packaging, Expertise Injection Protocol, and
      Router-Worker swarm architecture for maximum throughput.

  Three modes:
    SOLO:    One agent, full pipeline, sequential execution. Slower, simpler to orchestrate.
    SWARM:   Orchestrator + up to 5 parallel Build Agents. Faster, higher quality.
    MISSION: Full team — Orchestrator + Research + Validation + 5 Build Agents + QA. Fastest.

  Trigger for ANY digital design task: websites, dashboards, apps, scroll animations,
  mission controls, landing pages, or brand experiences.
  Runs natively in: OpenClaw, Antigravity Agent Manager, Claude Code, any agentic AI.

author: Iron Canvas — Island Development Crew
origin: >
  "Where there is no vision, the people perish." — Proverbs 29:18 (KJV)
---

# ⚡ IRON CANVAS v3
## *The Multi-Agent Design Orchestration System*

> **The Golden Rule:** Before changing anything — STUDY what's there.
> Extract. Understand. Then enhance.
>
> "Enhancement means amplifying what's already good, not replacing it
> with a uniform style."

---

## ═══════════════════════════════════════════════════
## THE COMPLETE PIPELINE — ALL THREE MODES
## ═══════════════════════════════════════════════════

### SOLO MODE (1 agent, sequential)
```
ORIENT(0)→STUDY(1)→FEEL(2)→SCOUT(3)→VALIDATE(3.5)→PACKAGE(3.9)→FORGE(4)→GENERATE(5)→COMPOSE(6)→VERIFY(7)
```

### SWARM MODE (1 orchestrator + parallel build agents)
```
                    ┌─ ORCHESTRATOR ─────────────────────────────────────────────┐
                    │                                                             │
ORIENT(0)→STUDY(1)→FEEL(2)→SCOUT(3)→VALIDATE(3.5)→PACKAGE(3.9)                │
                    │           ↓ Design PRD dispatched to all agents simultaneously  │
                    │  ┌─────────────────────────────────────────────────────┐   │
                    │  │  AGENT-A       AGENT-B       AGENT-C       AGENT-D  │   │
                    │  │  Foundation    Motion        UI/UX         Artifacts │   │
                    │  │  (tokens +     (GSAP +       (components   (image    │   │
                    │  │   structure)    scroll)       + cursor)     gen)     │   │
                    │  └──────┬──────────┬─────────────┬────────────┬────────┘   │
                    │         └──────────┴─────────────┴────────────┘            │
                    │                           ↓ MERGE                          │
                    │                    COMPOSE(6) + VERIFY(7)                  │
                    └────────────────────────────────────────────────────────────┘
```

### MISSION MODE (full team, maximum power)
```
┌─ ORCHESTRATOR (Claude Opus) ─────────────────────────────────────────────────────┐
│                                                                                    │
│  [RESEARCH AGENT]──STUDY(1)──FEEL(2)──SCOUT(3)──────────────────────────────┐   │
│                                                                                │   │
│  [VALIDATION AGENT]──Cross-LLM Technical Check──────────────────────────────┐│   │
│                                                                               ││   │
│  ──────────── PACKAGE(3.9): Design PRD issued to all Build Agents ──────────┘│   │
│                                                                               │   │
│  ┌──AGENT-A──┐  ┌──AGENT-B──┐  ┌──AGENT-C──┐  ┌──AGENT-D──┐  ┌─AGENT-E─┐ │   │
│  │Foundation  │  │  Motion   │  │  UI/UX    │  │ Artifacts  │  │ A11y +  │ │   │
│  │Tokens+HTML │  │GSAP+3D+   │  │Components │  │Image Gen + │  │Perf+QA  │ │   │
│  │Structure   │  │ScrollEng  │  │Cursor+Nav │  │Scroll Seq  │  │Audit    │ │   │
│  └─────┬──────┘  └─────┬─────┘  └─────┬─────┘  └─────┬──────┘  └────┬────┘ │   │
│        └───────────────┴───────────────┴──────────────┴──────────────┘      │   │
│                                         ↓                                     │   │
│                           [MERGE + VERIFY AGENT]──────────────────────────────┘   │
│                           COMPOSE(6) + 5-AXIS AUDIT(7)                            │
└────────────────────────────────────────────────────────────────────────────────────┘
```

---

## ═══════════════════════════════════════════════════
## SECTION 1: ORCHESTRATOR AGENT
## ═══════════════════════════════════════════════════
### *The Architect — Never Writes Code, Only Governs*

The Orchestrator is the master agent. It is the Mission Controller. Its job:
1. Run Phases 0-3.9 (research + feel + scout + validation + packaging)
2. Issue the Design PRD to specialized Build Agents
3. Monitor Build Agent progress and resolve conflicts
4. Run Phase 7 verification across all agent outputs
5. Deliver the final product

**Orchestrator system prompt:**
```markdown
You are the Iron Canvas Orchestrator. You are an expert design engineer and
creative director for the Iron Canvas design studio. Your role is to:

1. Run the Iron Canvas methodology through Phases 0-3.9 (ORIENT through PACKAGE)
2. Produce a complete Design PRD that Build Agents can execute independently
3. Dispatch that PRD to specialized Build Agents simultaneously
4. Review their outputs, resolve integration conflicts, and compose the final deliverable
5. Run the 5-axis Awwwards-grade verification audit

You NEVER write implementation code yourself — you architect, design, and judge.
Your output before dispatch: site-dna.json, feel-profile.json, north-star.png,
validation-report.md, design-prd.md

Model recommendation: Claude Opus / Gemini 3 Pro Deep Think (highest reasoning)
```

---

## ═══════════════════════════════════════════════════
## SECTION 2: PHASE 0 — ORIENT
## ═══════════════════════════════════════════════════
### *Project Classification & Mode Selection*

```json
{
  "project_type": "A/B/C/D/E/F",
  "execution_mode": "SOLO / SWARM / MISSION",
  "phase_emphasis": ["which phases get maximum attention"],
  "agent_team": ["which agents to spawn in SWARM/MISSION"],
  "tech_stack_default": "MINIMAL / STANDARD / ELEVATED / IMMERSIVE"
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

**MODE SELECTION GUIDE:**
```
SOLO:    Small sites, quick enhancemnts, single-developer context
SWARM:   Standard productions — parallel agents 2-3x faster
MISSION: Complex sites, dashboards, immersive experiences, Iron Canvas showcase work
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

## ═══════════════════════════════════════════════════
## SECTION 6: THE BUILD AGENTS — PARALLEL EXECUTION
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

## ═══════════════════════════════════════════════════
## SECTION 7: PHASE 6 — COMPOSE (MERGE + INTEGRATE)
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

## ═══════════════════════════════════════════════════
## SECTION 8: PHASE 7 — VERIFY
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

## ═══════════════════════════════════════════════════
## SECTION 9: § EXPERTISE INJECTION PROTOCOL
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

## ═══════════════════════════════════════════════════
## SECTION 10: § DASHBOARD ADDENDUM
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
## SECTION 11: § ANTI-PATTERNS
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

## ═══════════════════════════════════════════════════
## SECTION 12: § OPENCLAW + ANTIGRAVITY INVOCATIONS
## ═══════════════════════════════════════════════════

```
# MISSION MODE — Full team, maximum quality
Iron Canvas v3 MISSION MODE for [project].
Spawn agents: Research, Validation, Foundation(A), Motion(B), UI(C), Artifacts(D), QA(E).
Start: Orchestrator runs Phases 0-3.9 and produces Design PRD.
Then dispatch PRD to all Build Agents simultaneously.
Merge per Section 7. Verify with 5-axis audit.
Target: Awwwards Site of the Day quality.

# SWARM MODE — Standard production
Iron Canvas v3 SWARM MODE for [URL/project].
Phases 0-3.9 sequential (Orchestrator). Then parallel:
Agent-A: tokens + structure. Agent-B: motion. Agent-C: UI. Agent-D: artifacts.
Merge and verify.

# SOLO MODE — Quick enhancement
Iron Canvas v3 SOLO for [URL].
Run full pipeline sequentially. Phase 1 FIRST — no changes before DNA profile.
Output: production-ready enhanced site + verification-report.json.

# DASHBOARD BUILD
Iron Canvas v3 MISSION MODE — DASHBOARD ROUTE for [name].
Type C project. Scout: mission control UI references + North Star generation.
Deploy: Foundation + Motion(dashboard patterns) + UI(bento+glass) + Data(counters/charts) + QA.
Style: OLED black (#0a0e14), gold accent (#c9a84c), glassmorphism cards.

# SCROLL SEQUENCE ONLY
Iron Canvas v3 Phase 5-6 scroll sequence for [site].
Product: [description]. Section: [where it lives, dimensions].
Agent-D: 10-frame prototype first. If smooth → 60-frame full set.
Agent-B: Canvas + ScrollTrigger scroll engine. Content overlays per PRD timing.

# NARRATED SCROLL (Voice AI + Scroll — from Antigravity pattern)
Iron Canvas v3 MISSION MODE for [site] with narrated scroll experience.
Phase 3.5 VALIDATION AGENT: verify WebSocket TTS feasibility in browser,
AudioContext user-gesture requirement, scroll-sync latency budget.
If FEASIBLE: Agent-B adds useFalcon.ts hook integration at scroll trigger points.
Agent-C: floating mic UI component (idle/listening/speaking states).
Voice engine: [Murf Falcon / ElevenLabs / Web Speech API].
```

---

## ═══════════════════════════════════════════════════
## SECTION 13: § TASTE DOCTRINE
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
## § PRODUCTION BRANCHING PROTOCOL
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

## § OUTPUT ARTIFACTS

```
iron_canvas_output/
├── site-dna-profile.json            ← Phase 1
├── feel-profile.json                ← Phase 2
├── north-star-reference.png         ← Phase 3
├── scout-report.json                ← Phase 3
├── technical-validation-report.md   ← Phase 3.5 ★ NEW
├── design-prd.md                    ← Phase 3.9 ★ NEW
├── agent-outputs/
│   ├── agent-a/ (tokens, HTML, base CSS)
│   ├── agent-b/ (scroll, motion, transitions)
│   ├── agent-c/ (components, cursor, nav)
│   ├── agent-d/ (artifacts, prompts, frames/)
│   └── agent-e/ (audits, qa-fixes)
├── implementation/                  ← Phase 6 merged output
│   ├── tokens.css
│   ├── index.html
│   ├── styles/ (base, components, animations)
│   └── scripts/ (main, scroll, cursor, transitions, webgl)
└── verification-report.json         ← Phase 7
    ├── axis_1 through axis_5 scores
    └── final_verdict: DELIVER / REFINE
```

---

*Iron Canvas Master Skill v3.0 — Island Development Crew*
*"Enhancement means amplifying what's already good, not replacing it with a uniform style."*
*"Where there is no vision, the people perish." — Proverbs 29:18 (KJV)*

## § MANDATORY EXECUTION STANDARDS (Added 2026-03-19)

### Leonardo AI Dashboard — MANDATORY for Phase 5

Iron Canvas Phase 5 MUST include Leonardo AI Blueprint workflows when image generation is needed.

**Execution:** The agent MUST open Chrome and navigate to app.leonardo.ai to:
1. Use **Product Studio Photoshoot** for hero images and product angles
2. Use **Style Transfer** to match generated images to the site's DNA palette
3. Use **Custom Relight** for cross-frame lighting consistency
4. Use **Product Spin Video** for 360° sequences → extract frames with ffmpeg
5. Use **Background Change** to match section-specific contexts

**How to access:**
```
browser(action="open", url="https://app.leonardo.ai", profile="user")
browser(action="navigate", url="https://app.leonardo.ai/ai-generations")
```

The agent has full computer access. Chrome must be opened by the agent, not the user.
Leonardo AI is not optional — it is part of the standard Phase 5 pipeline alongside Nano Banana Pro.

### World-Class Reference Standard — Automotive Luxury

For product showcase sites (Type D), the reference standard is NOT generic e-commerce.
The standard is:

**MANDATORY RESEARCH TARGETS:**
- **Porsche** (porsche.com) — configurator, 360° views, color/trim selection
- **Lamborghini** (lamborghini.com) — dramatic heroes, immersive scroll, product storytelling
- **Ferrari** (ferrari.com) — editorial luxury, configurator, lifestyle integration
- **Koenigsegg** (koenigsegg.com) — extreme premium, bespoke configurator, engineering porn

**What to extract from these sites:**
1. Product configurator patterns (select variant → live visual update)
2. Hero image treatments (full-bleed, parallax, atmospheric)
3. Color/variant selector UX (how they handle multiple options elegantly)
4. Scroll-driven product reveals (how they unfold the product story)
5. Material/texture close-up sections
6. The "build your own" interactive experience

**For Crown Collection specifically:**
The site should have a scent/size selector that functions like a car configurator:
- Select scent → jar label updates, background atmosphere changes, scent notes animate in
- Select size → jar scales proportionally, price updates with counter animation
- "Build Your Crown" interactive experience — not just a shop page with cards

### No-Image Sites Are Phase 5 FAILURES

If Phase 1 STUDY reveals a site with ZERO images (like Crown Collection), Phase 5 is the
HIGHEST PRIORITY phase. The agent must:
1. Generate hero imagery from the site's content (transcripts, copy, brand story)
2. Generate product photography (from descriptions if no real photos exist)
3. Generate atmospheric/lifestyle images for each section that currently uses CSS-only backgrounds
4. Generate scent/variant-specific imagery
5. Build scroll-sequence frames if the product story warrants it

A site with no images that completes Iron Canvas with still no images is a FAILED run.
