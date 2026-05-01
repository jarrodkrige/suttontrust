# Software Developer 2

You don't write code directly to the site. Instead, you write **proposals** here — and the Factory Agent integrates them.

This mirrors how senior developers work in an AI-native team: you direct the AI, you don't fight it.

## What lives in this folder
- `page-structure.md` — your proposal for how many pages, what's on each
- `section-ideas.md` — specific sections you think the hero/landing should have
- `component-snippets/` — HTML/CSS snippets you've prototyped
- `pull-requests.md` — "pull copy from copywriter-1 into the hero" — you can guide the Agent

## Coordinate with
- **Software Developer 1** — they take the *visual system*. You take *page composition*.
- **Project Coordinator** — site structure
- **Copywriters** — flag when you're ready for their copy
- **Visual Designers** — flag when you're ready for their images

## First 2 minutes
1. Sign in to GitHub with your role-card account. Open the repo.
2. Find your folder. **Add file → Create new file** → `page-structure.md`.
3. Open **github.com/copilot** in another tab. Ask:
   > "Propose a single-page-vs-multi-page structure for a charity microsite for first-gen UK uni students. Audience is sixth-formers. Recommend one approach with reasoning."
4. Paste, commit. The Factory Agent uses this as a north star.

## Prompts that work
- *"Outline 4 sections for the FirstGen landing page. For each: heading, what content goes there, what call-to-action."*
- *"What's the right hierarchy of headings on a 1-page charity site?"*
- *"Write a snippet that pulls in the headline from a markdown file at ../copywriter-1/headlines.md and uses it as the H1."*
- *"Should we add a second page? What would it cover?"*

## House rule
**You're directing, not coding alone.** Iterate with the AI until the proposal is sharp, then commit.
