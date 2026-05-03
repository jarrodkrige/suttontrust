# Software Developer 4

You're the fourth dev on the team — extra capacity for the hour. You don't write code directly into the site; you write **proposals** and **snippets** here, and the Factory Agent integrates the strongest version.

SWD-1 owns the visual system, SWD-2 the page composition, SWD-3 polish. **Your job is the wildcards**: animation, interactivity, fun touches, the things that turn "fine" into "memorable" — *if* you can ship them in time. If you can't, fall back to helping with what's missing.

## What lives in this folder
- `wildcards.md` — the bold ideas (e.g. *"animate the stat figures counting up on scroll"*) with a snippet attached
- `component-snippets/` — small HTML/CSS/JS prototypes
- `gap-fills.md` — when you spot something the team is missing

## What this turns into on the live site

You're the wildcard on the SHELL. SWD-1/2/3 own the spine and polish; you add the memorable touch. Concretely:

| You commit … | The agent does … |
| --- | --- |
| `wildcards.md` with a snippet (e.g. animated stat counter, scroll fade-in, micro-interaction) | drops the snippet into the page — as a **new section in GROW ROOM** if it's bold enough, or woven into an existing section as polish |
| A `component-snippets/` prototype | lifts it in where it fits if it's stronger than what's there |
| `gap-fills.md` spotting something missing | the agent treats it like a refactor request |

**Demoable in 60 seconds wins.** If your animation needs explanation, simpler is better. Fall back to gap-fills when the spine still has rough edges — your wildcard only matters if the basics are in place.

## Coordinate with
- **Software Developers 1, 2, 3** — read everything they've committed before adding. Don't duplicate.
- **Visual Designers** — animation should match their tone, not fight it
- **Pitch Lead** — your interactivity should be *demoable* in 60 seconds

## First 2 minutes
1. Sign in to GitHub. Open the repo.
2. Read what SWD-1, SWD-2, SWD-3 have already committed. Find one gap.
3. Open **github.com/copilot**. Ask:
   > "I have 30 minutes to add one micro-interaction to a charity microsite that makes it feel polished and warm — not corporate. Suggest 3 options, ranked by ease vs. impact."
4. Pick one. Drop a snippet in `component-snippets/`.

## Prompts that work
- *"Write a CSS-only fade-up animation for a hero block on page load."*
- *"Suggest a subtle hover state for a CTA button — accessible (respects prefers-reduced-motion)."*
- *"What's one animation that would make a stat-card section feel alive without being annoying?"*

## House rule
**Ship one polished thing, not three half-finished ones.** Pick the one with the highest "wow per minute" and finish it.
