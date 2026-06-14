# AI Automation Engineer — Daily Interview Questions

A growing **public bank of interview questions** for AI / automation engineers, generated automatically every day by an [n8n](https://n8n.io/) + GPT workflow.

Each morning the workflow picks a topic (rotating across 12 areas — n8n & workflow automation, LLM apps / agents / RAG, REST API & webhook integrations, prompt engineering, JS/TS, Python, automation architecture, databases & vector stores, security, observability, system design, data/ETL), asks GPT to produce one realistic interview question, and commits it here as `questions/YYYY-MM-DD.md`.

> Model answers are kept in a separate private practice log — this repo is the **question bank** only.

## How it works

```
Every day 09:00 → Pick topic (by day-of-year) → GPT writes a question + answer
                                                   ├─► Telegram (question + answer, to me)
                                                   ├─► this repo   questions/YYYY-MM-DD.md  (question only)
                                                   └─► private repo answers/YYYY-MM-DD.md   (question + answer)
```

## Tech stack

- **n8n** — orchestration & scheduling
- **OpenAI GPT** — generates the question and a model answer
- **Telegram** — daily delivery
- **GitHub** — public question bank + private answer log

The workflow definition lives in [`workflows/`](workflows/).

---
*Portfolio / personal automation project. Built and validated with the n8n Workflow SDK.*
