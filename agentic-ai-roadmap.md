# Agentic AI Engineering Roadmap

November 23, 2026 – May 9, 2027 | 24 weeks | 6 hours/week (proposed).

TypeScript-first. Node.js, Fastify, Zod, Vitest; introduce Python only where justified. All repository material in English. Advanced project selection after week 9; optional second project after week 16. Holiday weeks may be used as catch-up; dates are adjustable.

## Weekly rhythm

- Monday 21:00–22:30: theory, design, acceptance criteria.
- Thursday 21:00–22:30: implementation.
- Saturday 09:00–12:00: integration, tests, review and publication.

## Sprint backlog

| Week | Dates | Project | Outcome |
|---|---|---|---|
| 1 | 23 Nov 2026 – 29 Nov 2026 | Gateway | Provider abstraction, async API, Zod validation, first completion |
| 2 | 30 Nov 2026 – 06 Dec 2026 | Gateway | Streaming, parallel requests, timeout, retry, cancellation |
| 3 | 07 Dec 2026 – 13 Dec 2026 | Gateway | Model routing, cost tracking, fallback, benchmarks, release |
| 4 | 14 Dec 2026 – 20 Dec 2026 | Issue Agent | GitHub read-only tools, schemas, structured plans |
| 5 | 21 Dec 2026 – 27 Dec 2026 | Issue Agent | Native agent loop, ReAct, bounded execution, error recovery |
| 6 | 28 Dec 2026 – 03 Jan 2027 | Issue Agent | MCP discovery, prompt injection tests, release |
| 7 | 04 Jan 2027 – 10 Jan 2027 | Knowledge Agent | Ingestion, embeddings, pgvector, retrieval with citations |
| 8 | 11 Jan 2027 – 17 Jan 2027 | Knowledge Agent | Session state, persistent memory, provenance, deletion |
| 9 | 18 Jan 2027 – 24 Jan 2027 | Knowledge Agent | Context compression, retrieval evals, release, capstone decision |
| 10 | 25 Jan 2027 – 31 Jan 2027 | Advanced project | Product specification, baseline, test environment |
| 11 | 01 Feb 2027 – 07 Feb 2027 | Advanced project | Single-agent baseline and tool integration |
| 12 | 08 Feb 2027 – 14 Feb 2027 | Advanced project | State graph, checkpoints, resumability |
| 13 | 15 Feb 2027 – 21 Feb 2027 | Advanced project | Supervisor, handoffs, parallel agents, conflict resolution |
| 14 | 22 Feb 2027 – 28 Feb 2027 | Advanced project | Human approval, audit trail, idempotency |
| 15 | 01 Mar 2027 – 07 Mar 2027 | Advanced project | Evaluation dataset, regression and judge validation |
| 16 | 08 Mar 2027 – 14 Mar 2027 | Advanced project | Tracing, cost and latency monitoring, MVP review |
| 17 | 15 Mar 2027 – 21 Mar 2027 | Capstone extension / optional project | Decision: deepen capstone or second product; scope and specs |
| 18 | 22 Mar 2027 – 28 Mar 2027 | Capstone extension / optional project | Security: permissions, injection, PII redaction |
| 19 | 29 Mar 2027 – 04 Apr 2027 | Capstone extension / optional project | Sandbox, execution budgets, failure recovery |
| 20 | 05 Apr 2027 – 11 Apr 2027 | Capstone extension / optional project | Workers, queues, persistence, concurrency |
| 21 | 12 Apr 2027 – 18 Apr 2027 | Capstone extension / optional project | Load tests, deployment pipeline, canary and rollback |
| 22 | 19 Apr 2027 – 25 Apr 2027 | Capstone extension / optional project | Local inference experiment; release candidate |
| 23 | 26 Apr 2027 – 02 May 2027 | Production & Portfolio | Deployment, operational runbook, end-to-end evals |
| 24 | 03 May 2027 – 09 May 2027 | Production & Portfolio | Final releases, architecture docs, demos, portfolio and OSS contribution |

## Definition of done

- Working example with documented setup and reproducible commands.
- Acceptance criteria verified by automated tests; relevant failure cases covered.
- CI green, no secrets or private data committed.
- README explains design trade-offs; ADR when a meaningful decision is made.
- Measure cost, latency and quality where applicable; report actual results.
- Explain the implementation without relying on the coding assistant.

## Decision gates

- Week 3: Gateway v0.1 with two providers and benchmark.
- Week 6: Issue Agent v0.1 with a bounded, read-only agent loop and MCP.
- Week 9: Knowledge Agent v0.1 with persistent state and retrieval evaluation; select advanced project.
- Week 16: advanced MVP; decide whether to deepen it or start a small second product.
- Week 24: public portfolio release. Kubernetes and vLLM/SGLang are optional experiments, not production requirements.

## Advanced project candidates

Production Incident Investigator (preferred technical candidate), Autonomous Business Assistant, or another project justified against the remaining skill matrix. No commitment to a separate Agentic Dev Team.

## Weekly workflow

Create issue/spec → implement → review → test/evaluate → document → publish. Use Codex as a collaborator, but retain ownership of architecture and verification.
