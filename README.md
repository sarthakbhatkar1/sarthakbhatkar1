# Hi, I'm Sarthak Bhatkar

**AI Platform Engineer | LLM Infrastructure | Distributed Systems**

[Website](https://worxlabs.in) · [LinkedIn](https://YOUR-LINKEDIN-URL) · [Medium](https://YOUR-MEDIUM-URL) · [Email](mailto:YOUR-EMAIL)

I build infrastructure that helps teams run AI systems reliably and securely in production.

I'm a **Lead, AI Platform Engineering at State Street**, working on enterprise AI infrastructure, model access, responsible AI, and high-throughput LLM systems. I also run **[WorxLabs](https://worxlabs.in)**, a studio that builds AI-first SaaS products.

My work sits between backend engineering, distributed systems, AI infrastructure, and developer platforms. I'm most interested in the problems that show up once AI moves past the prototype: latency, reliability, cost, security, observability, and operational complexity.

---

## What I Work On

### Enterprise AI infrastructure

I lead engineering on a governed LLM gateway that gives enterprise applications centralized model access with responsible AI controls built in.

| Metric | Scale / Impact |
|---|---|
| LLM traffic | 1.5B+ tokens processed daily |
| Model ecosystem | Access to 150+ models |
| Adoption | 21 enterprise teams |
| Request volume | 100K+ requests daily |
| Latency | 71% reduction in P50 latency |
| Cost efficiency | $200K+ quarterly savings |

*These figures describe enterprise systems I've worked on, not personal open-source projects.*

Areas I work in:

- **Gateway and routing:** multi-model access, provider abstraction, failover, request governance
- **Responsible AI:** configurable guardrails, content moderation, PII protection, auditability
- **Performance:** latency, caching, concurrency, resource efficiency
- **Security:** OAuth2, JWT, managed identities, multi-tenant authorization
- **Developer experience:** Python and TypeScript SDKs, standardized APIs, onboarding
- **Operations:** Kubernetes deployments, CI/CD, production support

### Research and recognition

- **ContextIQ-RAG:** co-authored a paper on post-retrieval optimization for enterprise RAG
- **Amdocs AI Challenge:** hackathon winner

---

## Selected Projects

| Project | What it is | Focus |
|---|---|---|
| **VanLLM** | Distributed guardrail engine for LLM interactions. Four independently deployable gRPC services with concurrent safety checks, short-circuit execution, and distributed tracing. | AI safety, distributed systems |
| **SentinelEval** | Evaluation and red-teaming workbench. Configurable suites, LLM-as-a-judge and deterministic scoring, refusal detection, CLI with CI quality gates, and a web dashboard. | AI evaluation, developer tooling |
| **Vani** | Local voice assistant and agent system. Speech pipeline, local LLM inference, planner and executor, tool registry, and hybrid memory. | Agents, local inference |
| **Extracto** | Document processing system that extracts structured information from unstructured files. | Extraction pipelines, retrieval |

---

## Technical Toolkit

| Area | Technologies |
|---|---|
| Languages | Python, TypeScript, JavaScript, SQL, C++ |
| Backend | FastAPI, REST, gRPC, Pydantic, SQLAlchemy |
| AI / LLM | LiteLLM, LangChain, LangGraph, LlamaIndex, Promptflow, RAG, MCP |
| AI reliability | Guardrails, LLM evaluation (G-Eval, DeepEval), red teaming, model routing |
| Infrastructure | Kubernetes (AKS), Docker, Azure, AWS, CI/CD |
| Data and messaging | PostgreSQL, Redis, Azure Event Hubs |
| Observability | OpenTelemetry, Grafana, distributed tracing |

---

## How I Approach Engineering

A prototype shows something is possible. A production system has to stay reliable under load, handle failures, protect its users, and be maintainable by other engineers. A few principles I follow:

- **Design for failure.** Error handling, observability, and recovery belong in the first version.
- **Measure before optimizing.** Performance problems are usually architectural.
- **Make safe behavior the default.** Security and guardrails belong in the platform.
- **Keep it simple.** Good abstractions make infrastructure easier for other teams to adopt.

---

## Outside Work

I like trying new technologies, building side projects, playing guitar, working out, and watching anime. I'm always glad to talk with engineers working on AI infrastructure, distributed systems, and developer platforms.
