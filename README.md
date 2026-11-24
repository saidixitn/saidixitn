# Sai Dixit Naidu

> **Lead Data Analyst & Systems Automation Engineer**  
> *Working with data, building with Python, automating the rest.*  
> Visakhapatnam, India · [saidixit.vercel.app](https://saidixit.vercel.app/) · [Works](https://saidixit.vercel.app/works/) · [Writing](https://saidixit.vercel.app/blog/) · [LinkedIn](https://www.linkedin.com/in/sai-dixit) · [Twitter / X](https://x.com/SaiDixitNaidu) · [saidixitn@gmail.com](mailto:saidixitn@gmail.com)

---

### Overview

I find where information gets stuck, then build what gets it moving.

I work across high-volume data querying, search engine indexing architecture, and deterministic background automation. Most of my time is spent inside job market datasets, Google for Jobs schema structures, BigQuery data pipelines, and writing Python services that eliminate manual verification.

```
01 / Spot the pattern  — Locate where data gets stuck or why a check is done twice.
02 / Build the fix      — Write the script, repair the schema, or design the tool.
03 / Automate it        — If it runs on a schedule, code should handle it in the background.
04 / Keep it calm       — No bloat. Software that stays out of your way and does its job.
```

---

### Selected Systems & Repositories

#### [Python](https://github.com/saidixitn/Python)
`Data Operations` · `BigQuery Sync` · `MongoDB Pipelines` · `PM2 Daemons`

A production operations fleet of PM2-scheduled Python services managing automated data extraction, warehouse ingestion, and live reporting.

- **BigQuery Synchronization**: Streams operational job telemetry and partner records into Google BigQuery with automated schema reconciliation.
- **Feed & Proxy Services**: Headless data export pipelines and proxy scrapers running continuous sanitation on high-volume feeds.
- **Revenue Reconciliation**: Automated data pipelines correlating domain traffic, conversion attribution, and Google Sheets ledger synchronization.
- **Resilient Execution**: Managed under PM2 process orchestration with automated recovery and zero hardcoded secrets.

---

#### [antigravity-nodejs](https://github.com/saidixitn/antigravity-nodejs)
`Backend Engine` · `Dual-Mode Mongo` · `Cursor Streaming` · `REST API`

A modular, high-throughput Node.js backend engine designed for multi-tenant data pipelines and search engine structured data validation without heavy ORM overhead.

- **Dual-Mode MongoDB Layer**: Small aggregation and local staging tasks default to local instances, while remote production clusters are resolved dynamically via credential discovery.
- **Optimized Ingestion**: Leverages compound index prefixes and cursor streaming to eliminate full collection scans on large datasets.
- **REST Microservice**: Express-based endpoint layer with interactive HTTP test notebooks for one-click verification.

---

#### [Job-Posting-Alerts](https://github.com/saidixitn/Job-Posting-Alerts)
`Differential Monitoring` · `Google for Jobs` · `Schema.org` · `Webhook Telemetry`

Autonomous telemetry system designed around the rule: *alert on change, not on state*. Evaluates millions of structured listings to detect schema anomalies and crawl drops before listings disappear from Google for Jobs.

- **Diff-Based Detection**: Compares successive feed states rather than checking static thresholds, eliminating alert fatigue.
- **Schema Validation**: Validates JSON-LD and microdata syntax against strict Google Search Console guidelines.
- **Operational Dispatch**: Instant webhook notifications and Telegram alerts with actionable context.

---

#### [jobinsights](https://github.com/saidixitn/jobinsights)
`Privacy Telemetry` · `Sub-2KB Footprint` · `Core Web Vitals` · `Attribution`

A privacy-friendly web analytics and revenue attribution engine built as a lightweight, zero-cookie alternative to bloated tracking suites.

- **Cookie-Free Architecture**: Full compliance with privacy regulations without requiring intrusive consent banners.
- **Sub-2KB Telemetry Ingest**: Ultra-lightweight telemetry collection with zero penalty on Lighthouse performance or Core Web Vitals.
- **Revenue Attribution**: Connects user acquisition funnels directly to downstream payment webhooks and session events.

---

#### [daybook](https://github.com/saidixitn/daybook)
`Developer Ledger` · `Local-First` · `Execution Telemetry` · `Zero-Backend`

A focused, distraction-free logging interface and operational ledger designed to track task lifecycles, script run histories, and daily sprint progress without server or database dependencies.

- **Zero-Backend Architecture**: Runs entirely in the browser with fast, local persistence.
- **Execution Tracking**: Clean timeline view separating active development from historical run logs.
- **Minimal Footprint**: Pure semantic web stack with zero framework overhead.

---

#### [Automation](https://github.com/saidixitn/Automation)
`Headless Fleet` · `Scheduled Workers` · `Data Sanitation` · `Linux Daemons`

A modular collection of production automation scripts and background daemons handling unattended daily workloads.

- **Headless Extraction**: Scrapers and API clients built for resilient long-running cron jobs.
- **Automated Reporting**: Generates and dispatches daily operational reports directly via SMTP and webhooks.
- **Deterministic Handlers**: Script execution with clean exit states, detailed logging, and safe fallback handling.

---

#### [google-paa-scraper](https://github.com/saidixitn/google-paa-scraper)
`Search Intelligence` · `SERP Crawler` · `NLP Trees` · `Python`

Automated search extraction crawler targeting Google "People Also Ask" dynamic question graphs. Traverses recursive question hierarchies to map search intent and semantic relationships for technical SEO research.

---

### Technical Manifest

```yaml
data_infrastructure:
  querying_storage:    [Python, SQL, Google BigQuery, MongoDB, Pandas, NumPy]
  search_intelligence: [Google for Jobs, Google Search Console API, Schema.org, Structured Data, Technical SEO]
  pipelines_etl:       [BigQuery Sync, Feed Sanitation, Schema Anomaly Detection, State Diffs]

automation_orchestration:
  runtime_daemons:     [PM2, Cron, Linux Daemons, Docker, Headless Scrapers]
  monitoring_alerts:   [Change-Detection Webhooks, Telegram Bots, SMTP Alerting, Feed Health Checks]
  integrations:        [REST APIs, Google Sheets API, WebSockets, Vercel Edge Runtime]

artificial_intelligence:
  models_evaluation:   [LLMs, OpenAI API, Ollama, Prompt Architecture, Output Evaluation]
  credentials:         ["AI Foundations" by OpenAI Academy (ID: c92ba288-81e6-4a41-ba20-f11055010ed8)]

web_systems_tooling:
  backend_runtimes:    [Node.js, Express, Python (FastAPI / Flask)]
  frontend_philosophy: [Vanilla JavaScript, Semantic HTML5, Pure CSS Motion, Zero-Framework UI]
```

---

### Writing & Notes

- [Alerts people trust: what I learned building a monitoring bot](https://saidixit.vercel.app/blog/alerts-people-trust)  
  *Why alerting on change matters more than alerting on state, and how to stop alert fatigue.*

- [Why job postings drop out of Google for Jobs](https://saidixit.vercel.app/blog/why-job-postings-drop-out-of-google-for-jobs)  
  *Common schema failures, crawl timing issues, and indexing mechanics observed across millions of jobs.*

- [Daybook: building without a backend](https://saidixit.vercel.app/blog/daybook-no-backend)  
  *How to build useful developer tools that run entirely in the browser without server maintenance.*

---

### Verified Online Profiles

- **Website**: [saidixit.vercel.app](https://saidixit.vercel.app/)
- **Selected Works**: [saidixit.vercel.app/works](https://saidixit.vercel.app/works/)
- **Experience**: [saidixit.vercel.app/experience](https://saidixit.vercel.app/experience)
- **LinkedIn**: [linkedin.com/in/sai-dixit](https://www.linkedin.com/in/sai-dixit)
- **Twitter / X**: [@SaiDixitNaidu](https://x.com/SaiDixitNaidu)
- **Direct Contact**: [saidixitn@gmail.com](mailto:saidixitn@gmail.com)

---

<div align="center">
  <sub>Sai Dixit Naidu · Visakhapatnam, India · <a href="https://saidixit.vercel.app/">saidixit.vercel.app</a></sub>
</div>
