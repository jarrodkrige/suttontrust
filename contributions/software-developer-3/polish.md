# Polish layer

Drop these into `site/styles.css`. They're additive — won't conflict with the base sheet.

```css
:focus-visible {
  outline: 3px solid var(--colour-trust);
  outline-offset: 2px;
  border-radius: 4px;
}

.cta {
  transition: background 200ms ease, transform 120ms ease;
}
.cta:hover { transform: translateY(-1px); }
.cta:active { transform: translateY(0); }

@media (prefers-reduced-motion: reduce) {
  * { transition: none !important; animation: none !important; }
}
```

Rationale: focus-visible is a real accessibility win without adding outlines for mouse users. Reduced-motion respects the system pref.
