<div align="center">

# Maidelín Prieto Soto

### Full-Stack Software Engineer · Building with AI coding agents

I build reliable full-stack software for real business processes, and I build it with AI coding agents inside a workflow that keeps every change reviewed, tested and recorded.

**Barcelona, Spain** · **15+ years in software development** · **Spanish / English**

<p>
  <a href="mailto:maidelin.prieto@gmail.com"><img src="https://img.shields.io/badge/Email-maidelin.prieto%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://github.com/aleph-engineering-gmbh"><img src="https://img.shields.io/badge/Aleph_Engineering-181717?style=flat-square&logo=github&logoColor=white" alt="Aleph Engineering on GitHub" /></a>
  <!-- Add LinkedIn here:
  <a href="https://www.linkedin.com/in/YOUR-HANDLE"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  -->
</p>

</div>

---

## About me

I am a Computer Science Engineer and full-stack developer with 15+ years across web, backend, mobile and enterprise software — from hospital emergency-management systems and ERP/CRM implementations to multi-repository product platforms and AI-assisted internal tools.

I am most comfortable where requirements are complex, integrations matter and the software has to stay understandable long after the first release. I work mainly with **Python, PHP, TypeScript and Flutter**. I develop with AI coding agents every day, and I built my own harness, **[ai-harness-framework](https://github.com/maideps/ai-harness-framework)**, to make that work dependable: one feature at a time, verification gates that must pass, and written decisions. The agent writes code; I own the design, the review and the result.

> I enjoy turning complicated business processes into software that people can actually use and maintain.

## Currently

- 🔬 Measuring AI features against real outcomes: **[ai-issue-triage](https://github.com/maideps/ai-issue-triage)** is evaluated against what maintainers actually did with three years of real issues
- 🏗️ Building **[studio-booking-saas](https://github.com/maideps/studio-booking-saas)** (Laravel/Vue): notifications, an audit log and a public API are next
- 🧰 Extracting what my AI apps have in common into **[ai-app-chassis](https://github.com/maideps/ai-app-chassis)**
- 🛠️ Full-Stack Software Developer at **[Aleph Engineering](https://github.com/aleph-engineering-gmbh)**
- 🤝 Open to full-stack roles where AI-assisted engineering is done with discipline

## Selected work

Public projects, built with AI coding agents under the harness workflow:

| Project | What it shows | Stack |
|---|---|---|
| **[ai-issue-triage](https://github.com/maideps/ai-issue-triage)** | Issue triage with a maintainer in the loop: proposes a label, finds likely duplicates and prepares a doc-grounded draft reply for approval. Evaluated against 9,411 real astral-sh/uv issues: hybrid search puts the duplicate maintainers linked in the top 10 for about half of them. The language-model steps still run on stand-ins, and the README says so. | FastAPI, PostgreSQL + pgvector, LangGraph, scikit-learn, React, Docker |
| **[ai-invoice-intake](https://github.com/maideps/ai-invoice-intake)** | Human-in-the-loop invoice automation: AI drafts, a person decides. Source-PDF review, three roles, append-only audit trail, HMAC-signed webhook, idempotent background jobs. Synthetic data only; one `docker compose up`. | FastAPI, PostgreSQL, Redis, React, TypeScript, Docker |
| **[studio-booking-saas](https://github.com/maideps/studio-booking-saas)** | Multi-tenant booking and membership SaaS for small studios. Tenant isolation, race-free bookings and exactly-once Stripe webhooks are proven by tests on a real PostgreSQL rather than claimed. In progress: 8 of 14 features. | Laravel, Vue 3, Inertia, PostgreSQL, Pest, Docker |
| **[ai-codebase-auditor](https://github.com/maideps/ai-codebase-auditor)** | Audits a codebase, legacy systems first, and decides whether AI coding agents can work in it safely: adopt, adapt or prepare first. Calibrated on five real repositories, including Redmine, phpBB and Struts. | TypeScript |
| **[ai-harness-framework](https://github.com/maideps/ai-harness-framework)** | The open-source harness behind every project here: feature list, one task in progress at a time, layered verification gates, sprint contracts and session handoffs. An adoption matrix tests it on Node, Python, Go and Rust projects. | JavaScript |
| **[ai-app-chassis](https://github.com/maideps/ai-app-chassis)** | The base I build LLM apps on, extracted from the apps above: a provider port with a fake model, per-step model routing, a cost ledger, versioned prompts, guardrails and an eval gate. Early: 2 of 6 features. | Python, FastAPI, Pydantic, LiteLLM |

Earlier professional work (private, described at a high level):

| Project | What I did | Stack |
|---|---|---|
| **Imagined Earth** | Reverse-vending and recycling-rewards platform: mobile apps, backend services and web interfaces across 15+ repositories. | Flutter, Laravel, TypeScript, React, Vue |
| **HireLens** | Backend for structured CV analysis, candidate scoring and interview-question generation with the OpenAI Responses API. | FastAPI, Python, OpenAI API |
| **AI Marketing Automation** | Pipeline that turns structured editorial plans into branded, automatically styled Google Docs. | Python, Google Docs/Drive APIs |
| **SIUM** | Incident, resource and workflow management for hospital emergency departments. | Symfony, PostgreSQL |
| **Enterprise ERP/CRM** | Implementations for water management, ITIL service desks, honey production and luxury manufacturing. | Odoo, Zoho CRM, PostgreSQL |

## How I work with AI coding agents

1. **Spec first.** Scope, architecture and standards are written down before any code.
2. **One feature at a time.** Work is split into a feature list, with a contract for each step.
3. **Gates decide, not the agent.** Lint, type check, tests, build and end-to-end must pass; a skipped check does not count as verified.
4. **Decisions are recorded.** Each non-obvious choice goes into a decisions log, so the reasoning outlives the session.
5. **A human reviews.** Agent output is a draft until I have read it and accepted it.

The projects also test the framework. Building ai-invoice-intake turned up two bugs in it ([D-021](https://github.com/maideps/ai-harness-framework/blob/master/DECISIONS.md#d-021-backup-ids-are-forced-strictly-monotonic-not-left-to-clock-resolution), [D-022](https://github.com/maideps/ai-harness-framework/blob/master/DECISIONS.md#d-022-adoption-matrix-fixtures-use-canonical-layer-scripts-not-the-host-repos-customised-ones)) and [nine improvement issues](https://github.com/maideps/ai-harness-framework/issues?q=is%3Aissue%20created%3A2026-10-14), all fixed upstream.

## Toolbox

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white)
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=flat-square&logo=laravel&logoColor=white)
![Symfony](https://img.shields.io/badge/Symfony-000000?style=flat-square&logo=symfony&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)

AI and data: RAG (pgvector + BM25), LangGraph, LiteLLM, OpenAI API, sentence-transformers, scikit-learn, MCP, evaluation against real data.

Also: Node.js, Inertia.js, Pest, MySQL, SQL Server, Redis, GitHub Actions, Firebase, Odoo, Zoho CRM, Claude Code, Codex, Gemini CLI.

## Experience

| Role | Company | Period |
|---|---|---|
| **Full-Stack Software Developer** | Aleph Engineering · Germany / Remote | 2026 – Present |
| **Software Automation Developer & IT Recruiter** | Cuban Engineer · Cuba / Remote | 2024 – Present |
| **Zoho Developer** | Zeus4 · USA / Remote | 2023 – 2024 |
| **Project Manager & Software Developer** | Desoft · Cuba | 2009 – 2022 |

## How I approach engineering

- **Keep the architecture proportional to the problem.** Not every feature needs a new abstraction or service.
- **Automate repetition, not judgment.** Tools should remove mechanical work and leave important decisions visible.
- **Prefer maintainable over clever.** Readable code and clear ownership age better than impressive shortcuts.
- **Treat AI output as a draft.** Review, testing and accountability still belong to the engineer, which is why my workflow has verification gates.
- **Understand the business process.** Good implementation starts before the first line of code.

## Education and languages

- **MSc. in Applied Computing** — University of Sancti Spíritus “José Martí”, 2013–2015
- **BSc. in Computer Science Engineering** — University of Informatics Sciences, 2004–2009
- **Spanish:** native · **English:** professional working proficiency

---

<div align="center">

### Let’s build something useful.

<a href="mailto:maidelin.prieto@gmail.com"><strong>maidelin.prieto@gmail.com</strong></a>

</div>
