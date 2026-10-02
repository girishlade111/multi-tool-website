# Multi-Tool Website — All-in-One Calculator Hub

A single-file, client-side web app bundling a collection of handy calculators and utility tools into one landing hub. No build step, no server, no data leaves the browser — just open and use.

## Included tools

- **SGPA / CGPA calculators** (including VIT & SRM variants)
- **7th CPC Pay Calculator** — Indian government pay-scale math
- **LIC Surrender Value Calculator** — policy surrender estimates
- **TNEB Bill Calculator** — Tamil Nadu electricity-bill estimates
- **MS Plate Weight Calculator** — mild-steel plate weight from dimensions
- **Lo Shu Grid Calculator** — numerology grid
- **Video Transcript Generator**

## Features

- Single self-contained HTML file (CSS + JS inlined) — works offline once loaded
- Responsive card-grid layout with light/dark styling
- Instant results, no sign-up, no tracking
- Zero dependencies, zero network calls

## Quick start

No installation or build required:

```bash
# Option 1: open directly in a browser
open multi-tool-website.html

# Option 2 (or index.html for GitHub Pages): serve locally
npx serve .
# then visit http://localhost:3000
```

## Project structure

```
multi-tool-website/
├── index.html             # Entry page (GitHub Pages)
├── multi-tool-website.html # The app (single self-contained file)
├── README.md
└── LICENSE
```

## Tech stack

- HTML5 + CSS3 (custom properties for theming)
- Vanilla JavaScript (no frameworks, no dependencies)

## Deploy notes

Deployed as a static site via **GitHub Pages** (`index.html` at the repo root). Any static host works — Netlify, Cloudflare Pages, Vercel, or `npx serve`.

## License

See [LICENSE](./LICENSE).

---

Built by [Girish Lade](https://ladestack.in) — part of the [LadeStack](https://ladestack.in) free-tools collection.
