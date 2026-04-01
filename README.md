# ew13r5 — Full-Stack Python Developer

I build automation systems that run 24/7 without manual intervention.

API integrations, data pipelines, real-time dashboards, background task automation.
Every project ships with Docker Compose, automated tests, and production-grade error handling.

---

## Stack

Python, FastAPI, React, TypeScript, PostgreSQL, Redis, Celery, Docker,
Playwright, Telegram Bot API, Shopify API, Meta Marketing API, Google Sheets API

---

## Projects

### [Ad Budget Guard](https://github.com/ew13r5/ad-budget-guard)

Real-time budget protection for Meta Ads. Monitors spend every 5 minutes, auto-pauses campaigns on threshold breach, detects anomalies (3 sigma). 4 rule types, Telegram and email alerts, PDF reports, full Meta OAuth 2.0 flow with token lifecycle management.

FastAPI, React, Celery, PostgreSQL, Redis, Docker — 6 services, 9 scheduled tasks, 20+ endpoints, 10 pages

---

### [Lead Gen Scraper](https://github.com/ew13r5/lead-gen-scraper)

Config-driven B2B lead generation with 4-stage data pipeline. 5 pre-built sources via YAML config — adding a new source takes 15 minutes, zero code changes. Pipeline: scrape, clean, validate, deduplicate (fuzzy matching via rapidfuzz), enrich, export.

FastAPI, React, Playwright, Celery, AG Grid, Docker — 5 services, 253 tests, 17 endpoints

---

### [Shopify Order Manager](https://github.com/ew13r5/shopify-order-manager)

E-commerce dashboard with per-item payout tracking. Calculates net revenue per product after fees, discounts, and refunds. SKU Unicode cleaning pipeline (NFKC + zero-width char stripping). Auto Google Sheets sync — 3 tabs, batch updates, dedup protection. Demo mode with 1,247 orders.

FastAPI, React, Celery, Shopify API, PostgreSQL, Docker

---

### [Auto Poster](https://github.com/ew13r5/multiplatform-auto-poster)

Multi-platform auto-posting system. Telegram (live), Twitter/X and Facebook (implemented). Week calendar scheduler, drag-and-drop queue, Celery Beat publishing every 60 seconds. Retry with exponential backoff, error spike protection, engagement tracking at 1h/4h/24h. Fernet token encryption with key rotation.

FastAPI, React 19, Celery, MinIO, Docker — 7 services, 95 tests

---

## Numbers

- 4 production-ready projects, open source
- 500+ automated tests combined
- 60+ API endpoints across projects
- 25+ Docker services total
- 18+ Celery scheduled tasks running 24/7

---

## Contact
- email: rostislavguseynov@gmail.com
- telegramm: @ew13r5
