<!-- ========================================================================
     HERO: THE LEADER CARD & PLAYMAT (TCG / EUROGAME CONCEPT)
     ======================================================================== -->
<div align="center">

  <img src="assets/leader-banner.svg" alt="Maikon Costa · Senior QA Engineer & RPA Developer" width="100%" />

  <p align="center">
    <a href="https://maikonfcosta.github.io/portfolio/" target="_blank">
      <img src="https://img.shields.io/badge/🎲_Live_Portfolio-Tabletop_&_TCG-0284c7?style=flat-square&logoColor=white" alt="Live Portfolio" />
    </a>
    <a href="https://www.linkedin.com/in/maikonfcosta/" target="_blank">
      <img src="https://img.shields.io/badge/LinkedIn-Maikon_Costa-0ea5e9?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" />
    </a>
    <a href="mailto:maikonfcosta@gmail.com">
      <img src="https://img.shields.io/badge/Email-maikonfcosta@gmail.com-334155?style=flat-square&logo=gmail&logoColor=white" alt="Email" />
    </a>
    <img src="https://img.shields.io/badge/Base-Valinhos%2C_SP_(Remote)-1e293b?style=flat-square&logoColor=white" alt="Location" />
    <img src="https://img.shields.io/badge/Status-Building_&_Open_to_Chat-0f766e?style=flat-square&logoColor=white" alt="Status" />
  </p>

</div>

---

### ⚡ Game Stats & Impact at a Glance

<div align="center">

| **~3,400** | **83% ➔ 20%** | **0% Flakiness** | **7 Days ➔ 1 Day** |
| :---: | :---: | :---: | :---: |
| **Active Tests in CI**<br><sub>Playwright, Vitest & xUnit across 6 products (Fluxo)</sub> | **Production Escape Rate**<br><sub>Defect drop achieved across four 2-week sprints</sub> | **Critical Ring Instability**<br><sub>Deterministic execution over consecutive builds</sub> | **Credit-Life RPA Bot**<br><sub>Consolidation speedup via Automation Anywhere & Python</sub> |

</div>

---

## 📜 The Rulebook · How I Play the Quality Game

In complex Eurogames (*Gloomhaven*, *Caverna*, *7 Wonders Duel*) and production systems, winning is never about lucky dice rolls: it's about knowing the rules inside out, isolating variables, and making sure the pipeline never breaks when you push to production.

I started out in **2018 with RPA**, solving messy operational workflows with deterministic bots. When I moved into **Quality Engineering (QA / SDET)**, I brought the exact same obsession: not just checking if a test turns green, but understanding exactly why systems fail and building safety nets so developers can deploy on Friday without anxiety.

- 🛡️ **Quality Engineering (Senior QA / SDET):** Built the QA foundation from scratch at Fluxo (foreign exchange fintech) across 6 products (.NET 8, Next.js, Python services, AI copilots). Reduced manual runs to **3.5% of test executions**, locked flaky rates to **0% in critical rings**, and bridged Datadog Error Tracking directly with Azure DevOps.
- ⚙️ **Process Automation (RPA Developer):** Built bots at BRQ Digital Solutions, Unimed Porto Alegre, and Bosch Service Solutions (8-year journey) using Automation Anywhere (A360 Certified), UiPath, Power Automate, and Python.
- 🤖 **AI-Assisted CI Diagnostics:** Experimenting with LLM agents that read error logs, PR diffs, and codebase context to classify failures (product bug vs infra hiccup vs test drift) with confidence scores.

<details>
<summary><b>📋 View Player Sheet · Quick Bio (Click to open)</b></summary>
<br>

| Trait | Details |
| :--- | :--- |
| **Player Name** | Maikon Felipe Fernandes da Costa |
| **Class & Archetype** | Senior QA Engineer · RPA Developer · SDET |
| **Education** | CST in Systems Analysis & Development (USF) · B.S. in Business Administration |
| **Base Coordinates** | Valinhos, São Paulo · Brazil (UTC-3) |
| **Languages** | Portuguese (Native) · English (Professional Working / B2) |
| **Special Moves** | Zero-flakiness test rings, contract drift scanning, load & SLO testing, enterprise RPA |

</details>

---

## 🃏 The Open Source Deck · Featured Projects

All projects below are fully open source, running on live CI/CD, and backed by reproducible code.

| Project | Focus & Core Stack | The Move (What it Does) | Live Deliverables |
| :--- | :--- | :--- | :--- |
| **[Playwright Reference Suite](https://github.com/maikonfcosta/playwright-reference-suite)** | `TypeScript` `Playwright` `Docker` | RealWorld/Conduit suite with per-test data isolation and direct API auth. Runs 17 critical tests in ~10s on push and 59 nightly cross-browser tests. | [Live HTML Report](https://maikonfcosta.github.io/playwright-reference-suite/)<br>• Docker environment |
| **[Failure Classifier](https://github.com/maikonfcosta/failure-classifier)** | `Python 3.12` `Typer` `CI Engine` | Deterministic CLI engine that classifies CI breaks into 3 causes: product defect, environment glitch, or test code drift. Categorized **20/22 real failures** correctly. | [GitHub Repo](https://github.com/maikonfcosta/failure-classifier)<br>• Production failure traces |
| **[AI CI Triage](https://github.com/maikonfcosta/ai-ci-triage)** | `TypeScript` `GitHub Actions` `LLM` | GitHub Action that correlates error traces, PR diffs, and source code to post root-cause diagnostics directly to PR reviews, pinpointing file and line number. | [Real PR Comment Demo](https://github.com/maikonfcosta/playwright-reference-suite/pull/1#issuecomment-5896070196)<br>• Idempotent updates |
| **[QA Playbook](https://github.com/maikonfcosta/qa-playbook)** | `Engineering Strategy` `Docs` | Public quality playbook covering test pyramid distribution, deterministic data isolation, bug taxonomy, and patch coverage gates (≥ 80%). | [Live Playbook Docs](https://maikonfcosta.github.io/qa-playbook/)<br>• Team quality blueprint |
| **[Synthetic Monitoring](https://github.com/maikonfcosta/synthetic-monitoring)** | `Playwright` `Actions` `SLOs` | Production headless probes auditing 4 live applications. Implements double-fault validation to completely eliminate false alerts during transient network blips. | [Live Demo GIF](https://github.com/maikonfcosta/synthetic-monitoring/blob/main/docs/demo.gif)<br>• Runs 2x daily in Actions |
| **[API Contract Lab](https://github.com/maikonfcosta/api-contract-lab)** | `Python` `OpenAPI` `pytest` | Contract drift verification and 24-rule RBAC authorization matrix against Gitea REST API v1. Validates resource possession vulnerabilities (BOLA/IDOR) in &lt;2s. | Dual ring (`@critical < 1s`, `@full`)<br>• GitHub Actions CI |
| **[Locust Performance Kit](https://github.com/maikonfcosta/locust-perf-kit)** | `Python` `Locust` `uv` | Load testing with realistic 80/20 reader/writer workloads and strict p95 latency gates (&lt;300ms). Injects controlled failure spikes to validate recovery. | [Live Demo GIF](https://github.com/maikonfcosta/locust-perf-kit/blob/main/docs/assets/locust-gate-demo.gif)<br>• Zero-dep runner |
| **[Data Seeding Pipeline](https://github.com/maikonfcosta/data-seeding-pipeline)** | `Python` `SQLite` `TDM` | Fast CLI generating relational test datasets with seed-locked reproducibility, foreign key cascade integrity, and strict PII sanitization conforming to LGPD. | [Live Demo GIF](https://github.com/maikonfcosta/data-seeding-pipeline/blob/main/docs/assets/seeding-demo.gif)<br>• 96% test coverage |
| **[Rotine & TrackFit PRO](https://rotine-compliance-report.vercel.app)** | `Next.js` `TypeScript` `Supabase` | Side ventures: Rotine (B2B RPA orchestration SaaS) and TrackFit PRO (offline-first fitness PWA). Audited for 100% pass on WCAG 2.2 AA accessibility. | [Live Compliance Report](https://rotine-compliance-report.vercel.app)<br>• Production deployment |

---

## 🗺️ Campaign Log · Where I've Been Playing

<details>
<summary><b>Click to expand the career campaign map (2014 – Present)</b></summary>
<br>

```mermaid
timeline
    title Career Progression & Campaign Milestones
    section 2014 - 2023 : Bosch Service Solutions : From Operations to Pioneering RPA Developer
    section 2023 - 2025 : BRQ Digital Solutions : RPA Consultant (Credit-life bot: 7 days to 1 day)
    section 2025 - 2026 : Unimed Porto Alegre : Systems Analyst / Healthcare RPA Developer
    section Jan - Sep 2026 : Fintech Fluxo : Senior QA Engineer (6 products · ~3,400 CI tests · 0% flakiness)
    section Present : Open Source & Consulting : Test Architecture, Playwright & Deterministic CI/CD
```

* **Round 04 · Present | Open Source & Test Architecture:** Crafting open-source test tooling, helping teams untangle flaky CI pipelines, and consulting on Playwright test architecture.
* **Round 03 · Jan/2026 – Sep/2026 | Senior QA Engineer @ Fluxo (B2B FX Fintech):** Owned the test strategy across 6 products (.NET 8, Next.js, Python, AI Copilots). Built QA from zero, scaled to ~3,400 tests, dropped defect escape from 83% to 20%, and achieved 0% flakiness on critical gates.
* **Round 02 · Aug/2025 – Jan/2026 | Systems Analyst / RPA Developer @ Unimed Porto Alegre:** Automated critical healthcare operations: assessment, bot development, integration testing, and production support.
* **Round 01 · Dec/2014 – Jun/2025 | RPA Consultant @ BRQ & 8-Year Journey @ Bosch:** Built financial bots reducing cycle time from 7 days to 1 day at BRQ. At Bosch, grew over 8 years from administration into full-time RPA pioneer since 2018 (Automation Anywhere, Catalytic, Power Automate).

</details>

---

## 🧰 Component Box · Tech Stack

<div align="center">

| Tray | Tools & Technologies |
| :--- | :--- |
| **QA & Test Automation** | ![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white) ![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white) ![xUnit](https://img.shields.io/badge/xUnit-512BD4?style=flat-square) ![Pytest](https://img.shields.io/badge/Pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white) ![Testing Library](https://img.shields.io/badge/Testing%20Library-E33332?style=flat-square&logo=testinglibrary&logoColor=white) ![MSW](https://img.shields.io/badge/MSW-FF6A33?style=flat-square) ![OpenAPI](https://img.shields.io/badge/OpenAPI-85EA2D?style=flat-square&logo=swagger&logoColor=black) ![Locust](https://img.shields.io/badge/Locust-3C8D2F?style=flat-square) ![Axe Core](https://img.shields.io/badge/Axe--Core-007ACC?style=flat-square) |
| **DevOps & Observability** | ![Azure DevOps](https://img.shields.io/badge/Azure%20DevOps-0078D7?style=flat-square&logo=azuredevops&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white) ![Datadog](https://img.shields.io/badge/Datadog-632CA6?style=flat-square&logo=datadog&logoColor=white) ![SonarCloud](https://img.shields.io/badge/SonarCloud-F3705A?style=flat-square&logo=sonarqubecloud&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white) ![Sentry](https://img.shields.io/badge/Sentry-362D59?style=flat-square&logo=sentry&logoColor=white) |
| **RPA & Process Engineering** | ![Automation Anywhere](https://img.shields.io/badge/Automation%20Anywhere-FF5A00?style=flat-square) ![UiPath](https://img.shields.io/badge/UiPath-FA4616?style=flat-square&logo=uipath&logoColor=white) ![Power Automate](https://img.shields.io/badge/Power%20Automate-0066FF?style=flat-square) ![Python Bots](https://img.shields.io/badge/Python%20Bots-3776AB?style=flat-square&logo=python&logoColor=white) |
| **Languages & Core Stacks** | ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![C# .NET 8](https://img.shields.io/badge/C%23%20.NET%208-512BD4?style=flat-square&logo=dotnet&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-CC292B?style=flat-square&logo=sqlite&logoColor=white) ![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white) ![Claude Code](https://img.shields.io/badge/Claude%20Code-D97757?style=flat-square&logo=anthropic&logoColor=white) ![MCP Protocol](https://img.shields.io/badge/MCP-111111?style=flat-square) |

</div>

---

## 🎲 Activity & Contribution Grid

<div align="center">
  <img height="160" src="https://maikon-readme-stats.vercel.app/api?username=maikonfcosta&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true" alt="GitHub stats for maikonfcosta" />
  <img height="160" src="https://maikon-readme-stats.vercel.app/api/top-langs/?username=maikonfcosta&layout=compact&theme=tokyonight&hide_border=true" alt="Most-used languages in maikonfcosta" />
</div>

<br>

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/maikonfcosta/maikonfcosta/output/github-contribution-grid-snake-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/maikonfcosta/maikonfcosta/output/github-contribution-grid-snake.svg">
    <img alt="GitHub contribution grid snake animation" src="https://raw.githubusercontent.com/maikonfcosta/maikonfcosta/output/github-contribution-grid-snake.svg" width="95%" />
  </picture>
</div>

---

## 🪑 Pull Up a Chair · Let's Talk!

> *"A test only counts when it has the real power to fail on the bug."* 🎲⚔️

Whether you want to chat about QA architecture, building flakiness-free CI/CD pipelines, or just talk about heavy Eurogames:

* 🌐 **Interactive Portfolio:** [maikonfcosta.github.io/portfolio](https://maikonfcosta.github.io/portfolio/)
* 💼 **LinkedIn:** [linkedin.com/in/maikonfcosta](https://www.linkedin.com/in/maikonfcosta/)
* 📬 **Email:** [maikonfcosta@gmail.com](mailto:maikonfcosta@gmail.com)
* 🎲 **Off-Duty:** Modern Heavy Board Games (*Gloomhaven*, *Caverna*, *Azul*) · One Piece TCG Competitive · Funko Collector · Family time.
