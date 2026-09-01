# Bayou Claims Group

Working repo for the Harris County excess-proceeds research business.

- `/docs` — the live website + dashboard (this is what GitHub Pages serves)
- `/01_Compliance` through `/05_Tracker` — business documents (see the top-level README for a
  guide to each folder)

## Turning on the live site (one-time, ~1 minute)
1. Go to this repo's **Settings → Pages**.
2. Under "Build and deployment," set Source to **Deploy from a branch**.
3. Branch: **main**, folder: **/docs**. Save.
4. GitHub will publish at `https://mrabousakho.github.io/bayou-claims-group/` (site) and
   `https://mrabousakho.github.io/bayou-claims-group/dashboard.html` (dashboard) within a minute
   or two.

## Keeping /docs and /06_Website, /07_Dashboard in sync
`/docs` is a copy for GitHub Pages' sake. If you (or I, in a future session) edit
`06_Website/index.html` or `07_Dashboard/dashboard.html`, copy the changes into `/docs` too
before pushing, or just ask me to do it next time.
