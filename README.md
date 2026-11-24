# Sai Dixit Naidu

Building data pipelines, automation scripts, and lightweight web tools.

[Website](https://saidixit.vercel.app/) · [Works](https://saidixit.vercel.app/works/) · [Writing](https://saidixit.vercel.app/blog/) · [LinkedIn](https://www.linkedin.com/in/sai-dixit) · [Twitter / X](https://x.com/SaiDixitNaidu) · [saidixitn@gmail.com](mailto:saidixitn@gmail.com)

---

### About

I'm a developer based in Visakhapatnam, India.

I like building software that quietly does real work in the background. Most of my day is spent writing Python scripts, working with databases like BigQuery and MongoDB, and building automation that removes repetitive human effort.

I find where information gets stuck, then build what gets it moving:
- **Spot the pattern**: Notice where a team gets slowed down or why someone is manually doing the same check twice.
- **Build the fix**: Write a clean script, clean up messy data, or create a simple tool.
- **Automate it**: If a task needs to run every morning, code should handle it in the background without needing a person to remember.
- **Keep it calm**: No bloat, no unnecessary dependencies, and no complicated setup. Software should do its job fast and stay out of the way.

---

### Projects & Repositories

#### 1. [Python](https://github.com/saidixitn/Python) — Automated Data Operations Fleet

- **What it is**: A collection of background scripts that run 24/7 on a server to move and sync data between databases, spreadsheets, and data warehouses.
- **Why I built it**: Checking partner feeds, doing daily data imports, and updating spreadsheets by hand takes hours and leads to mistakes. I built this fleet so code handles all routine data operations automatically every morning.
- **How it works**: Built in Python and kept running continuously with PM2 (a Linux process manager). The scripts pull records from MongoDB, clean up the formatting, stream data into Google BigQuery for analytics, and sync metrics directly to Google Sheets.

---

#### 2. [antigravity-nodejs](https://github.com/saidixitn/antigravity-nodejs) — Fast Backend Engine for MongoDB

- **What it is**: A clean, lightweight Node.js backend designed to run fast searches and queries across large MongoDB databases.
- **Why I built it**: Many backend frameworks are heavy and slow down when handling large volumes of database records. I wanted a lean API server that connects directly to the database without extra bloat.
- **How it works**: Built with Node.js and Express. It uses a "dual-mode" setup: small test tasks run locally on your own machine, while production tasks dynamically connect to secure cloud databases. It streams database records in chunks so the server never runs out of memory.

---

#### 3. [Job-Posting-Alerts](https://github.com/saidixitn/Job-Posting-Alerts) — Search Engine Indexing & Schema Monitor

- **What it is**: A monitoring bot that checks whether structured job listings are showing up properly on Google for Jobs, and alerts the team if anything breaks.
- **Why I built it**: When a website makes a small coding error in its structured schema, Google can stop showing its job listings. If nobody notices, the site loses visitors for weeks.
- **How it works**: Runs automatically on a schedule. Instead of sending spammy alerts every day, it compares today's run with yesterday's run. If it detects a drop or an error, it sends an immediate notification via Telegram and webhooks with details on what broke.

---

#### 4. [jobinsights](https://github.com/saidixitn/jobinsights) — Privacy-Friendly Web Analytics

- **What it is**: A tiny website analytics tool that counts visitors and tracks page performance without using tracking cookies.
- **Why I built it**: Standard tools like Google Analytics are heavy, slow down web pages, and require annoying cookie banner popups. I wanted an analytics engine that gives useful numbers while respecting user privacy.
- **How it works**: Uses a tiny JavaScript tracking script (under 2 KB) that logs page views and performance vitals. Because it does not store personal data or use tracking cookies, it loads instantly and complies with privacy laws out of the box.

---

#### 5. [daybook](https://github.com/saidixitn/daybook) — Zero-Backend Developer Ledger

- **What it is**: A minimal task and notes tracker that runs completely inside your web browser.
- **Why I built it**: Most note-taking and to-do apps require creating accounts, logging in, and waiting for slow servers. I wanted a tool that opens instantly, works without an internet connection, and never requires server maintenance.
- **How it works**: Built with plain HTML, CSS, and vanilla JavaScript. It saves all your notes and task history directly in your browser's local storage. There is no backend server to pay for or maintain.

---

#### 6. [Automation](https://github.com/saidixitn/Automation) — Scheduled Scripts & Daemons

- **What it is**: A set of standalone Python scripts that automate routine jobs like web scraping and email reports.
- **Why I built it**: To save time on repetitive daily computer tasks by letting scheduled scripts do the heavy lifting in the background.
- **How it works**: Runs on automated timers (cron). The scripts fetch data from websites and APIs, format the results into clean summaries, and automatically email reports to stakeholders.

---

#### 7. [google-paa-scraper](https://github.com/saidixitn/google-paa-scraper) — Search Question Crawler

- **What it is**: A Python crawler that gathers Google's "People Also Ask" questions for any search topic.
- **Why I built it**: To understand what real people are searching for online and help research search trends.
- **How it works**: Takes a search keyword, queries Google, expands the related questions, and maps out the question tree so you can see what topics users care about most.

---

### What I Use

- **Languages**: Python, JavaScript, SQL, HTML, CSS
- **Databases & Warehouses**: Google BigQuery, MongoDB
- **Automation & Tools**: PM2, Cron, Git, GitHub Actions, Google Sheets API
- **Web & APIs**: Node.js, Express, REST APIs

---

### Writing & Articles

I also write about what I learn while building these systems:

- [**Alerts people trust: what I learned building a monitoring bot**](https://saidixit.vercel.app/blog/alerts-people-trust)  
  *Why sending too many alerts causes teams to ignore them, and how to alert only on meaningful changes.*

- [**Why job postings drop out of Google for Jobs**](https://saidixit.vercel.app/blog/why-job-postings-drop-out-of-google-for-jobs)  
  *Common coding errors that cause Google to remove listings from search results.*

- [**Daybook: building without a backend**](https://saidixit.vercel.app/blog/daybook-no-backend)  
  *How to build fast, useful tools that run entirely in the browser with zero server costs.*

---

<div align="center">
  <sub>Sai Dixit Naidu · Visakhapatnam, India · <a href="https://saidixit.vercel.app/">saidixit.vercel.app</a></sub>
</div>
