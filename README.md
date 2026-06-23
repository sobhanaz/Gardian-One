# Gardian One — نگاهبان

> **سامانهٔ هوشمند امنیت و نگهبانی** — «پیش به سوی امنیتی هوشمند»
> A comprehensive smart security & surveillance system proposal.

**🌐 Live site:** https://sobhanaz.github.io/Gardian-One/

---

## Overview

**نگاهبان (Negahban)** is an integrated **human + machine** security platform that augments
on-site guards with AI rather than replacing them. The proposal is delivered as a set of
interactive, print-ready (RTL / Persian) web documents.

Core capabilities of the proposed system:

- 🧠 **AI face recognition** — authorized/unauthorized detection with instant alerts
- 🛡️ **Guard-substitution detection** — behavioral analysis confirms the right person is on post
- 📍 **Indoor positioning (RTLS)** — live guard & asset tracking on a floor map
- 🚪 **Access control & zoning** — turnstiles, biometric terminals, role-based access
- 📑 **Auditable reporting** — every event logged with time, location and image
- 🏛️ **Full data sovereignty** — on-premise deployment; biometric data never leaves site

---

## Deliverables

All pages are live on GitHub Pages and cross-linked from the landing hub and the proposal's
table of contents.

| Document | File | Live |
|---|---|---|
| 🏠 Landing hub | `index.html` | [open](https://sobhanaz.github.io/Gardian-One/) |
| 📘 Full proposal (main) | `negahban-proposal.html` | [open](https://sobhanaz.github.io/Gardian-One/negahban-proposal.html) |
| 🏆 Value / business case (why us) | `negahban-why.html` | [open](https://sobhanaz.github.io/Gardian-One/negahban-why.html) |
| 📄 Executive one-pager | `negahban-onepager.html` | [open](https://sobhanaz.github.io/Gardian-One/negahban-onepager.html) |
| 🧮 Cost calculator (interactive) | `negahban-cost-calculator.html` | [open](https://sobhanaz.github.io/Gardian-One/negahban-cost-calculator.html) |
| 📈 ROI / break-even (interactive) | `negahban-roi.html` | [open](https://sobhanaz.github.io/Gardian-One/negahban-roi.html) |
| 📐 Technical specification | `negahban-technical-spec.html` | [open](https://sobhanaz.github.io/Gardian-One/negahban-technical-spec.html) |
| 🧩 Technology & development process | `negahban-tech-stack.html` | [open](https://sobhanaz.github.io/Gardian-One/negahban-tech-stack.html) |
| 📊 Financial/technical/business supplement | `negahban-supplement.html` | [open](https://sobhanaz.github.io/Gardian-One/negahban-supplement.html) |
| 📑 Pitch deck (PowerPoint) | `negahban-pitch.pptx` | [download](https://sobhanaz.github.io/Gardian-One/negahban-pitch.pptx) |
| 📝 Commercial kit (quote, payment plan, contract, SLA, warranty) | `negahban-commercial.html` | [open](https://sobhanaz.github.io/Gardian-One/negahban-commercial.html) |
| 🚀 Pilot / POC proposal | `negahban-pilot.html` | [open](https://sobhanaz.github.io/Gardian-One/negahban-pilot.html) |
| 🔏 Privacy, compliance & FAQ | `negahban-compliance.html` | [open](https://sobhanaz.github.io/Gardian-One/negahban-compliance.html) |
| 🏢 Company, team & portfolio (template) | `negahban-company.html` | [open](https://sobhanaz.github.io/Gardian-One/negahban-company.html) |

Also in the repo: `negahban-proposal.pdf` / `.docx` (exported proposal), `logo-preview.html`
(brand/logo models), `favicon.svg` (shared brand shield), and `content.js` (see below).

---

## Reference scenario

Figures throughout the documents are sized for a sample deployment:

- **11-floor** safety/occupational building
- **500** employees + **200** daily visitors
- ~**110** cameras, **18** biometric terminals, **4** turnstiles

## Cost at a glance

> Base assumption: **USD = ۱۶۰٬۰۰۰ تومان** (160,000 toman). Every number is editable live in the
> [cost calculator](https://sobhanaz.github.io/Gardian-One/negahban-cost-calculator.html).

| Item | Estimate |
|---|---|
| Per-building deployment (hardware + install + commissioning) | ≈ **۲۱٫۴** میلیارد تومان |
| Platform development (one-time, amortizable across sites) | ≈ **۷٫۷** میلیارد تومان |
| **Grand total** | ≈ **۲۹٫۱** میلیارد تومان |
| Year-1 operations | ≈ ۱٫۶۵ میلیارد تومان |

The development cost is one-time — a second building only needs the deployment portion.

---

## Proposed technology stack

| Layer | Technology |
|---|---|
| Backend services | **Go** |
| AI / computer vision | **Python** + ONNX Runtime (TensorRT/CUDA) |
| Mobile app | **Flutter** (Android/iOS) |
| Web dashboard | **React** + TypeScript |
| Database | **PostgreSQL** + pgvector + TimescaleDB |
| Cache / presence | **Redis** |
| Message bus | **NATS JetStream** |
| Video processing | **GStreamer** / FFmpeg |
| Orchestration | **Docker** + **Kubernetes** |
| Object storage | **MinIO** (S3, on-prem) |
| Observability | Prometheus + Grafana + Loki + OpenTelemetry |

> This stack describes the **product being proposed**. This repository itself is a static
> set of HTML documents (no build step) plus Chart.js loaded from a CDN.

---

## Repository structure

```
.
├── index.html                      # Landing hub
├── negahban-proposal.html          # Main proposal (TOC links to all pages)
├── negahban-why.html               # Value / business case
├── negahban-onepager.html          # Executive summary (print A4)
├── negahban-cost-calculator.html   # Interactive cost model
├── negahban-roi.html               # Interactive ROI model
├── negahban-technical-spec.html    # Technical spec & implementation guide
├── negahban-supplement.html        # Sensitivity, BMC, SWOT, tech, prereqs
├── logo-preview.html               # Brand / logo models
├── content.js                      # Single source of proposal content
├── favicon.svg                     # Shared brand shield favicon
├── negahban-pitch.pptx             # Pitch deck
├── negahban-proposal.pdf / .docx   # Exported proposal
└── .github/workflows/deploy.yml    # GitHub Pages deployment
```

`content.js` is the single source of the proposal's content/structure (typed blocks: `p`,
`table`, `cards`, `stats`, `features`, …) used to generate the proposal HTML and Word output.
It is **not** loaded at runtime by the published pages.

---

## Viewing & local development

No build or dependencies. Open `index.html` (the hub) or any page directly in a browser.
The interactive pages (cost calculator, ROI) persist edits in `localStorage` and have a
**Reset** button to restore defaults.

## Deployment

Every push to `main` is automatically published to GitHub Pages via
[`.github/workflows/deploy.yml`](.github/workflows/deploy.yml) (uploads the repo root as the
Pages artifact). Live at https://sobhanaz.github.io/Gardian-One/.

---

## Company

- **Company:** شرکت راهکار پرداز فن آوران هوشمند
- **Phone:** ۰۹۰۵۸۴۳۲۴۵۲
- **Website:** www.negahban.ir

## Copyright

© ۱۴۰۵ شرکت راهکار پرداز فن آوران هوشمند. تمام حقوق محفوظ است.
© 2026 Raahkaar Pardaaz Fanavar-e Hoshyaar. All rights reserved.

This is a proprietary proposal and intellectual property. Use and distribution are restricted
to agreed-upon purposes only.
