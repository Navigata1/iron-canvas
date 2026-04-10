# TASTE-SKILL → IRON CANVAS GAP ANALYSIS
## What needs to be absorbed before v4.1 enhancements land

> Prepared: March 29, 2026
> Taste-skill repo: github.com/Leonxlnx/taste-skill (7 skills, 50 commits, 5.5K stars)
> Iron Canvas repo: github.com/Navigata1/iron-canvas (v4.1, 37 files, 88K SKILL.md)

---

## EXECUTIVE SUMMARY

Iron Canvas and taste-skill solve the same problem from different angles:
- **Iron Canvas** is a *pipeline* — it studies a site, scores brand personality, generates a North Star, then enhances with multi-agent orchestration
- **Taste-skill** is a *ruleset* — it defines configuration dials, forbidden patterns, and specific CSS/component-level anti-slop rules

Iron Canvas already covers ~70% of what taste-skill teaches, but taste-skill has **specific, actionable enforcement rules at the CSS and content level** that Iron Canvas currently lacks. These are the "last mile" rules that prevent agents from producing generic-looking output even when the pipeline is followed correctly.

**The core insight:** Iron Canvas tells agents *what process to follow*. Taste-skill tells agents *what code NOT to write*. Iron Canvas needs both.

---

## GAP 1: DESIGN SLOP ANTI-PATTERNS (CRITICAL)
**Taste-skill has it. Iron Canvas does NOT.**

Iron Canvas's `references/anti-patterns.md` covers 11 *workflow* anti-patterns (Cookie-Cutter, Blind Generation, Template Imposition, etc.). These are process failures.

Taste-skill has a completely different category: **design-level AI tells** — the CSS patterns and content patterns that make AI output look generic. Iron Canvas has ZERO coverage of these.

### Rules Iron Canvas needs to absorb:

**Visual / CSS Anti-Tells:**
- NO neon/outer glow box-shadows. Use inner borders or tinted shadows only
- NO pure `#000000` black. Use off-black, Zinc-950, or charcoal
- NO oversaturated accent colors. Saturation < 80%
- NO excessive gradient text on large headers
- NO custom mouse cursors (ruins performance/accessibility)
- NO default `box-shadow` values (`shadow-md`, `shadow-lg`). Tint to background hue
- NO `h-screen` for full-height sections. ALWAYS `min-h-[100dvh]` (iOS Safari fix)
- NO complex flexbox percentage math. Use CSS Grid instead
- NO emojis in code, markup, text content, headings, or alt text

**Typography Anti-Tells:**
- NO `Inter` font for premium/creative contexts. Use `Geist`, `Outfit`, `Cabinet Grotesk`, `Satoshi`
- NO oversized H1s that just "scream." Control hierarchy with weight and color
- Serif BANNED in dashboard/software UIs

**Layout Anti-Tells:**
- NO centered Hero sections when brand Bold ≥ 5. Force split screen or asymmetric
- NO 3-column equal card feature rows. Use zig-zag, asymmetric grid, or horizontal scroll
- NO 3-column Bootstrap-style grids without massive whitespace

**Content Anti-Tells:**
- NO generic names: "John Doe", "Jane Smith", "Sarah Chan"
- NO startup slop names: "Acme", "Nexus", "SmartFlow"
- NO fake round numbers: `99.99%`, `50%`, `$100.00`. Use organic data: `47.2%`, `$99.00`
- NO AI copywriting clichés: "Elevate", "Seamless", "Unleash", "Next-Gen", "Game-changer", "Delve"
- NO Lorem Ipsum. Write real draft copy
- NO broken Unsplash links. Use `picsum.photos/seed/{name}/800/600` or SVG avatars
- NO same avatar image for multiple users

**Where it goes in Iron Canvas:** NEW section in `references/anti-patterns.md` — rename to "Anti-Patterns & AI Design Tells". Add a "DESIGN SLOP" section below the existing 11 workflow anti-patterns. Wire into Phase 4 (FORGE) and Agent-A's token generation checklist.

---

## GAP 2: OUTPUT ENFORCEMENT PROTOCOL (HIGH)
**Taste-skill has it (output-skill). Iron Canvas does NOT.**

The output-skill prevents AI agents from being lazy:

**Banned output patterns:**
- `// ...`, `// rest of code`, `// implement here`, `// TODO`
- `// similar to above`, `// continue pattern`, `// add more as needed`
- "Let me know if you want me to continue"
- "For brevity..." / "the rest follows the same pattern"
- Outputting a skeleton when full implementation was requested
- Showing first and last section while skipping the middle

**Handling long outputs:**
```
[PAUSED — X of Y complete. Send "continue" to resume from: next section name]
```
No compression, no skipping ahead.

**Where it goes in Iron Canvas:** NEW file `references/output-enforcement.md`. Wire into ALL agent prompts (A through E) and the orchestrator. This is especially critical for Agent-A (foundation code) and Agent-B (motion code) where lazy output = broken sites.

---

## GAP 3: INTERACTIVE STATE MANDATE (MEDIUM)
**Taste-skill mandates it. Iron Canvas covers it partially.**

Iron Canvas has `references/interaction-library.md` which defines HOW to implement states. But taste-skill adds a **mandatory generation rule**: agents MUST implement full interaction cycles:

- **Loading states:** Skeletal loaders matching layout dimensions (no generic circular spinners)
- **Empty states:** Beautifully composed empty states indicating how to populate data
- **Error states:** Clear, inline error reporting (no `window.alert()`)
- **Active/Pressed feedback:** `-translate-y-[1px]` or `scale-[0.98]` on `:active`

Iron Canvas's interaction-library.md already has button states and form states, but doesn't mandate loading/empty/error as **required deliverables** for every component. Add this mandate to Agent-C's prompt.

---

## GAP 4: SPECIFIC HIGH-END COMPONENT PATTERNS (MEDIUM)
**Taste-skill has named patterns. Iron Canvas has conceptual coverage but less specificity.**

### From soft-skill — Double-Bezel ("Doppelrand") Architecture:
```
Outer Shell: bg-black/5, ring-1 ring-black/5, p-1.5, rounded-[2rem]
Inner Core: own background, shadow-[inset_0_1px_1px_rgba(255,255,255,0.15)],
            rounded-[calc(2rem-0.375rem)] for concentric curves
```
This specific technique for making cards look like machined hardware is not in Iron Canvas.

### From soft-skill — Button-in-Button Trailing Icon:
Arrow icons nested in their own circular wrapper within the button, not floating naked next to text.

### From soft-skill — Fluid Island Navigation:
Floating glass pill nav (`mt-6 mx-auto w-max rounded-full`), hamburger morphing to X, screen-filling overlay with staggered mask reveal.

### From soft-skill — Creative Variance Engine:
Silent "roll" selecting vibe archetype (Ethereal Glass / Editorial Luxury / Soft Structuralism) + layout archetype (Asymmetrical Bento / Z-Axis Cascade / Editorial Split). Iron Canvas does this through the Brand Personality Matrix, but the specific pattern catalog here is richer.

**Where it goes:** Enrich `references/interaction-library.md` with these named patterns. Add the Double-Bezel and Button-in-Button to Agent-C's component toolkit.

---

## GAP 5: DEPENDENCY VERIFICATION RULE (MEDIUM)
**Taste-skill has it. Iron Canvas does NOT.**

Before importing ANY 3rd party library, agents MUST check `package.json`. If missing, output the install command FIRST. Never assume a library exists.

Also: Tailwind version lock — check `package.json` first, don't use v4 syntax in v3 projects. For v4, don't use `tailwindcss` plugin in `postcss.config.js` — use `@tailwindcss/postcss`.

**Where it goes:** Add to Agent-A's foundation prompt and the orchestrator's Phase 4 checklist.

---

## GAP 6: RESPONSIVE HARDENING RULES (MEDIUM)
**Taste-skill is more specific. Iron Canvas has general responsiveness.**

Specific rules Iron Canvas should absorb:
- ALL multi-column layouts collapse to single column below 768px. No exceptions
- Touch targets: minimum 44px tap area on all interactive elements
- `clamp()` for all display typography (already partially in typography-system.md)
- Contain layouts with `max-w-[1400px] mx-auto` or `max-w-7xl`
- No horizontal scroll on mobile is a critical failure signal

**Where it goes:** Add specific rules to `references/grid-rhythm.md` and Agent-A's foundation prompt.

---

## GAP 7: MOTION IMPLEMENTATION SPECIFICS (LOW-MEDIUM)
**Both systems cover motion, but taste-skill has React-specific performance rules Iron Canvas lacks.**

Key rule Iron Canvas should absorb for React/Next.js projects:
- **NEVER use React `useState` for magnetic hover or continuous animations.** Use Framer Motion's `useMotionValue` and `useTransform` outside the render cycle
- **Perpetual motion MUST be memoized** (`React.memo`) and isolated in microscopic Client Components. Never trigger re-renders in parent layout
- **GSAP and Framer Motion NEVER mixed in the same component tree.** Default to Framer Motion for UI interactions. GSAP exclusively for isolated scrolltelling or canvas backgrounds
- **`staggerChildren` parent and children MUST reside in the same Client Component tree**
- **Use `IntersectionObserver` for scroll reveals, never `window.addEventListener('scroll')`**

Iron Canvas already uses GSAP-first approach and has motion tiers, but when agents encounter React/Next.js projects, these Framer Motion rules prevent performance collapse.

**Where it goes:** Add a "REACT/NEXT.JS MOTION RULES" subsection to `references/motion-budget.md`.

---

## GAP 8: CREATIVE ARSENAL NAMED PATTERNS (LOW)
**Both have pattern libraries, but taste-skill catalogs 30+ named patterns Iron Canvas doesn't list.**

Patterns worth absorbing into `references/interaction-library.md`:
- Parallax Tilt Card (3D mouse-tracking)
- Spotlight Border Card (border illumination under cursor)
- Holographic Foil Card (iridescent rainbow shift on hover)
- Tinder Swipe Stack (physical card swiping)
- Morphing Modal (button expands into dialog)
- Horizontal Scroll Hijack (vertical scroll → horizontal gallery)
- Zoom Parallax (background zoom tied to scroll)
- Scroll Progress Path (SVG lines drawing on scroll)
- Kinetic Marquee (reversing/speeding text bands on scroll)
- Text Mask Reveal (typography as window to video)
- Text Scramble Effect (Matrix-style decode on load)
- Particle Explosion Button (CTAs shattering into particles)
- Directional Hover Aware Button (fill entering from mouse entry side)
- Mesh Gradient Background (lava-lamp animated color blobs)

These are specifically named so agents can reference them by name during Phase 5/6 generation.

---

## GAP 9: BENTO MOTION ENGINE CARD ARCHETYPES (LOW)
**Taste-skill has 5 specific card archetypes. Iron Canvas has the dashboard addendum but is less specific.**

The 5 Bento card types from taste-skill:
1. **The Intelligent List** — auto-sorting infinite loop with `layoutId`
2. **The Command Input** — multi-step typewriter effect with processing state
3. **The Live Status** — breathing indicators with overshoot spring notification badges
4. **The Wide Data Stream** — infinite horizontal carousel (`x: ["0%", "-100%"]`)
5. **The Contextual UI** — staggered text highlight + floating toolbar

These are valuable for Iron Canvas's Dashboard Route (Type C projects).

**Where it goes:** Add to the Dashboard Addendum section in SKILL.md.

---

## GAP 10: REDESIGN AUDIT CHECKLIST (LOW)
**Taste-skill's redesign-skill is a dedicated audit. Iron Canvas Phase 1 extracts DNA instead.**

Iron Canvas's approach (study the site first, extract DNA) is philosophically superior — it adapts to what's there rather than imposing rules. But taste-skill's redesign audit checklist has ~60 specific checks organized by category (Typography, Color, Layout, Interactivity, Content, Components, Icons, Code Quality) that could serve as a validation layer.

**Recommendation:** Don't replace Phase 1. Instead, add a subset of the redesign audit checks to Phase 7 (REFINE) as a "Design Quality Gate" — a checklist that catches common AI design mistakes before handoff.

---

## WHAT IRON CANVAS ALREADY DOES BETTER

For completeness, here's where Iron Canvas is stronger than taste-skill:

1. **Pipeline discipline** — taste-skill has no equivalent to Study→Feel→Scout→Forge→Generate→Compose→Verify
2. **Brand Personality Matrix** — 6-axis scoring (taste-skill has 3 dials, much simpler)
3. **AI image generation** — North Star system, Artifact Assessment Gate, Keyframe Interpolation. Taste-skill has zero image generation
4. **Scroll engine architecture** — Canvas + ScrollTrigger + 15fps frame extraction. Taste-skill mentions scroll patterns but doesn't architect them
5. **Multi-agent orchestration** — 5 specialized agents with autonomy tiers. Taste-skill is single-agent
6. **Asset classification** — SCROLL-TIED / LOOPING / STATIC taxonomy. Taste-skill doesn't classify assets
7. **Cross-LLM validation** — Phase 3.5. Taste-skill has no validation layer
8. **Design PRD packaging** — Phase 3.9. Taste-skill has no PRD concept
9. **Client handoff** — Phase 8. Taste-skill has no handoff
10. **oklch color system** — Perceptually uniform palette generation. Taste-skill uses hex

---

## IMPLEMENTATION PRIORITY

| Priority | Gap | Effort | Files to Modify |
|----------|-----|--------|-----------------|
| **P0** | Gap 1: Design Slop Anti-Patterns | Medium | `references/anti-patterns.md`, `SKILL.md` |
| **P0** | Gap 2: Output Enforcement | Low | NEW `references/output-enforcement.md`, all agent prompts |
| **P1** | Gap 5: Dependency Verification | Low | `agent-prompts/agent-a-foundation.md`, `SKILL.md` |
| **P1** | Gap 3: State Mandate | Low | `agent-prompts/agent-c-ui.md`, `SKILL.md` |
| **P1** | Gap 6: Responsive Hardening | Low | `references/grid-rhythm.md`, `agent-prompts/agent-a-foundation.md` |
| **P2** | Gap 7: React Motion Rules | Low | `references/motion-budget.md` |
| **P2** | Gap 4: High-End Patterns | Medium | `references/interaction-library.md` |
| **P3** | Gap 8: Creative Arsenal | Low | `references/interaction-library.md` |
| **P3** | Gap 9: Bento Archetypes | Low | Dashboard Addendum in `SKILL.md` |
| **P3** | Gap 10: Redesign Audit | Medium | Phase 7 in `phases/07-refine.md` |

---

## RECOMMENDATION

**Do NOT merge taste-skill wholesale into Iron Canvas.** The philosophies are different:
- Taste-skill imposes a specific aesthetic (anti-Inter, anti-centered, anti-3-column)
- Iron Canvas derives aesthetics from the site's existing DNA

Instead, absorb taste-skill's rules as **guardrails** — things agents should avoid regardless of brand personality — rather than as aesthetic mandates. The "AI tells" (no pure black, no fake data, no AI copywriting clichés) are universal. The layout preferences (no centered hero, no 3-column cards) should be conditioned on the Brand Personality Matrix scores, not absolute bans.

**Suggested approach:**
1. Create `references/design-quality-gates.md` — the universal anti-slop rules
2. Create `references/output-enforcement.md` — the lazy output prevention rules
3. Enrich existing reference files with the specific rules from gaps 3-9
4. Update SKILL.md with inline references to the new guardrails (maintaining the self-containment rule)
5. Push all changes to staging. Review. Then main.

---

*Analysis complete. Awaiting Jon's direction on which gaps to close first.*
