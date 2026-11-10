# Aman Verma — Engineering Dossier

A grounded, evidence-based self-review of my coding standards across five shipped modules (2023 → now) — measured on the things code review actually penalizes: concurrency safety, crash surface, test coverage, and architectural boundaries.

## 🔗 Live site

**→ [av-feaster.github.io/aman-dossier](https://av-feaster.github.io/aman-dossier/)**

The landing page is the full **Engineering Growth** report.

## The arc at a glance

| Era | Module | External grade |
| --- | --- | --- |
| 2023 · Intern | Auth / Token Refresh | C− |
| Late 2023 | DQAnalytics SDK | B− |
| 2024 | DQAnalytics 2.0 | B |
| 2025 · Mid | Webinar 2.0 | B+ |
| Now · Lead | DxAgent (AI) | A− |

**Platforms:** iOS (Swift) → KMM / Compose · **Span:** 2023 → present · **Basis:** direct source review of each module

The clearest single proof point: unsynchronized data races were my biggest 2023 failure, and documented lock-based concurrency is now one of my strongest areas — a direct line from a named weakness to a named strength.

## Contents

| File | What it is |
| --- | --- |
| [`index.html`](./index.html) | The Engineering Growth report (served as the live site) |
| [`Aman — Engineering Growth (LinkedIn).html`](./Aman%20%E2%80%94%20Engineering%20Growth%20%28LinkedIn%29.html) | LinkedIn-share variant of the report |
| [`Aman Verma — Engineering, in motion.html`](./Aman%20Verma%20%E2%80%94%20Engineering%2C%20in%20motion.html) | Companion "Engineering, in motion" page |
| [`Engineering Growth — Code Quality Over Three Eras.md`](./Engineering%20Growth%20%E2%80%94%20Code%20Quality%20Over%20Three%20Eras.md) | Source write-up in Markdown |

---

<sub>Prepared from direct source review · Token Mgr (Jul '23) · DQAnalytics (Nov '23) · DQAnalytics 2.0 (2024) · Webinar 2.0 (2025) · DxAgent (current)</sub>
