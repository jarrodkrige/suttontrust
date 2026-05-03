# Software Developer 1

You don't write code directly to the site. Instead, you write **proposals** here — and the Factory Agent integrates them.

This is on purpose. It mirrors how senior developers actually work in an AI-native team: you direct the AI, you don't fight it.

## What lives in this folder
- `palette.md` — the colour and typography choices you propose for the site
- `layout-ideas.md` — your thoughts on hero structure, grid, page composition
- `component-snippets/` — HTML/CSS snippets you've prototyped that the Agent can lift
- `refactor-requests.md` — "the hero feels cramped, suggest the Agent widens it"

## What this turns into on the live site

Your job is to direct the Factory Agent to **reshape the SHELL** — the page structure, the styling system, and the components. The agent reads what you commit and updates `site/index.html` and `site/styles.css`. Concretely:

| You commit … | The agent does … |
| --- | --- |
| `palette.md` with hex codes | updates the CSS variables at the top of `site/styles.css` (page colours, type, spacing change in seconds) |
| `layout-ideas.md` describing hero proportions or grid | rewrites the relevant `<section>` markup to match (mobile-first, text/image ratio, etc.) |
| A snippet in `component-snippets/` | lifts the snippet into the page where it fits |
| `refactor-requests.md` saying "the team has 5 stat cards but the template only has 3 slots" | **adds slots** — the agent can grow the grid because you authorized it |

**You unlock the template's flexibility.** The starter `site/index.html` has a default shape; your proposals are how it bends. When a copywriter writes more body sections than the template has slots for, your refactor request says "make room." When a section has no contributor by ship-it, your request says "drop it." The structure-authority contract is in the `<!-- META: STRUCTURE AUTHORITY -->` block at the top of `<main>` in `site/index.html` — read it once.

## Coordinate with
- **Software Developer 2** — you take the *visual system* (palette, type, spacing). They take *page composition*.
- **Software Developers 3 & 4** (if present) — they own polish and wildcards; coordinate so you don't trip over each other
- **Visual Designer 1** — palette agreement
- **Project Coordinator** — for direction
- **Accessibility Champion** — they'll review your contrast choices

## First 2 minutes
1. Sign in to GitHub with your role-card account.
2. Open the repo. Find your folder.
3. Click **Add file → Create new file**. Name it `palette.md`.
4. Open another tab → **github.com/copilot**. Ask:
   > "Suggest a 4-colour palette for a charity microsite for first-generation UK university students. Warm, trustworthy, hopeful. Give hex codes and the reasoning for each."
5. Paste the result into `palette.md`. Commit. The Factory Agent will see it in seconds.

## Prompts that work
- *"Critique this hero layout idea: full-bleed image left, headline + CTA right. Mobile-friendly?"*
- *"Suggest a typography pairing for warm, editorial-feeling charity site. Display font + body font."*
- *"Write a CSS snippet for an accessible focus state that works on dark and light backgrounds."*
- *"What would make this site feel less corporate?"*

## House rule
**You're the AI's editor, not its typist.** Never accept the first answer. Iterate twice before committing.
