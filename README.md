# Chronos Memos

A small publication of magazine-style HTML artefacts produced by [Chronos Capital](https://ccap.ai) for clients and partners — workshop memos, briefings, and the occasional deck.

Served as a static site via GitHub Pages. Each artefact is a self-contained HTML file; [`index.html`](index.html) is the landing page that lists them.

## Adding a new artefact

1. Drop the HTML file at the repo root with a slug-style name (e.g. `client-workshop-jun-2026.html`).
2. Add a new `<a class="card">` entry near the top of the `.grid` block in `index.html`.
3. Commit and push to `main`. GitHub Pages will redeploy automatically.
