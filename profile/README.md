# Pomelo

A native macOS app that spins up a full, isolated, runnable dev environment for
every branch — services, databases, and shared infra, wired automatically.
No YAML archaeology, no port juggling.

- Website: https://pomelohq.app
- Documentation: https://pomelohq.app/docs/install
- Download (macOS): https://github.com/pomelohq/pomelo/releases/latest
- Source: https://github.com/pomelohq/pomelo

## What it does

- **One full stack per branch** — its own worktree, services, databases, and
  ports. Two branches never collide.
- **Golden main, cloned in seconds** — databases via `CREATE DATABASE … TEMPLATE`,
  `node_modules` via APFS copy-on-write.
- **Native services first** — real processes (nvm, rbenv, …); Docker reserved for
  data and infra. Lighter than running everything in containers.
- **Databases in the app** — browse and query per-branch Postgres and Redis; your
  agent can too, over MCP.
- **Swift, not Electron** — 120fps, portless (Go core over FFI), notarized.

Open source, AGPL-3.0.
