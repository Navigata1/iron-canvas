# IRON CANVAS — REPO FILE MAP
## *What's new, what's updated, what's untouched*

Extract the tar.gz and your repo should look exactly like this.
✅ = already in your repo, keep as-is
🔄 = REPLACE your existing file with this version
🆕 = NEW file, add to repo (didn't exist before)

---

```
iron-canvas/
│
├── SKILL.md                              🔄  REPLACE  (v3.0 — full multi-agent system)
├── ROUTING.md                            🆕  NEW      (master bridge file — critical)
├── README.md                             🔄  REPLACE  (updated for v3)
├── CHANGELOG.md                          🔄  REPLACE  (updated for v3)
├── FEEL.md                               ✅  KEEP     (unchanged)
├── index.html                            ✅  KEEP     (Iron Canvas studio site)
├── vercel.json                           ✅  KEEP     (unchanged)
├── Iron_Canvas_v1.md                     ✅  KEEP     (your original — historical ref)
│
├── phases/
│   ├── 00-orient.md                      🆕  NEW      (project type + mode selection)
│   ├── 01-study.md                       ✅  KEEP     (unchanged)
│   ├── 02-feel.md                        ✅  KEEP     (unchanged)
│   ├── 03-scout.md                       🔄  REPLACE  (was 03-collect.md — now has
│   │                                                    North Star image generation)
│   ├── 03.5-validate.md                  🆕  NEW      (cross-LLM technical validation)
│   ├── 03.9-package.md                   🆕  NEW      (Design PRD packaging)
│   ├── 04-forge.md                       ✅  KEEP     (unchanged)
│   ├── 05-generate.md                    🔄  REPLACE  (was thin — now has mandatory
│   │                                                    Artifact Assessment Gate,
│   │                                                    confidence scoring, Leonardo
│   │                                                    browser protocol, scroll frames)
│   ├── 06-compose.md                     🔄  REPLACE  (was thin — now has full
│   │                                                    scroll engine assembly,
│   │                                                    agent merge sequence,
│   │                                                    integration verification)
│   └── 07-refine.md                      ✅  KEEP     (unchanged)
│
├── agent-prompts/                        🆕  NEW FOLDER (didn't exist before)
│   ├── orchestrator.md                   🆕  NEW      (includes Phase 5/6 mandatory
│   │                                                    dispatch checklists)
│   ├── agent-a-foundation.md             🆕  NEW
│   ├── agent-b-motion.md                 🆕  NEW
│   ├── agent-c-ui.md                     🆕  NEW
│   ├── agent-d-artifacts.md              🆕  NEW
│   └── agent-e-qa.md                     🆕  NEW
│
├── references/
│   ├── anti-patterns.md                  ✅  KEEP     (unchanged)
│   ├── scroll-engine.md                  ✅  KEEP     (unchanged)
│   ├── model-selection.md                ✅  KEEP     (unchanged)
│   ├── prompt-engineering.md             ✅  KEEP     (unchanged)
│   ├── leonardo-blueprints.md            ✅  KEEP     (unchanged)
│   └── expertise-injection.md            🆕  NEW      (domain injection for each agent)
│
├── templates/
│   ├── site-dna-profile.md               ✅  KEEP     (unchanged)
│   ├── feel-profile.md                   ✅  KEEP     (unchanged)
│   ├── invocation-templates.md           🔄  REPLACE  (updated for v3 modes)
│   ├── design-prd.md                     🆕  NEW      (Phase 3.9 PRD template)
│   └── technical-validation-report.md    🆕  NEW      (Phase 3.5 template)
│
└── sub-skills/                           ✅  KEEP FOLDER (legacy v1 sub-skills,
    ├── 01-PERCEPTION.md                              still valid as focused tools)
    ├── 02-MOTION-ARCHITECTURE.md
    ├── 03-FORGE.md
    └── 04-VERIFY.md
```

---

## Summary Count

```
✅ KEEP (untouched):   14 files across phases/, references/, templates/, sub-skills/
🔄 REPLACE:             7 files (SKILL, README, CHANGELOG, 03-scout, 05-generate,
                                  06-compose, invocation-templates)
🆕 NEW:                11 files (ROUTING, 00-orient, 03.5-validate, 03.9-package,
                                  entire agent-prompts/ folder, expertise-injection,
                                  design-prd, technical-validation-report)
─────────────────────────
TOTAL AFTER:           32 files across 6 folders + root
```

---

## What The Archive Contains (tar.gz)

The downloaded archive includes ONLY the 🔄 REPLACE and 🆕 NEW files.
Your ✅ KEEP files stay exactly as they are in GitHub.

```
Archive structure after extraction:
IRON_CANVAS_REPO/
├── ROUTING.md                ← drop in repo root
├── SKILL.md                  ← replace in repo root
├── README.md                 ← replace in repo root
├── CHANGELOG.md              ← replace in repo root
├── agent-prompts/            ← new folder, drop whole thing
│   ├── orchestrator.md
│   ├── agent-a-foundation.md
│   ├── agent-b-motion.md
│   ├── agent-c-ui.md
│   ├── agent-d-artifacts.md
│   └── agent-e-qa.md
├── phases/
│   ├── 00-orient.md          ← new file in existing phases/ folder
│   ├── 03-scout.md           ← replace existing 03-collect.md (rename)
│   ├── 03.5-validate.md      ← new file in existing phases/ folder
│   ├── 03.9-package.md       ← new file in existing phases/ folder
│   ├── 05-generate.md        ← replace existing phases/05-generate.md
│   └── 06-compose.md         ← replace existing phases/06-compose.md
├── references/
│   └── expertise-injection.md ← new file in existing references/ folder
└── templates/
    ├── design-prd.md          ← new file in existing templates/ folder
    ├── invocation-templates.md ← replace existing
    └── technical-validation-report.md ← new file in templates/ folder
```

---

*Iron Canvas v3 — Island Development Crew*
