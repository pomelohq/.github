<p align="center">
  <img src="https://raw.githubusercontent.com/pomelohq/pomelo/main/.github/assets/logo.png" width="120" height="120" alt="Pomelo">
</p>

<h1 align="center">Pomelo</h1>

<p align="center">
  A dev environment. One per branch.<br>
  A native macOS app for multi-repo projects — free and open source.
</p>

<p align="center">
  <a href="https://github.com/pomelohq/pomelo/releases/latest"><img src="https://img.shields.io/github/v/release/pomelohq/pomelo" alt="Release"></a>
  <a href="https://www.gnu.org/licenses/agpl-3.0"><img src="https://img.shields.io/badge/License-AGPL_v3-blue.svg" alt="License: AGPL v3"></a>
  <a href="https://github.com/pomelohq/pomelo/releases/latest"><img src="https://img.shields.io/badge/platform-macOS%2014%2B%20·%20Apple%20Silicon-lightgrey.svg" alt="Platform: macOS"></a>
  <a href="https://pomelohq.app"><img src="https://img.shields.io/badge/docs-pomelohq.app-d9b45b.svg" alt="Docs"></a>
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/pomelohq/pomelo/main/.github/assets/app.png" width="820" alt="Pomelo — a full, isolated dev environment for every branch">
</p>

A native macOS app that spins up a full, isolated, runnable dev environment for
every branch — services, databases, and shared infra, wired automatically.
No YAML archaeology, no port juggling.

- **Website** — https://pomelohq.app
- **Documentation** — https://pomelohq.app
- **Download (macOS)** — https://github.com/pomelohq/pomelo/releases/latest
- **Source** — https://github.com/pomelohq/pomelo

## What it does

- **One full stack per branch** — its own worktree, services, databases, and
  ports. Two branches never collide.
- **Golden main, cloned in seconds** — databases via `CREATE DATABASE … TEMPLATE`,
  `node_modules` via APFS copy-on-write.
- **Native services first** — real processes (nvm, rbenv, …); Docker reserved for
  data and infra. Lighter than running everything in containers.
- **Same-origin networking** — a built-in dev-proxy serves a frontend and its
  backends under one origin (no CORS); a webhook relay fans events out to every
  branch.
- **Databases in the app** — browse and query per-branch Postgres and Redis; your
  agent can too, over MCP.
- **Swift, not Electron** — built for ProMotion, portless (Go core over FFI),
  notarized.

Open source, AGPL-3.0.
