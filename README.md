# bruce-frontend

A static, read-only job board showing postings fetched daily from
Greenhouse, Lever, and Ashby job boards -- data pulled by
[bruce](https://github.com/thedtripp/bruce), a private job-search
automation project. This repo holds nothing but the published site:
plain HTML/CSS/JS, no build step, no backend.

`jobs.json` is regenerated and pushed here automatically once a day by
bruce's scheduled workflow. `index.html`/`style.css`/`app.js` are
mirrored from bruce's `docs/` folder whenever they change there.

Live site: served via GitHub Pages from this repo's `main` branch.
