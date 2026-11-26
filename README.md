# Yan Lo Bianco

### Senior Software Engineer · Back-end, Distributed Systems & AI-First Engineering

I build back-end systems that keep data consistent while everything around them changes: legacy migrations, event pipelines and, lately, AI agents that write and test code under human supervision. 8+ years in, I still write code every day.

Over seven years as a senior engineer at **ZG Soluções**, a health-tech company, I was the **sole developer of an analytics platform**, helped migrate the **most critical module of a legacy monolith to a multi-tenant, event-driven platform** with Kafka and CDC, and built an **AI development toolkit adopted as the default by all ~50 developers** in the company, which became the foundation for autonomous QA agents.

**Goiânia, Brazil (UTC−3) · Open to senior back-end and full-stack roles, remote**

[LinkedIn](https://www.linkedin.com/in/yanlobianchi/) · [Portfolio](https://yan-lobianco.netlify.app)

---

## What I work on

**Data consistency in distributed systems.** CDC with Debezium, idempotent upserts, out-of-order events, entities that wait for data that doesn't exist yet, and automated reconciliation when events get lost.

**AI-first engineering, with guardrails.** Spec-driven development with agents, TDD loops with clear exit criteria, defense in depth (deterministic hooks, least-privilege service accounts, read-only production access) and a human on every merge and deploy.

**Reliability you can measure.** Load tests before optimizing, alerts and dashboards as code, and incident monitoring that summarizes production by severity.

---

## Selected work

The code is employer-owned, so these are described, not linked. Happy to walk through any of them in a call.

| Project | What it demonstrates | Stack |
| --- | --- | --- |
| **AI development toolkit** | Spec → plan → TDD → review → QA → showcase → deploy, one skill per stage. Rolled out to ~50 developers through a hook; foundation for an autonomous QA agent that runs tests in isolated Kubernetes jobs and made manual QA the exception. 30+ shared skills. | Claude Code, MCP, Kubernetes, Jira |
| **Monolith → event-driven platform** | Incremental migration (Strangler Fig) of the product's most critical module. Debezium reads each legacy database's WAL; Kafka Streams acts as an anti-corruption layer; composite keys and upserts make replays safe; two-layer reconciliation triggers Debezium incremental snapshots. Real-time UI updates with Redis Pub/Sub and WebSocket. | Micronaut, Groovy, Kafka, Debezium, PostgreSQL, Kubernetes |
| **AI-first observability** | k6 load tests to find bottlenecks, SigNoz alerts and dashboards as code, a skill that turns every production incident into a new alert, and a monitor that reports all production environments every 30 minutes. | SigNoz, OpenTelemetry, Prometheus, k6 |
| **Analytics platform** | Continuous ETL from many PostgreSQL databases into Elasticsearch, APM-driven query tuning, a data catalog, an approval workflow for reports, and a batch export engine. Proposed the move to a columnar OLAP database (ClickHouse). | Spring Batch, Elasticsearch, Elastic APM, Angular |

---

## How I work

- **Start from the problem.** Who it hurts, what it costs, and how we'll know it's solved.
- **Evolve, don't rewrite.** Old and new systems run side by side until the switch is safe.
- **Measure before optimizing.** Traces, profiling and load tests decide where effort goes.
- **Make failure cheap.** Idempotency turns retries and false positives into non-events.
- **AI amplifies discipline, it doesn't replace it.** Good specs, good tests, a human in the loop.

---

## Stack

**Languages:** Java, Groovy, Kotlin, TypeScript, SQL, Python  
**Back-end:** Micronaut, Spring Boot, Grails, Hibernate/JPA, REST, reactive programming  
**Data & messaging:** Kafka, Kafka Streams, Debezium, PostgreSQL, Elasticsearch, Redis  
**Infrastructure:** Kubernetes, Docker, Helm, ArgoCD, Jenkins, Ansible  
**Observability:** SigNoz, OpenTelemetry, Prometheus, Grafana, Elastic APM, k6  
**AI:** Claude Code (agents, skills, hooks, harness and loop engineering), MCP servers

## Interests

Software architecture, distributed systems, data engineering, serverless, and the responsible use of AI agents in production. Also calculus and theory of computation.

## Education

B.Eng. Computer Engineering, Pontifícia Universidade Católica de Goiás · Undergraduate research (PIBIC/CNPq) on palm-vein biometrics with PCA and KNN

From university: a [compiler](https://github.com/yanlobianchi/Compiler), a [Bison calculator interpreter](https://github.com/yanlobianchi/interpreter-bison-calc), and distributed-systems coursework with [sockets](https://github.com/yanlobianchi/sistemas-distribuidos.vacina-socket) and [REST](https://github.com/yanlobianchi/sistemasdistribuidos.restapi).
