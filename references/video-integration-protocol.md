# VIDEO INTEGRATION PROTOCOL
## *Iron Canvas — Pending Transcript Integration*

> **STATUS: FRAMEWORK BUILT — AWAITING TRANSCRIPT CONTENT**
>
> This file was pre-built from three YouTube videos shared by Jon
> that demonstrate building beautiful digital experiences.
>
> Video IDs:
>   Video 1: j74kjYvzzLk
>   Video 2: N_X9Zt8nXwk
>   Video 3: DUOvVST7fCw
>
> To complete this file:
> 1. Paste transcripts to Claude (copy from YouTube → Show transcript)
>    OR run through your YouTube v4.0 pipeline and paste the output
> 2. Claude reads all three and populates the sections below
> 3. Each section maps insights to functional Iron Canvas protocol
>
> Pre-built hooks are ready. The file integrates immediately upon transcript delivery.

---

## HOW INSIGHTS ARE CLASSIFIED

Every insight from the videos falls into one of four categories:

```
CATEGORY A: PHILOSOPHY
  → Mental models, principles, design thinking approaches
  → Integrates into: SKILL.md preamble, Phase 2 (FEEL), Orchestrator brief
  → Example: "Design systems should feel alive, not mechanical"

CATEGORY B: TECHNIQUE
  → Specific implementation methods, code patterns, tools
  → Integrates into: Phase-specific files, expertise-injection.md, references/
  → Example: "Use clip-path: inset() for elegant text reveal animations"

CATEGORY C: WORKFLOW
  → Process insights, sequencing decisions, agent-level behaviors
  → Integrates into: Orchestrator, phase files, agent prompts
  → Example: "Explore 10 directions before committing to one"

CATEGORY D: CRAFT DETAIL
  → The 1% decisions that separate great from excellent
  → Integrates into: interaction-library.md, agent-c-ui.md, anti-patterns
  → Example: "Easing curves should match the emotional register of the moment"
```

---

## PRE-BUILT INTEGRATION HOOKS

These sections exist now. They will be populated when transcripts arrive.

---

### HOOK 1: FEEL PHILOSOPHY ADDENDUM
*Target: phases/02-feel.md — Section: Emotional Design Principles*
*Category: A — Philosophy*

```
[TO BE POPULATED FROM VIDEO INSIGHTS]

Expected content: How the creator approaches "feel" before visual execution.
How they translate a brief or intention into emotional direction.
What questions they ask before opening any software.
```

**Integration plan:**
Add as a callout box in phases/02-feel.md titled:
"Field-Tested Emotional Design Principles" with attribution to creator's approach.
The insights become questions in the feel-profile.json output.

---

### HOOK 2: VISUAL COMPOSITION PRINCIPLES
*Target: references/composition.md (new file, created from video content)*
*Category: A + B — Philosophy + Technique*

```
[TO BE POPULATED FROM VIDEO INSIGHTS]

Expected content: How the creator thinks about where things go on a page.
Hierarchy principles. What the eye does. Focal points. White space use.
Any specific compositional frameworks or mental models they use.
```

**Integration plan:**
New file `references/composition.md` will be created.
Referenced from Phase 1 (STUDY) and Phase 4 (FORGE).
Agent-A consults this when making layout structure decisions.

---

### HOOK 3: ANIMATION PHILOSOPHY
*Target: references/motion-budget.md — Section: Motion Intent*
*Category: A — Philosophy*

```
[TO BE POPULATED FROM VIDEO INSIGHTS]

Expected content: How the creator decides what should move and why.
The relationship between motion and meaning. Common motion anti-patterns
they call out. How to use motion to guide attention without distraction.
```

**Integration plan:**
Add as "Motion Intent Principles" section at top of references/motion-budget.md.
These principles precede the technical motion budget scoring.

---

### HOOK 4: TYPOGRAPHY CRAFT DETAILS
*Target: references/typography-system.md — Section: Craft Details*
*Category: D — Craft Detail*

```
[TO BE POPULATED FROM VIDEO INSIGHTS]

Expected content: Specific typographic observations the creator makes.
How they approach type as a design element. Pairing logic. Scale decisions.
Any specific typefaces or combinations they use and why.
```

**Integration plan:**
Appended to references/typography-system.md as a "Craft Details" section.
Applied through Agent-A and Agent-C token decisions.

---

### HOOK 5: INTERACTION CRAFT DETAILS
*Target: references/interaction-library.md — Section: Craft Notes*
*Category: D — Craft Detail*

```
[TO BE POPULATED FROM VIDEO INSIGHTS]

Expected content: Hover states, transitions, micro-interactions the creator
emphasizes. Specific GSAP patterns they demonstrate. Any novel interaction
approaches not already in the Iron Canvas library.
```

**Integration plan:**
Appended to references/interaction-library.md as a "From the Field" section.
Immediately usable by Agent-C.

---

### HOOK 6: TOOL / WORKFLOW DISCOVERIES
*Target: references/expertise-injection.md or model-selection.md*
*Category: B + C — Technique + Workflow*

```
[TO BE POPULATED FROM VIDEO INSIGHTS]

Expected content: Any specific tools, libraries, APIs, or workflows
demonstrated that aren't already in Iron Canvas. If the creator uses
a specific version of something or a custom approach to a common tool.
```

**Integration plan:**
New tools → expertise-injection.md with full injection block.
Workflow discoveries → relevant phase file or new reference doc.
Model/AI tool recommendations → model-selection.md update.

---

### HOOK 7: THE CREATOR'S MENTAL MODEL (IF DISTINCT)
*Target: SKILL.md — Section: Design Philosophy / Or new philosophy.md*
*Category: A — Philosophy*

```
[TO BE POPULATED FROM VIDEO INSIGHTS]

Expected content: The creator's overall design philosophy, if they articulate one.
How they describe what makes something beautiful vs. merely functional.
Their standard for when work is "done."
The north star they aim for that shapes all their decisions.
```

**Integration plan:**
If the creator has a coherent, distinct mental model not already in Iron Canvas:
Create `references/design-philosophy.md` as a companion to SKILL.md.
Reference in Orchestrator agent prompt as philosophical context.

---

## AFTER TRANSCRIPT DELIVERY: INTEGRATION CHECKLIST

```
□ All insights extracted and classified (A/B/C/D)
□ Hook 1 populated + phases/02-feel.md updated
□ Hook 2 populated + references/composition.md created
□ Hook 3 populated + references/motion-budget.md updated
□ Hook 4 populated + references/typography-system.md updated
□ Hook 5 populated + references/interaction-library.md updated
□ Hook 6 populated + relevant files updated
□ Hook 7 assessed → philosophy.md created if warranted
□ ROUTING.md updated with any new files
□ Orchestrator prompt updated if philosophy-level shifts apply
□ CHANGELOG.md updated: "Video Integration — [creator name] insights added"
□ Archive updated: iron-canvas-v3-final.tar.gz rebuilt
```

---

## WHAT MAKES THIS DIFFERENT FROM JUST READING A VIDEO

The goal is not to quote the creator. It is to distill their practice
into protocol that Iron Canvas agents execute without human guidance.

A useful principle becomes a checklist item.
A demonstrated technique becomes an expertise injection block.
A mental model becomes a question in the feel profile.
A craft detail becomes a specific line in an agent prompt.

Iron Canvas doesn't collect inspiration. It converts inspiration into execution.

---

*Iron Canvas v3 — references/video-integration-protocol.md*
*Status: Framework complete — pending transcript content*
