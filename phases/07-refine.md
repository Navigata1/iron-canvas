# Phase 7: REFINE — Iterative Polish

> The refinement loop: LOOK → REACT → DESCRIBE → FIX → LOOK AGAIN

## The Rule

You are never done after one pass. Premium quality requires iteration. Look at the result, react honestly, describe what's wrong, fix it, look again. Repeat until you'd be proud to show it.

## The Refinement Loop

```
LOOK → REACT → DESCRIBE → FIX → LOOK AGAIN
  ↑                                    ↓
  └────────────────────────────────────┘
         (repeat until premium)
```

### LOOK
Screenshot the page. Full page desktop. Full page mobile. Each section individually. Look at it like a user seeing it for the first time.

### REACT
Gut reaction. What feels off? What catches your eye (good or bad)? Don't analyze yet — just react.

### DESCRIBE
Now articulate: WHY does that thing feel off? Be specific:
- "The hero text competes with the background — not enough contrast"
- "Product cards feel static — missing hover lift effect"
- "The scroll animation stutters at 40% progress — frame gap too large"

### FIX
Apply the fix. One thing at a time.

### LOOK AGAIN
Screenshot again. Did the fix work? Did it create new problems?

## Quality Checklist (Per Site — Adapt to DNA)

### Identity Preservation
- [ ] Site retains its unique personality and palette
- [ ] Enhanced version is recognizably the SAME site but better
- [ ] No elements feel foreign or imposed from a different aesthetic

### Visual Quality
- [ ] All images blend into their containers naturally
- [ ] No floating objects on mismatched backgrounds
- [ ] Typography hierarchy is clear using the site's own fonts
- [ ] Shadows tinted to the site's own hue
- [ ] Color contrast passes WCAG AA (4.5:1 for body text)

### Interaction Quality
- [ ] Hover/active/focus states on every interactive element
- [ ] Scroll animations fire smoothly (no mobile jank)
- [ ] Touch targets ≥ 44×44px on mobile
- [ ] No unexpected layout shifts during interaction

### Scroll Engine Quality (If Applicable)
- [ ] Scroll sequence scrubs smoothly in both directions
- [ ] Content overlays sync with animation timing
- [ ] Loading experience is graceful (progress indicator)
- [ ] No blank canvas at any scroll position
- [ ] Mobile fallback works (reduced frames or static image)

### Performance
- [ ] Lighthouse Performance score ≥ 85
- [ ] Largest Contentful Paint < 2.5s
- [ ] First Input Delay < 100ms
- [ ] Cumulative Layout Shift < 0.1
- [ ] Frame preloading doesn't block initial render

### Cross-Device
- [ ] Desktop (1440px) — verified
- [ ] Tablet (768px) — verified
- [ ] Mobile (375px) — verified
- [ ] Mobile landscape — no broken layouts

## Common Refinement Patterns

### Problem: Image doesn't blend
**Fix:** Add CSS overlay gradient matching the section's background color:
```css
filter: brightness(0.8) saturate(1.2);
/* or */
mix-blend-mode: multiply;
```

### Problem: Text unreadable over image
**Fix:** Add gradient scrim:
```css
background: linear-gradient(to top, rgba(0,0,0,0.7) 0%, transparent 50%);
```

### Problem: Scroll animation stutters
**Fix:** Check frame count and gap. Add intermediate frames where stutter occurs. Increase `scrub` value for more smoothness.

### Problem: Hover states feel generic
**Fix:** Tint the hover effect to the site's palette:
```css
/* Instead of: */
transform: scale(1.02);
/* Use: */
transform: scale(1.02) translateY(-4px);
box-shadow: 0 12px 40px rgba(var(--brand-rgb), 0.2);
```

### Problem: Mobile scroll is laggy
**Fix:** Reduce frame count, lower resolution, disable non-essential animations:
```css
@media (max-width: 768px) {
  .grain::after { display: none; }
  .parallax { transform: none !important; }
}
```

## Phase 7 Completion Criteria

- [ ] Full refinement loop completed (minimum 2 passes)
- [ ] All quality checklist items pass
- [ ] Desktop, tablet, and mobile verified with screenshots
- [ ] Performance metrics within targets
- [ ] Final screenshot captures saved for documentation
- [ ] User approval obtained before promoting to production

## Promotion to Production

Once Phase 7 is complete and approved:
1. Create visual diff (staging vs current production screenshots)
2. Present to stakeholder for approval
3. Merge staging → main (per Production Branching Protocol)
4. Verify production deployment
5. Document in project changelog

---

*← [Phase 6: COMPOSE](06-compose.md) | Back to [Iron_Canvas_v1.md](../Iron_Canvas_v1.md)*
