# Yifei Cheng · Academic homepage

Static, bilingual academic homepage for GitHub Pages. No build step or runtime dependencies.

## Preview

Run `python -m http.server 8000` in this directory, then visit http://localhost:8000.

## Update content

- `index.html`: page structure and default English content.
- `app.js`: selected publications, Chinese translations, profile details, and citation interactions.
- `styles.css`: layout, responsive styles, reduced-motion and print support.
- `assets/`: favicon and future paper figures.

To replace a conceptual paper illustration, place a figure in `assets/` and add an `image: 'assets/your-figure.webp'` property to its object in `papers` in `app.js`. Images use `object-fit: contain` to preserve the full scientific figure. Current graphics are original conceptual diagrams, not experimental results.

## Deployment

Publish the repository `2654400439/2654400439.github.io` via GitHub Pages from `main`, root directory. `.nojekyll` enables plain static hosting. The default URL is https://2654400439.github.io/.

Only the website files should be committed. `.private-source/` contains private source materials and is intentionally ignored. No patents, undergraduate publications, internal projects, certificates, or private original documents are included in the website.

The profile and publication selection were confirmed with the owner on 2026-10-07. NDSS 2027 is displayed as accepted. Unavailable paper links are omitted rather than invented. The publication lists are intentionally selective.
