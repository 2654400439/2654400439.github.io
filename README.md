# Yifei Cheng · Academic homepage

Static, bilingual academic homepage for GitHub Pages. No build step or runtime dependencies.

## Preview

Run `python -m http.server 8000` in this directory, then visit http://localhost:8000.

## Update content

- `index.html`: page structure and default English content.
- `app.js`: Chinese translations, language switching, and citation interactions.
- `publications.js`: 13 published or accepted graduate papers, full author lists, paper links, and BibTeX. The three items marked `featured` appear with figures; all 13 also appear in the collapsible full list.
- `styles.css`: layout, responsive styles, reduced-motion and print support.
- `assets/`: favicon and future paper figures.

Paper figures live in `assets/papers/` and are referenced by `image` in `publications.js`. The three supplied figures were resized to 840 × 600 without cropping, as requested. The source image directory is excluded from deployment. Author positions are derived from each complete ordered author list: first authorship uses a tinted name; other positions use bold underlining. The full list defaults to collapsed, supports keyboard operation and retains its open state when switching languages.

Author lists were verified against the supplied thesis, PDF pages 135–136, on 2026-10-09. OPTICS lists Yifei Cheng as the third author. The thesis itself and its other contents are not published. WeChat links are owner-provided and labeled as article features; they are not endorsements.

## Deployment

Publish the repository `2654400439/2654400439.github.io` via GitHub Pages from `main`, root directory. `.nojekyll` enables plain static hosting. The default URL is https://2654400439.github.io/.

Only the website files should be committed. `.private-source/` contains private source materials and is intentionally ignored. No patents, undergraduate publications, internal projects, certificates, or private original documents are included in the website.

The profile and publication selection were confirmed with the owner on 2026-10-07. NDSS 2027 is displayed as accepted. Unavailable paper links are omitted rather than invented. The publication lists are intentionally selective.
