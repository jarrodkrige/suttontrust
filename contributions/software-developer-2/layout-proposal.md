# Layout proposal — index.html

Following PC1's section flow. Each `<section>` keeps its existing `<!-- ROLE: ... -->` anchor so the agent's routing still works.

## Structure

```html
<main>
  <section id="hero">
    <h1>{Copywriter 1's headline option A}</h1>
    <p class="lede">{Copywriter 1's tagline}</p>
    <a class="cta" href="#signup">Find your match</a>
    <img src="assets/hero.png" alt="Three diverse UK sixth-formers sharing a phone, laughing" />
  </section>

  <section id="who">
    <h2>Who is this for?</h2>
    <!-- Copywriter 2's three personas as cards -->
  </section>

  <section id="what">
    <h2>What you'll find here</h2>
    <!-- Copywriter 2's bullet list as a 4-tile grid, with Designer 2's icons -->
  </section>

  <section id="numbers">
    <h2>By the numbers</h2>
    <!-- Researcher 1's three stats -->
  </section>

  <section id="voices">
    <h2>Voices</h2>
    <!-- Copywriter 3's quotes as blockquote cards -->
  </section>

  <section id="signup">
    <h2>Join the waitlist</h2>
    <!-- Pitch Lead 1's CTA copy -->
  </section>
</main>
```

Mobile-first, single column under 768px. Two-column grid for personas + features above 768px.
