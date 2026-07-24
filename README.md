# Mousa Abdelmaksoud

Co-founder & CTO at **[familymind.ai](https://familymind.ai)** — automating repeating pain points around family organisation with an AI operating system for families.
M.Sc. Computer Science, TU Munich. Based in Munich.

I ship products to real users with real feedback loops, and I've been doing it since I was 19.

---

## What I'm building now

**familymind** — one shared workspace where a family's calendars, tasks, and a proactive AI assistant live together. The AI doesn't wait to be prompted; it acts on context and signals.

Where the company is today:

- **3000 users** and **7% week-over-week organic growth**, with zero paid acquisition.
- **€180K raised non-dilutive** through EXIST-Gründerstipendium, EXIST Women, and AI Nation. No equity given up.
- Named **one of the Top 4 Social Impact Startups in Germany** by the [Social Impact Republic](https://www.social-impact-republic.org/), 2024.

Where the engineering is today:

- Increased the proactive AI's suggestion-acceptance rate from **23% to 36.8%**, a **60% relative improvement** measured over 1,260 production suggestions, by engineering richer context (location, weather, holidays, bridge days, calendar availability) on top of GPT-OSS 120B served via Cerebras.
- Cut agent-response latency by **~10× at p50** by replacing repeated upstream API calls with a cache layer and invalidation strategy.
- Designed and own the full system: a polyglot stack (Spring Boot API gateway, FastAPI AI service), a mulit-agent system (chat, proactive, utilities, knowledge maintenance), an eval loop driven by accept / reject / ignore signal, and a Postgres-backed family knowledge graph maintained by an autonomous agent that handles supersession and temporal decay.
- Lead a team of 5; two engineers report to me directly.

---

## How I see the future I'm building toward

The bottleneck for AI value has moved from model capability to context delivery. Frontier models are no longer the constraint; getting the right context to them at the right moment is. I think that reframes two of the most interesting problems in the field.

The first is **proactive AI** — agents that close the context loop themselves, anticipating what a user needs based on signals already available, instead of waiting for the user to type the right prompt. The next class of AI products won't be chat windows; they'll be agents that turn repeated interactions into background workflows the user never has to start.

The second is **structured knowledge for AI**. Inside companies sitting on thousands of documents, the AI is only as useful as the context it can assemble. Most knowledge systems were designed for human browsing, not for an agent. Software engineering already solved how to organize complex file bases so each developer has the right context: repositories, modules, references, dependencies. I think the next generation of organizational knowledge systems will borrow many concepts from software engineering practises. 

---

## How I Think & Build

I find a real user with a real problem, sell the dream before having the means, learn whatever adjacent discipline is required, ship to feedback, watch the user use it, iterate. That loop is the same one I ran at 19 when I built and shipped an ERP / inventory / accounting system to my dad's retail business (I studied double-entry accounting next to my CS degree to do it, the system is still running, unmaintained, today). At 21, eager to build in VR/AR, I identified a company with the budget for immersive tech but no structured internship or mentorship program to offer. To bridge this gap, I designed a custom program from scratch, sold it to the company to secure sponsorship, recruited a senior mentor via LinkedIn, obtained university accreditation, and selected 12 student interns from 50 applicants. Under my management, we shipped two educational VR games, an immersive [Chemistry Lab](https://github.com/mousamax/VR-Chemistry-Lab) and an anatomy-themed [Bio-game](https://github.com/mousamax/VR-Bio-Game) which the sponsor used to land a B2B deal in Singapore, while 4 student alumni later secured roles at FAANG.

---

## About the repos here

Most of my public repos are from school or earlier — they're history, not current work. The substantive engineering of the last few years is closed-source at familymind, JetBrains, and Siemens. Happy to walk through any of it in detail; ping me.

---

## Stack

Python, FastAPI, Pydantic AI, multi-agent orchestration, eval pipelines, prompt + context engineering · Java, Spring Boot · TypeScript, Next.js, React · Flutter, Dart · PostgreSQL, Redis, RabbitMQ, Firebase · AWS, Docker, GitLab CI/CD · LangFuse · Anthropic, OpenAI, Cerebras · AST tooling · Microsoft Entra ID

---

## Talk to me about

Proactive agents and GenUI. Knowledge graphs and context systems for personal and organizational AI. Founder hiring, technical co-founder questions, and what it's like building a company in the German ecosystem.

- Email — [mousa@familymind.ai](mailto:mousa@familymind.ai)
- LinkedIn — [linkedin.com/in/mousa-abdelmaksoud](https://www.linkedin.com/in/mousa-abdelmaksoud/)
- familymind — [familymind.ai](https://familymind.ai)
