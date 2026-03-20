# expertise-injection.md — Specialized Technical Knowledge

Inject these modules into the relevant Build Agent prompts or PRDs to ensure technical excellence.

## 1. GSAP & MOTION (Inject into AGENT-B)
- **Engine:** GSAP 3.x with ScrollTrigger.
- **Canvas Implementation:** Use `requestAnimationFrame` for drawing frames. Map `progress` to `Math.floor(progress * (totalFrames - 1))`.
- **Optimization:** Cap `devicePixelRatio` at 2. Use `will-change: transform`.
- **Easing:** Prefer `cubic-bezier(0.34, 1.56, 0.64, 1)` (The Iron Spring).

## 2. NANO BANANA PRO & ARTIFACTS (Inject into AGENT-D)
- **Model:** Gemini 3 Pro Image (Nano Banana Pro).
- **Prompt Protocol:** [Subject] + [Material] + [Hex Colors] + [Lighting] + [Context].
- **Consistency:** Use the "Same Base Prompt" protocol for frame sequences.
- **Leonardo Blueprints:** Use for 360° Spin Video and Style Transfer matching.

## 3. CLAUDE CODE BEST PRACTICES (Global Injection)
- **RPIT:** Research domain before writing code.
- **Spec-Driven:** Always reference the Design PRD as the anchor.
- **Validation:** Use `playwright` or screenshots to verify visual state.
- **Context Management:** Keep sessions focused; clear context after merging features.

## 4. ACCESSIBILITY & PERFORMANCE (Inject into AGENT-E)
- **A11y:** WCAG AA (4.5:1 contrast). ARIA-labels for all custom UI.
- **Perf:** LCP < 2.5s. Optimize images to WebP via `cwebp`.
- **Reduced Motion:** Always implement `@media (prefers-reduced-motion: reduce)`.
