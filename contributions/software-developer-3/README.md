# Software Developer 3

You're a third pair of hands on the page. You don't write code directly into the site — you write **proposals** and **snippets** here, and the Factory Agent integrates the strongest version.

Software Developers 1 and 2 own the primary system: SWD-1 the visual system (palette, type, spacing), SWD-2 the page composition. **Your job is the polish layer**: layout fixes, micro-interactions, component snippets the others might not have time for. Your work competes with theirs for inclusion — pick something specific and ship a sharper version.

## What lives in this folder
- `refactor-requests.md` — *"the hero feels cramped, suggest the Agent widens it"*
- `component-snippets/` — small HTML/CSS bits you've prototyped (e.g. a focus state, a loading spinner, a footer)
- `polish-pass.md` — list of small improvements you'd make if you had more time

## What this turns into on the live site

You're the polish layer on the SHELL. SWD-1 and SWD-2 own the spine; you sharpen specific parts of `site/index.html` and `site/styles.css`. Concretely:

| You commit … | The agent does … |
| --- | --- |
| `refactor-requests.md` like "the hero feels cramped, widen the text column" | applies that change to the hero markup or CSS |
| A snippet in `component-snippets/` | lifts the snippet into the page if it's sharper than what's there |
| `polish-pass.md` listing small CSS improvements | applies them in subsequent consolidation passes |

**Your work competes with SWD-1 and SWD-2's** for inclusion. Read what they've committed first; pick something specific; ship a sharper version. The agent picks the strongest contribution per spot.

## Coordinate with
- **Software Developers 1 and 2** — read what they've committed first. Then choose what to add.
- **Visual Designers** — for spacing, ratios
- **Accessibility Champions** — for focus states, motion preferences

## First 2 minutes
1. Sign in to GitHub with your role-card account.
2. Read `software-developer-1/palette.md` and `software-developer-2/page-structure.md` once they appear.
3. Open **github.com/copilot**. Ask:
   > "Critique this site structure for a charity microsite for first-gen UK uni students. What's the strongest small improvement I could make in the next 30 minutes?"
4. Pick one improvement. Drop it as a `refactor-requests.md` entry.

## Prompts that work
- *"Suggest 3 small CSS improvements for a hero with text on the left and image on the right — the kind that make it feel polished, not corporate."*
- *"What's a single accessible improvement I could make to this card grid? Show me the CSS."*
- *"Compare these two layouts. Which feels warmer for a charity audience?"*

## House rule
**You're the third pair of eyes.** SWD-1 and SWD-2 own the spine. You make it sing.
