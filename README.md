# Mousa Abdelmaksoud

Co-founder & CTO at **[familymind.ai](https://familymind.ai)** — building the AI operating system for families.
M.Sc. Computer Science, TU Munich. Based in Munich.

I ship products to real users with real feedback loops, and I've been doing it since I was 19.

---

## What I'm building now

**familymind** — one shared workspace where a family's calendars, tasks, and a proactive AI assistant live together. The AI doesn't wait to be prompted; it acts on context and signals, reducing mental load and preventing conflicts.

A few engineering numbers I'm willing to be drilled on:

- **23% → 36.8% acceptance rate** on proactive suggestions, measured on a 1,260-suggestion sample. The lift came from context engineering on top of GPT-OSS 120B served via Cerebras — encoding location, weather, holidays, bridge days, and calendar availability into the agent's window.
- **~10× p50 latency reduction** on agent-turn context assembly, by replacing repeated upstream API calls for context variables with a cache layer plus invalidation strategy.
- **2,300 users**, **7% week-over-week organic growth**, **€180K non-dilutive** (EXIST-Gründerstipendium, EXIST Women, AI Nation). No paid acquisition.
- Recognized as one of the **Top 4 Social Impact Startups in Germany** by DPS / UnternehmerTUM (2024).

I lead a team of 5 — two engineers report to me. I own the architecture: a polyglot stack (Spring Boot API gateway, FastAPI AI service), a multi-agent system (chat, proactive, utilities, knowledge maintenance), an eval loop driven by accept / reject / ignore signal, and a Postgres-backed family knowledge graph maintained by an autonomous agent with supersession and temporal-decay semantics.

---

## What I worked on before familymind

**AI Engineer at JetBrains** (Jun 2024 – Jul 2025, part-time, two product teams)
At JetBrains Academy, I shipped an end-to-end AI course-generation system to the curriculum team — a multi-agent pipeline producing module skeletons plus AST-based deterministic topic extraction — cutting their time-to-ship a new module by ~50%. Single-engineer ownership of a production system. On the AI Coding Assistant team, I ran the eval program comparing Claude Sonnet 4.6, OpenAI frontier models, and JetBrains' in-house code completion model, and built the Next-Edit-Suggestion baseline that set the bar for the internal training team to beat. A/B testing showed developers preferred speed over marginal accuracy gains — a finding that shaped product direction.

**Software Engineer at Siemens** (Dec 2023 – May 2024, Cybersecurity Department)
I pitched myself as a founder in the interview and walked out with product ownership of a research-stage internal DevSecOps platform instead of a generic intern bucket. I shipped it to production in 6 months: Vue 2 → Vue 3, JavaScript → TypeScript, Microsoft Entra ID integration, completed the Django backend, and built an API-key feature so developer teams could plug the security pipeline (Bandit, Semgrep, Gitleaks) into their own CI/CD. Adopted by the department as a working MVP.

**Co-founder & CTO at Niowell** (Feb – Oct 2023)
A two-sided marketplace for mental-health and wellness professionals, with a B2B-HR layer for employers. I owned engineering: React + TypeScript frontend, Spring Boot microservices, Stripe, GitLab CI/CD, Docker. Onboarded ~120 verified providers, reached ~900 users, launched in Spain. I exited after eight months over structural co-founder misalignment — and used what I learned to choose Munich.

---

## Research

**M.Sc. thesis, TU Munich — Social Computing Group, Entrepreneurial Masterclass track.**
Grade 1.0 (German top mark), graduated with honors.

The thesis defined principles, tunable design variables, and a simulation harness for **proactive AI in personal assistance** — investigating how an AI assistant can deliver value without an explicit prompt. Motivated by a real retention problem at familymind: users dropped because the AI was reactive. The contributions shipped back into the product. The category — context- and signal-driven agents — is now becoming the dominant pattern in code completion, NES, and ambient assistants.

**B.Sc. thesis, Cairo University — Siemens-sponsored.**
Active-learning + uncertainty sampling on a transformer for customer-support ticket classification. The methodological choice attacked Siemens' actual constraint, labeling cost.

---

## How I work

I find a real user with a real problem, sell the dream before having the means, learn whatever adjacent discipline is required, ship to feedback, watch the user use it, iterate. That loop is the same one I ran at 19 when I built and shipped an ERP / inventory / accounting system to my dad's retail business (I studied double-entry accounting next to my CS degree to do it — the system is still running, unmaintained, today), and at 21 when I orchestrated a sponsoring company, a senior mentor I cold-recruited from LinkedIn, 12 selected students from 50 applicants, and the university into a self-invented VR/AR internship that the sponsor then used to land a B2B deal in Singapore.

---

## Stack

Python, FastAPI, Pydantic AI, multi-agent orchestration, eval pipelines, prompt + context engineering · Java, Spring Boot · TypeScript, Next.js, React · Flutter, Dart · PostgreSQL, Redis, RabbitMQ, Firebase · AWS, Docker, GitLab CI/CD · LangFuse · Anthropic, OpenAI, Cerebras · AST tooling · Microsoft Entra ID

---

## Reach me

- Email — [mousa@familymind.ai](mailto:mousa@familymind.ai)
- LinkedIn — [linkedin.com/in/mousa-abdelmaksoud](https://www.linkedin.com/in/mousa-abdelmaksoud/)
- familymind — [familymind.ai](https://familymind.ai)

Best path in: a specific problem you're working on. I'd rather argue about that than read another generic intro.
