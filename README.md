# Abdelrhman Shalby
Senior Backend Engineer (Laravel, Node.js). I build systems that stay correct under load: payments, ledgers, orders, real-time traffic.

- Now: sole developer of an insurance-brokerage platform (Laravel + Flutter) at DTS Group.
- Before: founded Codeivity (2021 to 2026) and led 7 engineers. Highlights: a multi-vendor logistics platform whose real-time backend I designed and load-tested for 30,000+ concurrent users, and a live POS and crypto ledger.

## Proof repos
| Repo | What it proves |
|---|---|
| [insurance-policy-copilot](https://github.com/AbdouShalby/insurance-policy-copilot) | AI copilot deployed the way a forward-deployed engineer would: cited answers in Arabic and English, signed and idempotent CRM webhook, eval gate in CI ([2-min demo](https://github.com/AbdouShalby/insurance-policy-copilot#demo-video)) |
| [laravel-flutter-payments-patterns](https://github.com/AbdouShalby/laravel-flutter-payments-patterns) | Idempotent payments, signed webhooks, forward-only states, safe retries (Laravel + Flutter) |
| [Distributed-Order-Processing-System](https://github.com/AbdouShalby/Distributed-Order-Processing-System) | No overselling under concurrent orders: Redis locks + MySQL row locks |
| [Durable-Agent-Workflow-Platform](https://github.com/AbdouShalby/Durable-Agent-Workflow-Platform) | Idempotent requests, leased and fenced workers, durable approvals (TypeScript, PostgreSQL) |
| [Distributed-Locking-Deep-Dive-Lab](https://github.com/AbdouShalby/Distributed-Locking-Deep-Dive-Lab) | Lock failure modes: deadlocks, TTL expiry, retries |
| [WebSocket-Scaling-Lab](https://github.com/AbdouShalby/WebSocket-Scaling-Lab) | Horizontal WebSocket fan-out with Redis Pub/Sub, backpressure, graceful drain |
| [Backend-Architecture-Case-Studies](https://github.com/AbdouShalby/Backend-Architecture-Case-Studies) | System design reasoning with capacity and cost estimates |

## How I work with AI
I use Claude Code, Codex and Cursor every day, the way I'd expect a team to use them at a client:
- I own the problem, the design and the acceptance criteria, written down before any code.
- AI agents do most of the implementation against those written tasks.
- I review every change and verify it with tests and evaluations before it ships.

Each repo has a short "How this was built" note saying which tools did what.

## Stack
Laravel, PHP 8, Node.js, NestJS, TypeScript, Python (FastAPI), Flutter, Vue.js, MySQL, PostgreSQL, Redis, AWS (ECS, S3, CloudFront), Docker, Nginx, GitHub Actions.

Contact: abdoushalby@gmail.com | linkedin.com/in/abdelrhman-shalby
