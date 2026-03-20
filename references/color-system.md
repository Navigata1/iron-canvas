# COLOR SYSTEM
## *Iron Canvas — Phase 2 Integration*

> Color is not decoration. It is the emotional frequency of the brand.
> Every Iron Canvas build extracts, extends, and deploys color with intention.
> This file governs palette construction, gradient specification, and shadow protocol.

---

## STEP 1: PALETTE EXTRACTION

Before generating any CSS, extract the brand's existing color identity.

```
EXTRACTION SOURCES (in priority order):
1. Logo / wordmark (most authoritative)
2. Existing hero imagery (ambient palette)
3. Brand guidelines (if available in prompt)
4. Industry color conventions (fallback)

EXTRACT THESE VALUES:
→ Primary brand color (the "signature" hue)
→ Secondary brand color (if exists)
→ Background preference (pure black / off-black / paper / cream / pure white)
→ Text color (pure black tends to be harsh — 95% black is better)
→ Accent (can be derived if not explicit)
```

---

## STEP 2: OKLCH PALETTE EXTENSION

Modern color systems use oklch (perceptually uniform) not hex → hex guesswork.
oklch(L C H) — Lightness 0-1, Chroma 0-0.4, Hue 0-360°

```css
/* EXAMPLE: Brand primary = oklch(0.55 0.18 260) — a deep indigo */

/* Derive full palette via chroma/lightness shifts, NOT hue rotation */
:root {
  /* Primary family */
  --color-primary-950: oklch(0.15 0.18 260); /* darkest */
  --color-primary-900: oklch(0.22 0.20 260);
  --color-primary-800: oklch(0.30 0.22 260);
  --color-primary-700: oklch(0.40 0.22 260);
  --color-primary-600: oklch(0.50 0.20 260);
  --color-primary-500: oklch(0.55 0.18 260); /* brand anchor */
  --color-primary-400: oklch(0.65 0.16 260);
  --color-primary-300: oklch(0.75 0.12 260);
  --color-primary-200: oklch(0.85 0.08 260);
  --color-primary-100: oklch(0.93 0.04 260);
  --color-primary-50:  oklch(0.97 0.02 260);

  /* Semantic tokens derived from primary */
  --color-accent:      var(--color-primary-500);
  --color-accent-glow: oklch(0.55 0.22 260 / 0.4); /* for glow effects */
  --color-surface:     oklch(0.08 0.02 260);        /* dark bg */
  --color-surface-alt: oklch(0.12 0.03 260);        /* card bg */
  --color-text:        oklch(0.96 0.01 260);        /* near-white body */
  --color-text-muted:  oklch(0.65 0.04 260);        /* secondary text */
  --color-border:      oklch(0.22 0.05 260 / 0.6);  /* subtle borders */
}
```

**Harmony options (choose one per project):**
```
ANALOGOUS:       Shift hue ±30° for secondary (safe, cohesive)
COMPLEMENTARY:   Shift hue +180° for accent contrast (high impact)
SPLIT-COMP:      Hue ±150° for triadic tension (avant-garde/editorial)
MONOCHROMATIC:   Same hue, vary L and C only (refined, luxury)
```

---

## STEP 3: GRADIENT MESH SPECIFICATION

Gradient mesh is the signature texture of premium 2024-2026 design.
Not flat gradients — organic, multi-point mesh that breathes.

**When to use:**
```
Brand Personality bold ≥ 6 → gradient mesh on hero background
Brand Personality avant-garde ≥ 7 → full-page gradient mesh system
Luxury/cinematic feel profile → deep mesh with low opacity noise overlay
Corporate/functional feel profile → subtle gradient, near-flat
```

**Implementation:**
```css
/* Conic gradient mesh (organic feel) */
.mesh-bg {
  background:
    radial-gradient(ellipse 80% 60% at 20% 30%,
      oklch(0.40 0.20 260 / 0.6) 0%, transparent 70%),
    radial-gradient(ellipse 60% 80% at 80% 70%,
      oklch(0.35 0.18 200 / 0.5) 0%, transparent 70%),
    radial-gradient(ellipse 100% 40% at 50% 0%,
      oklch(0.55 0.22 290 / 0.3) 0%, transparent 60%),
    oklch(0.08 0.02 260); /* base */
}

/* Noise overlay (grain texture — premium feel) */
.mesh-bg::after {
  content: '';
  position: absolute;
  inset: 0;
  background-image: url("data:image/svg+xml,..."); /* SVG noise filter */
  opacity: 0.035; /* subtle — should be felt not seen */
  mix-blend-mode: overlay;
}
```

**Mesh configuration by feel profile:**
```
DEEP/LUXURY:     3-4 radial gradients, dark base, low opacity (0.3-0.5)
                 Grain opacity: 0.04-0.06
VIBRANT/BOLD:    2-3 gradients, saturated colors, higher opacity (0.5-0.7)
                 Grain opacity: 0.02-0.04
LIGHT/CLEAN:     1-2 gradients, pastel chroma, very low opacity (0.1-0.3)
                 Grain opacity: 0.015-0.025
CORPORATE/FLAT:  No mesh. Maximum 1 subtle directional gradient.
```

---

## STEP 4: SHADOW PROTOCOL

Flat gray shadows are a dead giveaway of generic design.
Branded shadows match the ambient light of the design's color palette.

```css
/* RULE: Shadows should be tinted to the brand's primary hue */

/* ❌ Generic: */
box-shadow: 0 4px 20px rgba(0, 0, 0, 0.3);

/* ✅ Branded: */
box-shadow:
  0 4px 20px oklch(0.10 0.15 260 / 0.4),  /* ambient — brand tinted */
  0 1px 4px oklch(0.05 0.10 260 / 0.6);   /* sharp contact shadow */

/* ELEVATED (cards, modals) */
box-shadow:
  0 20px 60px oklch(0.08 0.18 260 / 0.5),
  0 4px 16px oklch(0.08 0.15 260 / 0.3),
  inset 0 1px 0 oklch(0.40 0.10 260 / 0.2); /* top edge highlight */

/* GLOW (CTA buttons, active states, featured items) */
box-shadow:
  0 0 0 1px var(--color-accent / 0.3),
  0 0 20px var(--color-accent-glow),
  0 4px 12px oklch(0.08 0.18 260 / 0.4);
```

---

## STEP 5: DARK MODE PROTOCOL

When Brand Personality bold ≥ 6 OR feel includes dark/night/deep energy:

```css
/* tokens.css already establishes light tokens */
/* tokens-dark.css overrides them */

@media (prefers-color-scheme: dark) {
  :root {
    --color-surface:     oklch(0.08 0.02 260);
    --color-surface-alt: oklch(0.12 0.03 260);
    --color-text:        oklch(0.96 0.01 260);
    --color-text-muted:  oklch(0.65 0.04 260);
    --color-border:      oklch(0.22 0.05 260 / 0.5);
    /* Primary/accent stay the same — only surfaces and text flip */
  }
}

/* Manual toggle support (data-theme attribute) */
[data-theme="dark"] {
  /* same as above */
}
```

**Agent-A generates dark mode tokens when:**
```
feel-profile.json → dark_mode: true
OR Brand Personality bold ≥ 6
OR feel_profile.emotion includes: "night", "deep", "cinematic", "dark", "moody"
```

---

## INTEGRATION POINT: feel-profile.json

Phase 2 output must include:

```json
{
  "color": {
    "primary_oklch": "oklch(0.55 0.18 260)",
    "secondary_oklch": "oklch(0.50 0.20 200)",
    "background_type": "near-black | off-white | pure-white | paper",
    "harmony": "analogous | complementary | monochromatic",
    "gradient_mesh": true,
    "mesh_intensity": "deep | vibrant | light | none",
    "grain_overlay": true,
    "grain_opacity": 0.04,
    "shadow_tint": true,
    "dark_mode": false
  }
}
```

---

*Iron Canvas v3 — references/color-system.md*
