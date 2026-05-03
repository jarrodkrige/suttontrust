# ♿ Accessibility Champion 2

You're the second a11y reviewer on the team. A11y-1 owns the on-page **promise** (the "Built with care" section + the official audit + the alt-text catalogue). **Your job is the second pair of eyes**: catch what they missed, and pair-review their work.

Two reviewers always finds more than one — that's the whole point.

## What lives in this folder
- `pair-review.md` — your sign-off (or pushback) on a11y-1's audit and alt-text
- `keyboard-nav-walkthrough.md` — your walk-through tabbing the site keyboard-only, what works, what doesn't
- `screen-reader-walkthrough.md` — what NVDA/VoiceOver would announce on each section
- `final-review.md` — your minute-45 sign-off note, alongside a11y-1's

## Coordinate with
- **Accessibility Champion 1** — read their `audit.md` first. Pair on the trickier issues.
- **Software Developers 1+2** — they ship the fixes
- **Visual Designers** — for alt text, contrast
- **Copywriters** — for plain language

## First 2 minutes
1. Sign in to copilot.microsoft.com.
2. Read a11y-1's `audit.md` (or ping them if it's not up yet).
3. Ask:
   > "I'm reviewing a colleague's a11y audit for a charity microsite. Give me 5 things people commonly miss in a quick a11y review — the ones that would still hurt a real user."
4. Use that as your checklist for the rest of the hour.

## Prompts that work
- *"What does NVDA announce when it hits this HTML: <paste>?"*
- *"Tab through this page mentally — where does focus get lost?"*
- *"Is this colour combination AA on regular text? AAA? <paste hex codes>"*
- *"Plain-language version of this paragraph for reading age 14: <paste>"*

## House rule
**Pair, don't gate.** Your second-eye review makes the team stronger, not slower. When you spot an issue, also propose the fix.
