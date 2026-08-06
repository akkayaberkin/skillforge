# SkillForge

Production-ready AI skill files. Drop-in instruction sets that make coding agents sharper, faster, and more reliable.

## What's a Skill?

A skill file is a focused instruction set for a specific domain or task. It tells an AI agent:

- **What to care about** — priorities, constraints, gotchas
- **What to ignore** — noise, anti-patterns, time-wasters
- **How to respond** — concise, code-first, zero fluff

Each skill is one `.md` file. No frameworks. No dependencies. Just paste and use.

## Skills

| Skill | Purpose |
|-------|---------|
| [`debugging.md`](skills/debugging.md) | Systematic bug diagnosis and root cause analysis |
| [`security-audit.md`](skills/security-audit.md) | Vulnerability scanning and secure code review |
| [`api-design.md`](skills/api-design.md) | REST/GraphQL API design and implementation |
| [`database.md`](skills/database.md) | Schema design, queries, migrations, optimization |
| [`testing.md`](skills/testing.md) | Test strategy, coverage, and quality |
| [`devops.md`](skills/devops.md) | CI/CD, containers, infrastructure |
| [`frontend.md`](skills/frontend.md) | UI/UX implementation and component architecture |
| [`performance.md`](skills/performance.md) | Profiling, optimization, scalability |
| [`code-review.md`](skills/code-review.md) | Review patterns, anti-patterns, and standards |
| [`refactoring.md`](skills/refactoring.md) | Safe code transformation and debt reduction |
| [`medical-software.md`](skills/medical-software.md) | Healthcare software: HIPAA, FDA, compliance |
| [`fintech.md`](skills/fintech.md) | Financial software: transactions, compliance, precision |
| [`auth.md`](skills/auth.md) | Authentication, authorization, session management |
| [`mobile.md`](skills/mobile.md) | React Native / Flutter / native mobile development |
| [`microservices.md`](skills/microservices.md) | Distributed systems, service boundaries, messaging |
| [`error-handling.md`](skills/error-handling.md) | Exception hierarchies, retries, circuit breakers, graceful degradation |
| [`logging.md`](skills/logging.md) | Structured logging, log levels, correlation IDs, observability |
| [`caching.md`](skills/caching.md) | Redis, CDN, HTTP caching, invalidation strategies, hit rate optimization |
| [`search.md`](skills/search.md) | Elasticsearch, full-text search, ranking, filtering, autocomplete |
| [`realtime.md`](skills/realtime.md) | WebSockets, SSE, pub/sub, presence, conflict resolution |
| [`file-handling.md`](skills/file-handling.md) | Upload/download, storage backends, streaming, virus scanning, image processing |
| [`i18n.md`](skills/i18n.md) | Internationalization, localization, RTL support, date/number formatting, pluralization |
| [`monitoring.md`](skills/monitoring.md) | Alerting, SLO/SLA, dashboards, anomaly detection, incident response |
| [`documentation.md`](skills/documentation.md) | API docs, ADRs, runbooks, README structure, changelogs |
| [`networking.md`](skills/networking.md) | HTTP/2, gRPC, TCP optimization, DNS, load balancing, rate limiting |
| [`data-pipeline.md`](skills/data-pipeline.md) | ETL, stream processing, batch jobs, data quality, schema evolution |
| [`gamedev.md`](skills/gamedev.md) | Game loops, physics, rendering, state sync, optimization |
| [`iot.md`](skills/iot.md) | MQTT, edge computing, device management, telemetry, firmware updates |
| [`blockchain.md`](skills/blockchain.md) | Smart contracts, wallet integration, transaction handling, gas optimization |
| [`ml-ops.md`](skills/ml-ops.md) | Model serving, feature stores, training pipelines, A/B testing, data versioning |
| [`accessibility.md`](skills/accessibility.md) | WCAG compliance, screen readers, keyboard navigation, ARIA, color contrast |
| [`email.md`](skills/email.md) | SMTP, templates, delivery tracking, spam prevention, bounce handling |
| [`queue-systems.md`](skills/queue-systems.md) | RabbitMQ, Kafka, SQS, dead letter queues, idempotency, exactly-once processing |

> New skills added regularly.

## Usage

1. Copy the skill file content
2. Paste it into your AI agent's system prompt or instruction file
3. Done. The agent now has domain expertise.

Or use the raw URL directly:

```
https://raw.githubusercontent.com/akkayaberkin/skillforge/main/skills/debugging.md
```

## Skill Format

Every skill follows the same structure:

```markdown
# Skill Name

## Role
What the agent becomes when this skill is active.

## Rules
Hard constraints. Never violate these.

## Priority Order
What matters most → least.

## Common Mistakes
What to avoid and why.

## Output Style
How responses should look.

## Quick Reference
Cheat sheet for the domain.
```

## Contributing

Skills are generated and curated. If you have a domain expertise skill to add, open a PR.

## License

MIT
