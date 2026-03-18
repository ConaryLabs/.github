## Systems software in Rust.

Built by [Peter Permenter](https://github.com/TusanHomichi) — a systems engineer focused on package management, backend architecture, and Linux internals.

### Projects

🔧 **[Conary](https://github.com/ConaryLabs/Conary)** — Cross-distribution Linux package manager\
SAT-based dependency resolution, content-addressable storage, hermetic builds, and immutable system generations via EROFS + composefs. 190K+ lines of Rust, 2,600+ unit tests, 249 integration tests across Fedora, Ubuntu, and Arch. Production server at [packages.conary.io](https://packages.conary.io) converting 68,000+ upstream packages on the fly.

📋 **[Timeshift](https://github.com/ConaryLabs/Timeshift)** — Shift scheduling for 911 dispatch centers\
Full-stack Rust/Axum + React/TypeScript. Multi-tenant PostgreSQL with seniority-based overtime queues, union contract rules, multi-round vacation bidding, and 26 leave types. Built from domain expertise at Valley Communications Center (King County, WA — 14 cities).

🧠 **[Mira](https://github.com/ConaryLabs/Mira)** — AI code intelligence MCP server\
Persistent memory and semantic code search for Claude Code via Tree-sitter and SQLite. Archived after core features were adopted natively by upstream platforms.

### Stack

Rust · Axum · Tokio · SQLite · PostgreSQL · React · TypeScript · Linux · EROFS · Ed25519 · Tree-sitter
