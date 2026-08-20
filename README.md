# Athletic Performance Intelligence

Static marketing site for MoodChanger's Athletic Performance Intelligence.

The entire site is a single self-contained `index.html` (all images, fonts, and scripts inlined) — no build step, no dependencies.

## Deploy on GitHub Pages

1. Create a new repository and push these files (`index.html`, `.nojekyll`, `README.md`).
2. In the repo: **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to *Deploy from a branch*, pick your branch (e.g. `main`) and the `/ (root)` folder.
4. Save. Your site publishes at `https://<user>.github.io/<repo>/` in a minute or two.

The `.nojekyll` file tells GitHub Pages to serve the file as-is.

## Local preview

Just open `index.html` in any browser — it works offline.
