<h1 align="center">Parkavi S</h1>

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
  <img src="https://cdn.simpleicons.org/n8n/EA4B71" alt="n8n" width="48" height="48" />
  &nbsp;
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
  G[Quiet hours, rate limit, kill switch]
