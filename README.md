```bash
$ whoami
parkavi — AI Automation Engineer

$ cat stack.txt
n8n · Claude API · Supabase · PostgreSQL · Docker · Linux · Python · JavaScript

$ status
building  → telemetry alert pipelines, LLM workflows
learning  → LiteLLM gateway, GCP server deployment
open to   → AI automation · n8n · DevOps · technical operations roles
```

## ⚡ How I think about automation

```text
 webhook ──▶ validate ──▶ store ──▶ dedupe ──▶ flapping check
                                                     │
                       P1 🔴  P2 🟠  P3 🟡  P4 🟢 ◀── severity routing
                                                     │
                      quiet hours · rate limit · kill switch
```

Every alert is stored before it is sent, and noisy repeats are filtered out, so people only see what matters.

## 🛠️ Projects

| | Project | What it does |
|---|---|---|
| 🛰️ | **Telemetry-n8n** *(private, company repo)* | 30+ node n8n pipeline: deduplication, flapping detection, suppression, P1–P4 routing |
| 📈 | **WTF-SKORE** *(private)* | Claude-written equity research reports with live market data and an approve/reject email step |
| ♾️ | **infinityxz-n8n-workflows** *(private)* | Client automation: brief delivery, re-engagement, weekly digest |
| 🚗 | [veloce-thar-concierge](https://github.com/Parkavi111/veloce-thar-concierge) | Concept showroom site with an AI concierge ([live demo](https://parkavi111.github.io/veloce-thar-concierge/)) |

## 🌐 Connect

[parkaviautomation.com](https://parkaviautomation.com) · [LinkedIn](https://linkedin.com/in/parkavi-53136242a)
