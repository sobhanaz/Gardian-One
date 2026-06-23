# Negahban — نگاهبان  
## Smart Security & Surveillance System

<div align="center">

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Status](https://img.shields.io/badge/status-Published-brightgreen.svg)
![Platform](https://img.shields.io/badge/platform-Web-blue.svg)
![Language](https://img.shields.io/badge/language-Persian%20%2B%20English-informational.svg)

**🌐 [Live Project](https://sobhanaz.github.io/Gardian-One/) | 📖 [Full Proposal](https://sobhanaz.github.io/Gardian-One/negahban-proposal.html) | 🎯 [Business Case](https://sobhanaz.github.io/Gardian-One/negahban-why.html)**

*The future of security is intelligent. Augmenting human expertise with AI-powered insights.*

</div>

---

## 📋 Overview

**Negahban** (نگاهبان — "The Guardian") is a comprehensive **human + machine security platform** that revolutionizes physical security by intelligently augmenting on-site security personnel rather than replacing them.

### The Problem
Traditional security relies on:
- ❌ Manual monitoring prone to human fatigue and error
- ❌ Reactive incident response
- ❌ Limited real-time tracking capabilities
- ❌ Inconsistent audit trails

### The Solution
Negahban combines cutting-edge AI with proven security practices to deliver:

- 🧠 **AI-Powered Face Recognition** — Real-time authorized/unauthorized detection with instant alerts
- 👤 **Guard Verification** — Behavioral analysis confirms the correct person is on post
- 📍 **Live Indoor Positioning (RTLS)** — Real-time guard & asset tracking on interactive floor maps
- 🚪 **Smart Access Control** — Biometric terminals, turnstiles, role-based access zones
- 📊 **Complete Audit Trail** — Every event logged with timestamp, location, and image
- 🏛️ **Data Sovereignty** — 100% on-premise deployment; biometric data never leaves your facility

---

## 🎯 Core Features

| Feature | Capability | Benefit |
|---------|-----------|---------|
| **Face Recognition** | AI-powered biometric identification | Instant threat detection |
| **Behavioral Analysis** | Guard shift verification & anomaly detection | Prevents impersonation |
| **Real-Time Tracking** | RTLS positioning with floor mapping | Optimized response times |
| **Access Control** | Multi-factor authentication & zone management | Comprehensive security |
| **Smart Reporting** | Automated event logging & analytics | Compliance & insights |
| **Integration Ready** | Turnstile, camera, and IoT device support | Scalable ecosystem |

---

## 📁 Project Structure

```
Negahban/
├── index.html                      # Landing hub
├── negahban-proposal.html          # Complete proposal (main document)
├── negahban-why.html               # Business case & value proposition
├── negahban-onepager.html          # Executive summary
├── negahban-cost-calculator.html   # Interactive cost modeling
├── negahban-roi.html               # ROI analysis & break-even
├── negahban-technical-spec.html    # Technical architecture
├── negahban-tech-stack.html        # Technology & development process
├── negahban-supplement.html        # Financial & technical deep-dive
├── negahban-commercial.html        # Pricing, contracts & SLAs
├── negahban-pilot.html             # POC proposal
├── negahban-compliance.html        # Privacy, compliance & FAQ
├── logo-preview.html               # Brand identity showcase
├── content.js                      # Shared content & utilities
├── favicon.svg                     # Project icon
├── negahban-proposal.pdf           # Exportable proposal (PDF)
├── negahban-proposal.docx          # Exportable proposal (Word)
└── README.md                       # This file
```

---

## 📚 Complete Document Suite

All documents are **live, interactive, and print-ready** with full RTL Persian support:

### Core Documents
| Document | Purpose | Format |
|----------|---------|--------|
| **[Full Proposal](https://sobhanaz.github.io/Gardian-One/negahban-proposal.html)** | Complete system design, architecture, and business model | Interactive HTML |
| **[Business Case](https://sobhanaz.github.io/Gardian-One/negahban-why.html)** | Why Negahban? Competitive advantages and ROI drivers | Interactive HTML |
| **[Executive Summary](https://sobhanaz.github.io/Gardian-One/negahban-onepager.html)** | One-page overview for decision makers | HTML |

### Interactive Tools
| Tool | Function | Use Case |
|------|----------|----------|
| **[Cost Calculator](https://sobhanaz.github.io/Gardian-One/negahban-cost-calculator.html)** | Real-time budget modeling | Proposal customization |
| **[ROI Analysis](https://sobhanaz.github.io/Gardian-One/negahban-roi.html)** | Break-even & payback modeling | Financial planning |

### Technical & Compliance
| Document | Details |
|----------|---------|
| **[Technical Spec](https://sobhanaz.github.io/Gardian-One/negahban-technical-spec.html)** | System architecture, APIs, integrations |
| **[Tech Stack](https://sobhanaz.github.io/Gardian-One/negahban-tech-stack.html)** | Technology choices, development process, roadmap |
| **[Compliance](https://sobhanaz.github.io/Gardian-One/negahban-compliance.html)** | Privacy policy, data protection, regulatory compliance |
| **[Financial Deep-Dive](https://sobhanaz.github.io/Gardian-One/negahban-supplement.html)** | Detailed cost breakdown, implementation timeline |

### Commercial & Implementation
| Document | Content |
|----------|---------|
| **[Commercial Kit](https://sobhanaz.github.io/Gardian-One/negahban-commercial.html)** | Pricing models, payment terms, service agreements, warranty |
| **[Pilot Program](https://sobhanaz.github.io/Gardian-One/negahban-pilot.html)** | POC proposal, timeline, success metrics |

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

## 🛠️ Technology Stack

### Proposed Product Stack
The Negahban platform itself is architected with enterprise-grade technologies:

**Backend & Processing**
- **Go** — High-performance backend services with concurrent request handling
- **Python** — AI/ML pipeline with OpenCV & TensorFlow for computer vision
- **ONNX Runtime** — Optimized inference with TensorRT acceleration for real-time processing

**Frontend & Client**
- **React + TypeScript** — Modern, type-safe web dashboard
- **Flutter** — Native iOS/Android mobile applications
- **HTML5/CSS3** — Standards-compliant web UI

**Data & Storage**
- **PostgreSQL** — Primary relational database with pgvector for embeddings
- **TimescaleDB** — Time-series optimization for event logs
- **MinIO** — S3-compatible on-premise object storage for images/video
- **Redis** — In-memory cache and real-time presence tracking

**Integration & Messaging**
- **NATS JetStream** — Reliable message bus for system events
- **GStreamer / FFmpeg** — Video processing and stream management

**Infrastructure & Observability**
- **Docker + Kubernetes** — Container orchestration and scaling
- **Prometheus + Grafana** — Metrics and visualization
- **Loki** — Distributed logging
- **OpenTelemetry** — End-to-end tracing

### This Repository
This repository is a **static HTML presentation** of the Negahban proposal:
- No build process or compilation required
- Pure HTML/CSS with Chart.js for interactive visualizations
- Responsive design with Persian (RTL) and English (LTR) support
- Automatic GitHub Pages deployment

---

## 🚀 Getting Started

### Viewing Online
Simply visit [https://sobhanaz.github.io/Gardian-One/](https://sobhanaz.github.io/Gardian-One/) to browse the live proposal.

### Local Development
1. **Clone the repository:**
   ```bash
   git clone https://github.com/sobhanaz/Gardian-One.git
   cd Gardian-One
   ```

2. **Open in browser:**
   - Start with `index.html` as the landing hub
   - Click through to any document (all links are internal)
   - No dependencies, build tools, or local server required

3. **Edit & test:**
   - Modify any HTML file
   - Refresh browser to see changes
   - Interactive calculators persist edits in browser `localStorage`
   - Click "Reset" buttons to restore defaults

### Cost & ROI Calculators
- **Cost Calculator:** Edit hardware quantities, labor rates, and timelines
- **ROI Model:** Adjust assumptions about savings and baseline costs
- All changes are saved locally; close and reopen to verify persistence

---

## 📊 Reference Deployment

The proposal includes figures for a reference scenario:

| Metric | Value |
|--------|-------|
| Building Type | Safety/Occupational Facility |
| Employees | 500 |
| Daily Visitors | 200 |
| Floors | 11 |
| IP Cameras | ~110 |
| Biometric Terminals | 18 |
| Turnstiles | 4 |

All cost and timeline estimates are **fully editable** in the interactive calculators.

---

## 💰 Estimated Investment

| Component | Est. Cost (USD) |
|-----------|-----------------|
| Hardware & Installation | $134M |
| Platform Development | $48M |
| Year-1 Operations | $10.3M |
| **Total (Single Site)** | **$182M** |

*Figures assume USD = 160,000 تومان. See [Cost Calculator](https://sobhanaz.github.io/Gardian-One/negahban-cost-calculator.html) for live modeling.*

Development cost is **one-time**; subsequent buildings require only deployment costs.

---

## 📄 License

This project is released under the **MIT License**.

```
MIT License

Copyright (c) 2026 Sobhan Azimzadeh

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
```

See [LICENSE](LICENSE) file for full terms.

---

## 🔗 Links & Resources

- **Live Site:** https://sobhanaz.github.io/Gardian-One/
- **Repository:** https://github.com/sobhanaz/Gardian-One
- **Author:** [Sobhan Azimzadeh](https://github.com/sobhanaz)
- **Contact:** [Telegram](https://t.me/sobhanazimzadeh) | [LinkedIn](https://www.linkedin.com/in/sobhan-azimzadeh-b956aa234)

---

## 🎯 Project Status

| Aspect | Status |
|--------|--------|
| Documentation | ✅ Complete |
| Web Deployment | ✅ Live on GitHub Pages |
| Interactive Tools | ✅ Functional |
| Persian Support | ✅ Full RTL Support |
| Mobile Responsive | ✅ Optimized |

---

<br/>
<br/>
<br/>

---

# نگاهبان — سامانهٔ هوشمند امنیت و نگهبانی

<div dir="rtl">

## 📋 مرور کلی

**نگاهبان** یک سامانهٔ جامع **انسان + ماشین** است که امنیت فیزیکی را با تقویت تیم نگهبانی در محل (نه جایگزینی) متحول می‌کند.

### مسئله
امنیت سنتی متکی بر:
- ❌ نظارت دستی که در معرض خستگی و اشتباه انسانی است
- ❌ پاسخ واکنشی به حوادث
- ❌ قابلیت ردیابی محدود در زمان واقعی
- ❌ ثبت‌سازی نامنسجم و غیرقابل‌اعتماد

### راهکار
نگاهبان تکنولوژی‌های روز جهان را با شیوه‌های اثبات‌شدهٔ امنیت ترکیب می‌کند:

- 🧠 **تشخیص چهره هوشمند** — تشخیص فوری مجاز/غیرمجاز با هشدار آنی
- 👤 **تأیید هویت نگهبان** — تحلیل رفتار برای اطمینان از حضور شخص صحیح
- 📍 **موقعیت‌یابی درونی زنده (RTLS)** — ردیابی نگهبان و دارایی‌ها
- 🚪 **کنترل دسترسی هوشمند** — احراز هویت چندسطحی و مناطق حفاظت‌شده
- 📊 **گزارش‌دهی ممیز** — ثبت تمام حوادث با زمان، مکان و تصویر
- 🏛️ **حاکمیت داده** — استقرار ۱۰۰٪ درون‌محلی؛ داده‌های بیومتریک هرگز خارج نمی‌شوند

---

## 🎯 قابلیت‌های اساسی

| قابلیت | توصیف | منفعت |
|--------|-------|-------|
| **تشخیص چهره** | شناسایی بیومتریک مبتنی بر هوش مصنوعی | تشخیص تهدید فوری |
| **تحلیل رفتار** | تأیید شیفت و تشخیص ناهنجاری | جلوگیری از جعل هویت |
| **ردیابی زنده** | موقعیت‌یابی RTLS با نقشهٔ کف | بهینه‌سازی زمان پاسخ |
| **کنترل دسترسی** | احراز هویت چندسطحی و مدیریت مناطق | امنیت جامع |
| **گزارش‌دهی هوشمند** | ثبت خودکار حوادث و تجزیه‌وتحلیل | انطباق و بصیرت |
| **آمادگی پذیریش** | پشتیبانی از دستگاه‌های دوربین و IoT | اکوسیستم مقیاس‌پذیر |

---

## 📁 ساختار سند

```
نگاهبان/
├── index.html                      # مرکز فرودگاهی
├── negahban-proposal.html          # پروپوزال کامل
├── negahban-why.html               # توجیه ارزش و موارد تجاری
├── negahban-onepager.html          # خلاصهٔ مدیریتی
├── negahban-cost-calculator.html   # ماشین‌حساب هزینه تعاملی
├── negahban-roi.html               # تحلیل ROI و بازگشت سرمایه
├── negahban-technical-spec.html    # مشخصات فنی معماری
├── negahban-tech-stack.html        # تکنولوژی‌ها و فرآیند توسعه
├── negahban-supplement.html        # تحلیل مالی و فنی گسترده
├── negahban-commercial.html        # مدل‌های قیمت‌گذاری و قرارداد
├── negahban-pilot.html             # پیشنهاد POC
├── negahban-compliance.html        # حریم خصوصی، انطباق و پرسش‌های رایج
├── logo-preview.html               # نمایشگاه هویت برند
├── content.js                      # محتوای اشتراک‌گذاری شده
├── favicon.svg                     # نماد پروژه
└── README.md                       # این فایل
```

---

## 📚 مجموعهٔ اسناد کامل

تمام اسناد **زنده، تعاملی و آماده‌ای برای چاپ** هستند:

### اسناد اصلی
| سند | هدف |
|------|------|
| **[پروپوزال کامل](https://sobhanaz.github.io/Gardian-One/negahban-proposal.html)** | طراحی کامل سیستم و مدل کسب‌وکار |
| **[موارد تجاری](https://sobhanaz.github.io/Gardian-One/negahban-why.html)** | توجیه ارزش و بازگشت سرمایه |
| **[خلاصهٔ یک‌صفحه‌ای](https://sobhanaz.github.io/Gardian-One/negahban-onepager.html)** | مرور کوتاه برای تصمیم‌گیران |

### ابزارهای تعاملی
| ابزار | کاربرد |
|------|--------|
| **[ماشین‌حساب هزینه](https://sobhanaz.github.io/Gardian-One/negahban-cost-calculator.html)** | مدل‌سازی بودجهٔ زنده |
| **[تحلیل ROI](https://sobhanaz.github.io/Gardian-One/negahban-roi.html)** | مدل‌سازی سربه‌سر |

### اسناد فنی و انطباق
| سند | جزئیات |
|------|---------|
| **[مشخصات فنی](https://sobhanaz.github.io/Gardian-One/negahban-technical-spec.html)** | معماری سیستم و یکپارچگی‌ها |
| **[تکنولوژی‌ها](https://sobhanaz.github.io/Gardian-One/negahban-tech-stack.html)** | انتخاب‌های فن‌آوری و فرآیند |
| **[انطباق](https://sobhanaz.github.io/Gardian-One/negahban-compliance.html)** | حریم خصوصی و حفاظت داده |
| **[تحلیل گسترده](https://sobhanaz.github.io/Gardian-One/negahban-supplement.html)** | تفکیک‌شدهٔ هزینه و زمان‌بندی |

### کیت تجاری و اجرا
| سند | محتوا |
|------|--------|
| **[کیت تجاری](https://sobhanaz.github.io/Gardian-One/negahban-commercial.html)** | مدل‌های قیمت‌گذاری و توافق‌نامه |
| **[برنامهٔ آزمایشی](https://sobhanaz.github.io/Gardian-One/negahban-pilot.html)** | پیشنهاد و معیارهای موفقیت POC |

---

## 🛠️ پشته‌ی فن‌آوری

### توصیف محصول پیشنهادی
سامانهٔ نگاهبان با تکنولوژی‌های سطح سازمانی طراحی شده است:

**خدمات و پردازش‌**
- **Go** — خدمات backend با کارایی بالا
- **Python** — خط‌لوله هوش مصنوعی با OpenCV
- **ONNX Runtime** — استنتاج بهینه‌شدهٔ TensorRT

**رابط و کلاینت**
- **React + TypeScript** — داشبوردِ وب مدرن
- **Flutter** — برنامه‌های iOS/Android بومی
- **HTML5/CSS3** — رابط کاربری استاندارد

**داده و ذخیره‌سازی**
- **PostgreSQL** — پایگاه داده رابطه‌ای اصلی
- **TimescaleDB** — بهینه‌سازی سری زمانی
- **MinIO** — ذخیره‌سازی شی سازگار با S3
- **Redis** — حافظهٔ موقت و ردیابی حضور

**یکپارچگی و پیام‌رسانی**
- **NATS JetStream** — ریل پیام قابل‌اطمینان
- **GStreamer / FFmpeg** — پردازش ویدیو

**زیرساخت و رصد**
- **Docker + Kubernetes** — هماهنگ‌سازی و مقیاس‌بندی
- **Prometheus + Grafana** — متریک و تجسم
- **Loki** — ورود توزیع‌شدهٔ
- **OpenTelemetry** — ردیابی جامع

---

## 🚀 شروع سریع

### مشاهدهٔ آنلاین
به [https://sobhanaz.github.io/Gardian-One/](https://sobhanaz.github.io/Gardian-One/) مراجعه کنید.

### توسعهٔ محلی
```bash
git clone https://github.com/sobhanaz/Gardian-One.git
cd Gardian-One
# هیچ وابستگی نمی‌خواهد — فایل‌های HTML را مستقیماً باز کنید
```

---

## 📊 استقرار مرجع

| معیار | مقدار |
|--------|-------|
| نوع ساختمان | تاسیسات ایمنی و شغلی |
| کارمندان | 500 |
| بازدیدکنندگان روزانه | 200 |
| طبقات | 11 |
| دوربین | ~110 |
| ترمینال بیومتریک | 18 |
| دوار ورودی | 4 |

---

## 📄 مجوز

این پروژه تحت **مجوز MIT** منتشر می‌شود.

© 2026 سهان عظیم‌زاده — Sobhan Azimzadeh

تمام حقوق برای استفاده، تغییر، و توزیع مجدد محفوظ است.

برای شرایط کامل به فایل [LICENSE](LICENSE) مراجعه کنید.

---

## 🔗 پیوندها و منابع

- **سایت زنده:** https://sobhanaz.github.io/Gardian-One/
- **مخزن:** https://github.com/sobhanaz/Gardian-One
- **نویسنده:** [سهان عظیم‌زاده](https://github.com/sobhanaz)
- **ارتباط:** [تلگرام](https://t.me/sobhanazimzadeh) | [لینکدین](https://www.linkedin.com/in/sobhan-azimzadeh-b956aa234)

---

## 🎯 وضعیت پروژه

| جنبه | وضعیت |
|------|--------|
| مستندات | ✅ تکمیل |
| استقرار وب | ✅ زنده در GitHub Pages |
| ابزارهای تعاملی | ✅ عملیاتی |
| پشتیبانی فارسی | ✅ پشتیبانی کامل RTL |
| سازگاری موبایل | ✅ بهینه‌شدهٔ |

---

</div>

<br/>

**Built with ❤️ by [Sobhan Azimzadeh](https://sobhanaz.github.io/Gardian-One/) | CEO @ [TECSO](https://tecso.team/)**
