# Accessibility checklist

## Must-haves on `site/`
- [ ] Every image has descriptive alt text (not the filename)
- [ ] Heading hierarchy: one `<h1>`, then `<h2>`s, then `<h3>`s. Don't skip levels.
- [ ] CTAs are real `<a>` or `<button>` elements, not styled `<div>`s
- [ ] Body copy minimum 16px, line-height 1.5+
- [ ] **Contrast:** the warm orange `#F4A261` on white `#FDFCFB` is 1.85:1 — fails AA for body text.
  Use it for **accents only** (CTA fill, icon strokes, hero pop). Never for body or small text.
- [ ] Visible focus state on all interactive elements
- [ ] Reading age ~14 — short sentences, plain words, no jargon

## Audit of existing copy
- Headline options (CW1) — clear ✅
- Personas (CW2) — short sentences, conversational ✅
- CTA + microcopy (CW4) — friendly, plain ✅
