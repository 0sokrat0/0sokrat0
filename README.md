# Daniel

**Backend Go engineer working on payment systems, service discovery, and operational automation.**

I build Go backend systems around money, state, and failure: PSP/P2P-style workflows, service-owned data, command/query/event contracts, idempotency, reconciliation, observability, and production support.

Most of my recent work is private or NDA-bound, so this profile describes engineering capabilities and problem classes rather than private repositories or product names.

## What I build

- **Payment backend systems:** transaction lifecycle, payment status flows, merchant/provider boundaries, account and balance state, ledger/accounting logic, dispute-support workflows, reconciliation seams.
- **Microservice architecture:** internal discovery/capability routing, service-owned schemas, stable command/query/provider contracts, monolith-to-service migration paths, Clean Architecture, DDD-style boundaries.
- **Event-driven workflows:** EDA/CQRS, domain events, background workers, consumers/projectors, analytics read models, webhook delivery, Telegram/operator notifications, retryable async processing.
- **Production reliability:** idempotency, duplicate-request safety, retries, timeouts, cancellation, audit logs, health checks, metrics, tracing, rollback and recovery paths.
- **Delivery discipline:** SDD-style design notes, API contracts, data models, state transitions, invariants, edge cases, verification plans, code review, integration/API/E2E testing.
- **Operational AI:** internal automation with LLM agents, MCP/tool boundaries, structured outputs, approval gates, auditability, and evaluation loops.

## Technical focus

| Area | Focus |
| --- | --- |
| Backend | Go, REST/gRPC APIs, workers, service boundaries, error handling, concurrency |
| Payments | PSP/P2P workflows, pay-in/pay-out paths, webhooks, ledger state, reconciliation |
| Data | PostgreSQL, SQL, MVCC, transactions, locking, indexing, migrations, Redis |
| Architecture | Microservices, Clean Architecture, DDD-style modules, EDA, CQRS, service discovery |
| Reliability | Idempotency, retries, timeouts, queues/events, partial failure, observability |
| Platform | Docker, Kubernetes/GitOps, GitLab CI, Linux, Prometheus/Grafana |
| AI engineering | Agents, MCP/tool integrations, least privilege, approval gates, evals |

## Engineering principles

- A payment flow is not finished because an API returned `200`; it is finished when the business state can be trusted, reconciled, and explained.
- A service boundary is useful only when it protects ownership, contracts, and failure modes. Otherwise it is just distributed spaghetti with a YAML addiction.
- Clean Architecture, DDD, EDA, and SDD are tools for making business rules explicit, not stickers to paste on a CRUD app.
- Idempotency, retries, timeouts, and cancellation are system contracts, not middleware decoration.
- Observability should answer support, finance, and recovery questions, not just make dashboards green.
- Simple, reversible designs beat clever machinery that only one person can debug at 03:00.

## Currently sharpening

- Senior-level Go/backend system design and production debugging.
- Payment-system correctness: lifecycle states, duplicate prevention, reconciliation, provider failures, audit trails.
- PostgreSQL/MVCC, transaction boundaries, locking behavior, indexing, and migrations.
- Contract-first APIs, integration tests, E2E tests, and evaluation-driven AI workflows.

## Public boundary

Client, employer, product, repository, infrastructure, metric, endpoint, customer, and incident details stay private. I describe the engineering shape of the work, not confidential systems.
