# DiabeticModels

**Open diabetes models — shown and hosted. Every build proves its math.** → [diabeticmodels.com](https://diabeticmodels.com)

The model-build-and-host wing of [OpenDiabetic](https://opendiabetic.com). Every model ships with
its **cited corpus**, its **recipe**, its **beat-base evaluation**, and its **receipt**. A model is
not "proven" until it beats its base on a held-out test — and that math is published, win or lose.

> Honesty rule: no weights + no beat-base receipt → labeled **in build**, never offered for download.

Models flow **down** to people's own devices; private health data never flows up. The facts the
models learn are published and cited at [DiabeticTruth](https://diabetictruth.org).

## Structure (static site — no build step)
| File | Purpose |
|---|---|
| `index.html` | Home + the build board (honest status) + "how we prove a model" |
| `llms.txt` · `robots.txt` · `sitemap.xml` | GEO / AI-crawler scaffolding |
| `style.css` | Shared styles |

## Deploy
Cloudflare Pages, connected to this repo (build command: none · output dir: `/`). Domain: `diabeticmodels.com`.

## Current build
- **LocalDiabetic Foot-Care Specialist** — IN BUILD. Cited corpus staged (NIDDK + IWGDF 2023); not yet cooked.
