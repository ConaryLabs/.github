## Systems software in Rust.

Built by [Peter Permenter](https://github.com/TusanHomichi) — a systems engineer focused on package management, backend architecture, and Linux internals.

### Projects

**[Conary](https://github.com/ConaryLabs/Conary)** — Early Linux package-manager preview

Conary is an adoption-led Rust package manager for Fedora 44, Ubuntu 26.04 LTS, and Arch Linux on x86_64. It can install converted packages, track packages already owned by the native package manager, and unadopt them without silently taking authority. The current public test is deliberately limited to disposable, snapshotted, or non-critical hosts.

The maintainer-operated [Remi service](https://remi.conary.io) converts supported upstream packages on demand. Package conversion and scriptlet support are still conservative preview surfaces, not production-service claims.

**[Timeshift](https://github.com/ConaryLabs/Timeshift)** — Shift scheduling for 911 dispatch centers

Full-stack Rust/Axum + React/TypeScript. Multi-tenant PostgreSQL with seniority-based overtime queues, union contract rules, multi-round vacation bidding, and leave management.

**[Mira](https://github.com/ConaryLabs/Mira)** — AI code intelligence MCP server

Persistent memory and semantic code search via Tree-sitter and SQLite. Archived after core features were adopted natively by upstream platforms.

### Stack

Rust · Axum · Tokio · SQLite · PostgreSQL · React · TypeScript · Linux · EROFS · Ed25519 · Tree-sitter
