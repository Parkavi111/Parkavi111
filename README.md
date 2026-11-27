<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&center=true&vCenter=true&width=560&lines=AI+Automation+Engineer;n8n+workflows+and+LLM+pipelines;Alerts+%7C+Telemetry+%7C+Guardrails" alt="Typing animation" />

[![Website](https://img.shields.io/badge/Website-parkaviautomation.com-1f6feb?style=flat-square)](https://parkaviautomation.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Parkavi_S-0a66c2?style=flat-square)](https://linkedin.com/in/parkavi-53136242a)

</div>

```text
$ whoami
parkavi — AI Automation Engineer

$ status
building  → telemetry alert pipelines, LLM workflows
learning  → LiteLLM gateway, GCP server deployment
open to   → AI automation · n8n · DevOps · technical operations roles
```

## 🛠️ Tech Stack

<p align="center">
  <img src="https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white" alt="n8n" />
  <img src="https://skillicons.dev/icons?i=py,js,postgres,supabase,docker,linux,git,github" alt="Tech stack icons" />
</p>

| Area | Tools |
|---|---|
| Automation | n8n, webhooks, REST APIs, JSON |
| AI | Claude API, LLM workflows |
| Data | Supabase, PostgreSQL |
| Code | Python, JavaScript |
| Ops | Docker, Linux, Git, GitHub |

## ⚡ How I think about automation

```mermaid
flowchart LR
  A[Webhook] e1@--> B[Validate] e2@--> C[Store] e3@--> D[Dedupe] e4@--> E[Flapping check] e5@--> F{Severity routing}
  F e6@--> P1[P1 🔴]
  F e7@--> P2[P2 🟠]
  F e8@--> P3[P3 🟡]
  F e9@--> P4[P4 🟢]
  G[Quiet hours, rate limit, kill switch] e10@-.-> F

  e1@{ animate: true }
  e2@{ animate: true }
  e3@{ animate: true }
  e4@{ animate: true }
  e5@{ animate: true }
  e6@{ animate: true }
  e7@{ animate: true }
  e8@{ animate: true }
  e9@{ animate: true }
  e10@{ animate: true }

  classDef input fill:#1f6feb,stroke:#58a6ff,color:#ffffff
  classDef step fill:#238636,stroke:#3fb950,color:#ffffff
  classDef check fill:#9e6a03,stroke:#d29922,color:#ffffff
  classDef route fill:#8957e5,stroke:#bc8cff,color:#ffffff
  classDef guard fill:#da3633,stroke:#f85149,color:#ffffff
  class A input
  class B,C,D step
  class E check
  class F,P1,P2,P3,P4 route
  class G guard
```

Every alert is stored before it is sent, and noisy repeats are filtered out, so people only see what matters.

## 🛡️ How I keep AI posts safe

```mermaid
flowchart LR
  A[Pick page] e1@--> B[LLM writes post] e2@--> C[Rule check] e3@--> D[LLM fact check] e4@--> E{Approve?} e5@--> F[Publish]
  C e6@-->|blocked| X[Log and email alert]
  D e7@-->|blocked| X

  e1@{ animate: true }
  e2@{ animate: true }
  e3@{ animate: true }
  e4@{ animate: true }
  e5@{ animate: true }
  e6@{ animate: true }
  e7@{ animate: true }

  classDef input fill:#1f6feb,stroke:#58a6ff,color:#ffffff
  classDef ai fill:#8957e5,stroke:#bc8cff,color:#ffffff
  classDef check fill:#9e6a03,stroke:#d29922,color:#ffffff
  classDef ok fill:#238636,stroke:#3fb950,color:#ffffff
  classDef stop fill:#da3633,stroke:#f85149,color:#ffffff
  class A input
  class B,D ai
  class C,E check
  class F ok
  class X stop
```

Two layers check every AI-written post, and a blocked post is logged instead of published.

## 🚀 Projects

| | Project | What it does |
|---|---|---|
| 🛰️ | **Telemetry-n8n** *(private, company repo)* | 30+ node n8n pipeline: deduplication, flapping detection, suppression, P1–P4 routing |
| 📈 | **WTF-SKORE** *(private)* | Claude-written equity research reports with live market data and an approve/reject email step |
| ♾️ | **infinityxz-n8n-workflows** *(private)* | Client automation: brief delivery, re-engagement, weekly digest |
| ⓕ | [placidway-daily-facebook-post](https://github.com/Parkavi111/placidway-daily-facebook-post) | n8n workflow: AI-written daily Facebook post with two-layer guardrails and an approval option |
| 🚗 | [veloce-thar-concierge](https://github.com/Parkavi111/veloce-thar-concierge) ([live demo](https://parkavi111.github.io/veloce-thar-concierge/)) | Concept showroom site with an AI concierge |
| 🧭 | [nextstep-wellbeing-compass](https://github.com/Parkavi111/nextstep-wellbeing-compass) | 4-question app that suggests one gentle next step, with hard-coded safety rules (demo, fictional data) |
| 🤖 | **arop** *(private)* | Flask app that manages simulated robots: tasks, auto-assignment, dashboard and 78 tests |
| 💼 | **linkedin-outreach-ai-improved** *(private)* | Chrome extension that writes LinkedIn messages. I added a connection note length limit and a live character counter |

<details>
<summary><b>More about arop</b></summary>

- Flask and SQLite
- Light and heavy robots, task priorities, manual and automatic assignment
- Simulation with battery drain and charging
- Admin login with CSRF protection
- 78 passing tests (as stated in its README)

</details>

## 🧪 Current Focus
- Telemetry alert pipelines
- LLM workflows
- LiteLLM gateway
- GCP server deployment
