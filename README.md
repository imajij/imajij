# Hi, I'm Ajij Uttam

CS undergrad at **BITS Pilani × Scaler School of Technology** (combined B.Sc.,
graduating Aug 2028), based in Bengaluru. I build backends and the
infrastructure that runs them.

**Looking for:** Backend · Full-Stack · Mobile · DevOps · Forward Deployed
Engineer internships.

[ajij.dev](https://ajij.dev) · [LinkedIn](https://www.linkedin.com/in/ajij-uttam) · [ajijuttam2006@gmail.com](mailto:ajijuttam2006@gmail.com)

## Now

- **Symbiotes MarTech** — backend + DevOps. TypeScript / Fastify / Next.js /
  tRPC / Postgres. Migrated services to ECS Fargate, built GitHub Actions
  CI/CD, and worked on multi-tenant isolation.
- **Pipecode.AI** — SDE intern, building internal tooling.

## Open source

[dora-rs/dora](https://github.com/dora-rs/dora) — Rust dataflow framework for robotics. Merged:

- [#2039](https://github.com/dora-rs/dora/pull/2039) — daemon retries
  reconnecting to the coordinator within a bounded window instead of exiting
  on the first refusal.
- [#2026](https://github.com/dora-rs/dora/pull/2026) — Arrow round-trip tests
  for the MAVLink2 bridge's write path.

## Projects

| Project | Stack | What it is |
|:--|:--|:--|
| [typeahead](https://github.com/imajij/typeahead) | Rust, Axum, Tokio, SQLite | Autocomplete backend: in-memory trie with per-node top-K, mid-word and typo-tolerant (Damerau-Levenshtein) matching, batched writes, TF-IDF × PageRank document search. Tests, criterion benchmarks, CI. |
| [intern-wire](https://github.com/imajij/intern-wire) | Python, FastAPI, SQLite/MongoDB, GitHub Actions | Internship aggregator scraping public LinkedIn and X pages; scheduled scrape + GitHub Pages deploy, URL dedup, stale-listing purge, token-gated admin. |
| Zest backend *(private)* | Rust, Axum | Rust/Axum backend for a mobile app. |
| render-farm *(private)* | Next.js, TypeScript, Postgres | Video-generation job platform. |

## Stack

**Languages:** Rust, TypeScript, Python, Go, Dart (Flutter)  
**Backend:** Axum, Tokio, Fastify, tRPC, FastAPI, Node.js, Next.js  
**Data:** PostgreSQL, SQLite, MongoDB, Redis  
**Infra:** AWS (ECS Fargate), Docker, GitHub Actions, Linux  
