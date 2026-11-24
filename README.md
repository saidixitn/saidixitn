<div align="center">

# Sai Dixit Naidu

**Lead Data Analyst & Systems Automation Engineer**  
*Working with data, building with Python, automating the rest.*

[Portfolio](https://saidixit.vercel.app/) &nbsp;·&nbsp; [Works](https://saidixit.vercel.app/works/) &nbsp;·&nbsp; [Experience](https://saidixit.vercel.app/experience) &nbsp;·&nbsp; [Writing](https://saidixit.vercel.app/blog/) &nbsp;·&nbsp; [LinkedIn](https://www.linkedin.com/in/sai-dixit) &nbsp;·&nbsp; [Twitter / X](https://x.com/SaiDixitNaidu) &nbsp;·&nbsp; [saidixitn@gmail.com](mailto:saidixitn@gmail.com)

<br />

<table>
  <tr>
    <td align="center" width="25%">
      <strong>Millions</strong><br />
      <sub>Listings Indexed</sub>
    </td>
    <td align="center" width="25%">
      <strong>&lt; 2 KB</strong><br />
      <sub>Telemetry Footprint</sub>
    </td>
    <td align="center" width="25%">
      <strong>Zero</strong><br />
      <sub>Third-Party Cookies</sub>
    </td>
    <td align="center" width="25%">
      <strong>24 / 7</strong><br />
      <sub>Autonomous Daemons</sub>
    </td>
  </tr>
</table>

</div>

---

### About

I find where information gets stuck, then build what gets it moving.

My work centers on high-volume data querying, search engine indexing architecture, and deterministic background automation. Most of my time is spent inside job market datasets, Google for Jobs schema structures, BigQuery data pipelines, and writing Python services that eliminate manual verification.

```
01 / Spot the pattern  — Locate where data gets stuck or why a check is done twice.
02 / Build the fix      — Write the script, repair the schema, or design the tool.
03 / Automate it        — If it runs on a schedule, code should handle it in the background.
04 / Keep it calm       — No bloat. Software that stays out of your way and does its job.
```

---

### Core Systems & Repositories

<table>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/saidixitn/Python">Python</a></h3>
      <p><strong>Production Data Operations, BigQuery Sync &amp; PM2 Fleet</strong></p>
      <p>Continuous pipeline orchestrator streaming live job telemetry into Google BigQuery, running proxy feed extraction, and managing automated revenue reconciliation.</p>
      <p>
        <kbd>Python</kbd> <kbd>BigQuery</kbd> <kbd>MongoDB</kbd> <kbd>PM2</kbd> <kbd>Sheets API</kbd>
      </p>
      <details>
        <summary><b>Key Subsystems &amp; Implementation</b></summary>
        <ul>
          <li><code>Stats/bigquery_sync.py</code> — High-throughput warehouse ETL streaming operational records into BigQuery.</li>
          <li><code>Proxy/</code> — Headless proxy scrapers and automated feed export handlers.</li>
          <li><code>Revenue/</code> — Automated revenue attribution and Google Sheets ledger synchronization.</li>
          <li>Managed under PM2 process trees with automatic restarts and zero hardcoded credentials.</li>
        </ul>
      </details>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/saidixitn/antigravity-nodejs">antigravity-nodejs</a></h3>
      <p><strong>Multi-Tenant MongoDB Engine &amp; REST Microservice</strong></p>
      <p>A modular Node.js backend engine designed for high-volume data ingestion, complex aggregation pipelines, and search engine structured data validation without heavy ORM overhead.</p>
      <p>
        <kbd>Node.js</kbd> <kbd>MongoDB</kbd> <kbd>Express</kbd> <kbd>REST API</kbd>
      </p>
      <details>
        <summary><b>Key Subsystems &amp; Implementation</b></summary>
        <ul>
          <li><code>core/mongo.js</code> — Dual-mode MongoDB layer (defaults temporary staging tasks to local instances; dynamically resolves remote clusters).</li>
          <li>Compound index prefixes and cursor streaming to eliminate full collection scans.</li>
          <li><code>api.js</code> &amp; <code>api.http</code> — Fast REST endpoints with interactive 1-click verification notebooks.</li>
        </ul>
      </details>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/saidixitn/Job-Posting-Alerts">Job-Posting-Alerts</a></h3>
      <p><strong>Differential Search Engine Indexing Telemetry</strong></p>
      <p>Autonomous monitoring engine built on the principle: <em>alert on change, not on state</em>. Compares historical run diffs across structured listings to catch Google for Jobs schema drops before listings vanish from search.</p>
      <p>
        <kbd>Python</kbd> <kbd>Google for Jobs</kbd> <kbd>Schema.org</kbd> <kbd>Webhooks</kbd>
      </p>
      <details>
        <summary><b>Key Subsystems &amp; Implementation</b></summary>
        <ul>
          <li>Diff-based anomaly detection across successive partner feed ingestions.</li>
          <li>Structured data validation against Google Search Console indexing standards.</li>
          <li>Automated Telegram and webhook dispatch with actionable issue context.</li>
        </ul>
      </details>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/saidixitn/jobinsights">jobinsights</a></h3>
      <p><strong>Privacy-First Web Telemetry Platform</strong></p>
      <p>A lightweight, cookie-free web telemetry and revenue attribution engine built as an alternative to bloated analytics trackers. Designed for high accuracy with zero user tracking cookies.</p>
      <p>
        <kbd>JavaScript</kbd> <kbd>Edge Runtime</kbd> <kbd>Web Vitals</kbd> <kbd>Attribution</kbd>
      </p>
      <details>
        <summary><b>Key Subsystems &amp; Implementation</b></summary>
        <ul>
          <li>100% cookie-free by default; GDPR and privacy-compliant without cookie banners.</li>
          <li>Sub-2KB ingestion footprint with zero impact on Core Web Vitals or page speed.</li>
          <li>Attribution pipelines linking visitor funnels to payment webhooks.</li>
        </ul>
      </details>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/saidixitn/daybook">daybook</a></h3>
      <p><strong>Zero-Backend Developer Ledger &amp; Task Tracker</strong></p>
      <p>A focused, local-first execution tracker and operational ledger built to capture script run histories, sprint notes, and task states with zero database dependencies.</p>
      <p>
        <kbd>JavaScript</kbd> <kbd>Local-First</kbd> <kbd>Semantic Web</kbd> <kbd>Zero-Backend</kbd>
      </p>
      <details>
        <summary><b>Key Subsystems &amp; Implementation</b></summary>
        <ul>
          <li>Fast client-side persistence with instant launch and zero setup.</li>
          <li>Clean distraction-free timeline interface.</li>
          <li>Zero external server or database overhead.</li>
        </ul>
      </details>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/saidixitn/Automation">Automation</a></h3>
      <p><strong>Headless Script Fleet &amp; Scheduled Cloud Daemons</strong></p>
      <p>A modular collection of production automation workers, data cleaners, and scheduled cron jobs running unattended on Linux servers.</p>
      <p>
        <kbd>Python</kbd> <kbd>Cron</kbd> <kbd>Linux Daemons</kbd> <kbd>SMTP Alerting</kbd>
      </p>
      <details>
        <summary><b>Key Subsystems &amp; Implementation</b></summary>
        <ul>
          <li>Automated data extraction and partner feed sanitation scripts.</li>
          <li>Daily operational reporting pipelines with automated email delivery.</li>
          <li>Deterministic error handling with clean system exit codes.</li>
        </ul>
      </details>
    </td>
  </tr>
</table>

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

### Selected Technical Writing

In-depth post-mortems and architecture breakdowns from building production systems:

- [**Alerts people trust: what I learned building a monitoring bot**](https://saidixit.vercel.app/blog/alerts-people-trust)  
  *Why alerting on change matters more than alerting on state, and how to stop alert fatigue.*

- [**Why job postings drop out of Google for Jobs**](https://saidixit.vercel.app/blog/why-job-postings-drop-out-of-google-for-jobs)  
  *Common schema failures, crawl timing issues, and indexing mechanics observed across millions of jobs.*

- [**Daybook: building without a backend**](https://saidixit.vercel.app/blog/daybook-no-backend)  
  *How to build useful developer tools that run entirely in the browser without server maintenance.*

---

<div align="center">
  <sub>Sai Dixit Naidu &nbsp;·&nbsp; Visakhapatnam, India &nbsp;·&nbsp; <a href="https://saidixit.vercel.app/">saidixit.vercel.app</a></sub>
</div>
