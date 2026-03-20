# IRON CANVAS — v4 REPO FILE MAP
## *What changed from v3 to v4*

🔄 = REPLACE your existing file with this version
🆕 = NEW file or newly populated (didn't exist or was empty framework)
✅ = KEEP as-is from v3

---

```
iron-canvas/
│
├── SKILL.md                              🔄  REPLACE  (v4 — full wiring + video integration)
├── ROUTING.md                            ✅  KEEP     (v3.1 routing still valid, SKILL.md now routes)
├── CHANGELOG.md                          🔄  REPLACE  (v4 entry added)
├── README.md                             ✅  KEEP     (update version refs manually: v3→v4)
├── REPO_MAP.md                           🔄  REPLACE  (this file — v4 map)
├── STRATEGIC_SYNTHESIS.md                ✅  KEEP     (gaps now closed in v4)
├── QUICK_REFERENCE.md                    ✅  KEEP     (update version refs manually: v3→v4)
├── FEEL.md                               ✅  KEEP     (unchanged)
├── Iron_Canvas_v1.md                     ✅  KEEP     (historical reference)
├── OPUS_HANDOFF.md                       ✅  KEEP     (historical — this session's handoff)
├── index.html                            ✅  KEEP     (Iron Canvas studio site)
├── vercel.json                           ✅  KEEP     (unchanged)
│
├── phases/
│   ├── 00-orient.md                      ✅  KEEP     (Discovery Interview in SKILL.md routes here)
│   ├── 01-study.md                       ✅  KEEP     (screen recording note in SKILL.md)
│   ├── 02-feel.md                        ✅  KEEP     (new output structure in SKILL.md)
│   ├── 03-scout.md                       ✅  KEEP     (Whisk+Flow in SKILL.md engine registry)
│   ├── 03.5-validate.md                  ✅  KEEP     (unchanged)
│   ├── 03.9-package.md                   ✅  KEEP     (Asset Manifest in SKILL.md Section 5)
│   ├── 04-forge.md                       ✅  KEEP     (unchanged)
│   ├── 05-generate.md                    ✅  KEEP     (keyframe interpolation in SKILL.md)
│   ├── 06-compose.md                     ✅  KEEP     (15fps protocol in SKILL.md)
│   ├── 07-refine.md                      ✅  KEEP     (Enhancement Discovery in SKILL.md)
│   └── 08-handoff.md                     ✅  KEEP     (now wired into pipeline via SKILL.md)
│
├── agent-prompts/
│   ├── orchestrator.md                   🔄  REPLACE  (v4 — Discovery Interview + Phase 8)
│   ├── agent-a-foundation.md             ✅  KEEP     (dark mode trigger in SKILL.md)
│   ├── agent-b-motion.md                 ✅  KEEP     (motion tier gating in SKILL.md)
│   ├── agent-c-ui.md                     🔄  REPLACE  (v4 — Two-Sweep Pattern)
│   ├── agent-d-artifacts.md              🔄  REPLACE  (v4 — Asset Classification + Whisk/Flow)
│   └── agent-e-qa.md                     🔄  REPLACE  (v4 — Enhancement Discovery + MCP QA)
│
├── references/
│   ├── anti-patterns.md                  🔄  REPLACE  (v4 — 3 new anti-patterns + craft wisdom)
│   ├── scroll-engine.md                  ✅  KEEP     (unchanged)
│   ├── model-selection.md                🔄  REPLACE  (v4 — Whisk + Flow + asset taxonomy)
│   ├── prompt-engineering.md             ✅  KEEP     (unchanged)
│   ├── leonardo-blueprints.md            ✅  KEEP     (unchanged)
│   ├── expertise-injection.md            ✅  KEEP     (Whisk/Flow injections in SKILL.md)
│   ├── structural-policy.md              ✅  KEEP     (unchanged)
│   ├── typography-system.md              ✅  KEEP     (now wired via SKILL.md Phase 2)
│   ├── color-system.md                   ✅  KEEP     (now wired via SKILL.md Phase 2)
│   ├── motion-budget.md                  ✅  KEEP     (now wired via SKILL.md Phase 2)
│   ├── grid-rhythm.md                    ✅  KEEP     (now wired via SKILL.md Phase 4)
│   ├── performance-budget.md             ✅  KEEP     (now wired via SKILL.md Phase 0)
│   ├── interaction-library.md            ✅  KEEP     (now wired via SKILL.md Agent-C)
│   ├── seo-conversion.md                 ✅  KEEP     (now wired via SKILL.md Phase 1+5+7)
│   ├── agent-autonomy.md                 🆕  NEW      (v4 — self-provisioning protocol)
│   └── video-integration-protocol.md     🔄  REPLACE  (v4 — 7 hooks fully populated)
│
├── templates/
│   ├── site-dna-profile.md               ✅  KEEP     (unchanged)
│   ├── feel-profile.md                   ✅  KEEP     (unchanged)
│   ├── invocation-templates.md           ✅  KEEP     (v4 invocations in SKILL.md Section 14)
│   ├── design-prd.md                     ✅  KEEP     (Asset Manifest addition in SKILL.md)
│   └── technical-validation-report.md    ✅  KEEP     (unchanged)
│
└── sub-skills/                           ✅  KEEP FOLDER (legacy v1 protocols)
    ├── 01-PERCEPTION.md
    ├── 02-MOTION-ARCHITECTURE.md
    ├── 03-FORGE.md
    └── 04-VERIFY.md
```

---

## Summary Count

```
✅ KEEP (untouched):   25 files
🔄 REPLACE:            8 files (SKILL, CHANGELOG, REPO_MAP, orchestrator,
                                 agent-c, agent-d, agent-e, anti-patterns,
                                 model-selection, video-integration-protocol)
🆕 NEW:                1 file  (agent-autonomy.md)
─────────────────────────
TOTAL:                 34 files across 6 folders + root
```

---

## What The v4 Archive Contains

The downloaded archive includes ONLY the 🔄 REPLACE and 🆕 NEW files.
Your ✅ KEEP files stay exactly as they are on GitHub.

```
IRON_CANVAS_V4/
├── SKILL.md                              ← replace in repo root
├── CHANGELOG.md                          ← replace in repo root
├── REPO_MAP.md                           ← replace in repo root
├── agent-prompts/
│   ├── orchestrator.md                   ← replace
│   ├── agent-c-ui.md                     ← replace
│   ├── agent-d-artifacts.md              ← replace
│   └── agent-e-qa.md                     ← replace
└── references/
    ├── anti-patterns.md                  ← replace
    ├── model-selection.md                ← replace
    ├── agent-autonomy.md                 ← NEW (self-provisioning protocol)
    └── video-integration-protocol.md     ← replace (was empty framework, now populated)
```

---

## What v4 Wires That v3.1 Didn't

The v3.1 reference files EXISTED but weren't connected to SKILL.md.
v4 SKILL.md now explicitly routes agents to read them at the correct phases:

```
File                              → Wired Into SKILL.md At
─────────────────────────────────────────────────────────────
typography-system.md              → Phase 2 FEEL output + Agent-A
color-system.md                   → Phase 2 FEEL output + Agent-A
motion-budget.md                  → Phase 2 FEEL output + Agent-B
grid-rhythm.md                    → Phase 4 FORGE + Agent-A
performance-budget.md             → Phase 0 ORIENT output
interaction-library.md            → Phase 4/6 + Agent-C
seo-conversion.md                 → Phase 1 + Phase 5 + Phase 7
phases/08-handoff.md              → Pipeline (Section 10 + Orchestrator)
video-integration-protocol.md     → Phase 3 + Phase 5 + Agent-D
```

---

*Iron Canvas v4 — Island Development Crew*
*"Where there is no vision, the people perish." — Proverbs 29:18 (KJV)*
