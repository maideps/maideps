<div align="center">

# Maidelín Prieto Soto

### Agentic Engineer · AI / Full-Stack

I build software with AI coding agents, every change tested and recorded. And I build AI agents that keep a human in the loop.

**Barcelona, Spain** · **15+ years in software development** · **Spanish / English**

<p>
  <a href="mailto:maidelin.prieto@gmail.com"><img src="https://img.shields.io/badge/Email-maidelin.prieto%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email" /></a>
  <!-- TODO: replace YOUR-HANDLE, then remove these comment markers:
  <a href="https://www.linkedin.com/in/YOUR-HANDLE"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  -->
  <a href="https://github.com/aleph-engineering-gmbh"><img src="https://img.shields.io/badge/Aleph_Engineering-181717?style=flat-square&logo=github&logoColor=white" alt="Aleph Engineering on GitHub" /></a>
</p>

</div>

---

## About me

I am a Computer Science Engineer with 15+ years across web, backend, mobile and enterprise software: hospital emergency management, ERP/CRM implementations, multi-repository product platforms and, now, AI products. I am most comfortable where requirements are complex, integrations matter and the software has to stay understandable long after the first release.

I develop with AI coding agents every day, under my own open-source harness, **[ai-harness-framework](https://github.com/maideps/ai-harness-framework)**. The agent writes code; I own the design, the review and the result.

## Currently

- 🛠️ Full-Stack Software Developer at **[Aleph Engineering](https://github.com/aleph-engineering-gmbh)**, on a 15+ repository recycling-rewards platform
- 🏗️ Building **[studio-booking-saas](https://github.com/maideps/studio-booking-saas)** (notifications, audit log and public API are next) and **[ai-app-chassis](https://github.com/maideps/ai-app-chassis)**
- 🤝 Open to AI / full-stack roles where AI-assisted engineering is done with discipline

## Selected work

Public projects, built with AI coding agents under the harness workflow:

| Project | What it shows | Stack |
|---|---|---|
| **[ai-issue-triage](https://github.com/maideps/ai-issue-triage)** | Proposes a label, finds likely duplicates and drafts a doc-grounded reply for a maintainer to approve. Evaluated on 9,411 real astral-sh/uv issues: duplicate recall@10 **0.527** vs about 0.40 for vector or keyword search alone; type macro-F1 **0.592** vs 0.143 for always guessing "bug". LLM steps still run on stand-ins, and the README says so. | FastAPI, PostgreSQL + pgvector, LangGraph, scikit-learn, React, Docker |
| **[ai-invoice-intake](https://github.com/maideps/ai-invoice-intake)** | AI drafts, a person decides: every extracted field is checked against the source PDF. Three roles, append-only audit trail, HMAC-signed webhook, idempotent background jobs. Released as v1.0.0; one `docker compose up`. | FastAPI, PostgreSQL, Redis, React, TypeScript, Docker |
| **[studio-booking-saas](https://github.com/maideps/studio-booking-saas)** | Multi-tenant booking and membership SaaS. Tenant isolation, race-free bookings and exactly-once Stripe webhooks, proven by tests on a real PostgreSQL. In progress: 8 of 14 features. | Laravel, Vue 3, Inertia, PostgreSQL, Pest, Docker |
| **[ai-harness-framework](https://github.com/maideps/ai-harness-framework)** | The harness behind every project here: feature list, one task at a time, layered verification gates, sprint contracts, session handoffs. Tested on Node, Python, Go and Rust projects. | JavaScript |
| **[ai-codebase-auditor](https://github.com/maideps/ai-codebase-auditor)** | Decides whether AI coding agents can safely work in a codebase, legacy systems first: adopt, adapt or prepare first. Calibrated on five real repositories, including Redmine, phpBB and Struts. | TypeScript |
| **[ai-app-chassis](https://github.com/maideps/ai-app-chassis)** | The base I build LLM apps on, extracted from the apps above: provider port with a fake model, per-step routing, cost ledger, versioned prompts, guardrails, eval gate. Early: 2 of 6 features. | Python, FastAPI, Pydantic, LiteLLM |

<p align="center">
  <a href="https://github.com/maideps/ai-issue-triage"><img src="https://github.com/maideps/ai-issue-triage/raw/main/docs/images/review.png" width="410" alt="ai-issue-triage: an issue beside a draft reply that quotes the uv docs, waiting for a maintainer's decision" /></a>
  <a href="https://github.com/maideps/ai-invoice-intake"><img src="https://github.com/maideps/ai-invoice-intake/raw/main/docs/images/review.png" width="410" alt="ai-invoice-intake: the source PDF beside the extracted fields and their confidence" /></a>
</p>

## Agentic engineering: how I work with AI coding agents

1. **Spec first.** Scope, architecture and standards are written down before any code.
2. **One feature at a time.** Work is split into a feature list, with a contract for each step.
3. **Gates decide, not the agent.** Lint, type check, tests, build and end-to-end must pass; a skipped check does not count as verified.
4. **Decisions are recorded.** Each non-obvious choice goes into a decisions log, so the reasoning outlives the session.
5. **A human reviews.** Agent output is a draft until I have read it and accepted it.

The projects also test the framework. Building ai-invoice-intake turned up two bugs in it ([D-021](https://github.com/maideps/ai-harness-framework/blob/master/DECISIONS.md#d-021-backup-ids-are-forced-strictly-monotonic-not-left-to-clock-resolution), [D-022](https://github.com/maideps/ai-harness-framework/blob/master/DECISIONS.md#d-022-adoption-matrix-fixtures-use-canonical-layer-scripts-not-the-host-repos-customised-ones)) and [nine improvement issues](https://github.com/maideps/ai-harness-framework/issues?q=is%3Aissue%20created%3A2026-10-14), all fixed upstream.

Underneath the workflow: keep the architecture proportional to the problem, automate repetition rather than judgment, and understand the business process before the first line of code.

## Experience

| Role | Company | Period |
|---|---|---|
| **Full-Stack Software Developer** | Aleph Engineering · Germany / Remote | 2026 – Present |
| **Project Manager, Citykleta project** | Aleph Engineering · Germany / Remote | 2026 |
| **AI Workflow Developer & Operations Lead** | Cuban Engineer · Remote | 2024 – Present |
| **Zoho Developer** | Zeus4 · USA / Remote | 2023 – 2024 |
| **Project Manager & Software Developer** | Desoft · Cuba | 2009 – 2022 |

Professional work (private, described at a high level):

| Project | What I did | Stack |
|---|---|---|
| **Imagined Earth** | Reverse-vending and recycling-rewards platform: mobile apps, backend services and web interfaces across 15+ repositories, plus Android releases. | Flutter, Laravel, TypeScript, React, Vue |
| **Citykleta** | Delivery management for a bike-rental platform across 7 repositories: ticketed plan, C4 architecture, ADRs, OpenAPI and runbooks. | Flutter, Node.js, TypeScript, React |
| **HireLens** | Backend for structured CV analysis, candidate scoring and interview-question generation with the OpenAI Responses API. | FastAPI, Python, OpenAI API |
| **AI Marketing Automation** | Pipeline that turns structured editorial plans into branded, automatically styled Google Docs. | Python, Google Docs/Drive APIs |
| **SIUM** | Incident, resource and workflow management for hospital emergency departments. | Symfony, PostgreSQL |
| **Enterprise ERP/CRM** | Implementations for water management, ITIL service desks, honey production and luxury manufacturing. | Odoo, Zoho CRM, PostgreSQL |

## Toolbox

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white)
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=flat-square&logo=laravel&logoColor=white)
![Symfony](https://img.shields.io/badge/Symfony-000000?style=flat-square&logo=symfony&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)

AI and data: RAG (pgvector + BM25), LangGraph, LiteLLM, OpenAI API, sentence-transformers, scikit-learn, MCP, evaluation against real data.

Also: Node.js, Inertia.js, Pest, MySQL, SQL Server, Redis, GitHub Actions, Firebase, Odoo, Zoho CRM, Claude Code, Codex, Gemini CLI.

## Education and languages

**MSc. in Applied Computing**, University of Sancti Spíritus “José Martí” (2013–2015) · **BSc. in Computer Science Engineering**, University of Informatics Sciences (2004–2009) · **Spanish** native · **English** professional working proficiency

---

<div align="center">

### Let’s build something useful.

<a href="mailto:maidelin.prieto@gmail.com"><strong>maidelin.prieto@gmail.com</strong></a>

</div>
