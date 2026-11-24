# silicamentis.eu

Source for the SilicaMentis Strategy website: static HTML and assets, no build step.

## Files
- `index.html` – home page
- `privacy.html` – privacy notice
- `assets/` – images, logos and other site files
- Netlify settings are in `netlify.toml` at the repo root (base directory `website`, response headers)

## How changes go live
1. Until Netlify is linked to this repo, the site is deployed by drag-and-drop of this folder in Netlify. Always drag from this folder, so the repo matches what is live.
2. Once linked: changes are made on a branch, Netlify builds a deploy preview, and Kieran reviews and merges to `main`. Merging to `main` publishes to silicamentis.eu.

## Rules
- Nothing secret goes in this repo (no keys, passwords or tokens). The `.gitignore` blocks the common ones.
- Pages under `/admin/` are never linked from the site and are kept out of search engines (see the root `netlify.toml`).

Owner: Kieran Hanrahan, kieran@silicamentis.eu
