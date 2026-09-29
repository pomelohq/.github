<p align="center">
  <img src="https://raw.githubusercontent.com/pomelohq/pomelo/main/.github/assets/logo.png" width="120" height="120" alt="Pomelo">
</p>

<h1 align="center">Pomelo</h1>

<p align="center">
  Every branch gets its own running stack.<br>
  A native macOS app for multi-repo projects. Free and open source.
</p>

<p align="center">
  <a href="https://github.com/pomelohq/pomelo/releases/latest"><img src="https://img.shields.io/github/v/release/pomelohq/pomelo" alt="Release"></a>
  <a href="https://www.gnu.org/licenses/agpl-3.0"><img src="https://img.shields.io/badge/License-AGPL_v3-blue.svg" alt="License: AGPL v3"></a>
  <a href="https://github.com/pomelohq/pomelo/releases/latest"><img src="https://img.shields.io/badge/platform-macOS%2014%2B%20%7C%20Apple%20Silicon-lightgrey.svg" alt="Platform: macOS"></a>
  <a href="https://pomelohq.app"><img src="https://img.shields.io/badge/docs-pomelohq.app-d9b45b.svg" alt="Docs"></a>
</p>

<p align="center">
  <a href="https://pomelohq.app/#film"><img src="assets/film-poster.jpg" width="820" alt="Watch the Pomelo film (74 seconds)"></a>
  <br>
  <sub><a href="https://pomelohq.app/#film">Watch the film (1:14)</a></sub>
</p>

Your agents finished three branches. Now run them: port 3000 is taken, one migration breaks the other
branch, and you are back to stop, stash, switch, re-seed.

Pomelo gives every branch of a multi-repo project its own running environment, side by side: its own git
worktrees, ports, databases and address, next to a code editor, terminals and your AI agent.

- **Website and docs:** https://pomelohq.app
- **Download (macOS):** https://github.com/pomelohq/pomelo/releases/latest
- **Source:** https://github.com/pomelohq/pomelo

## What it does

- **One running stack per branch.** Worktrees for every repo, its own ports and databases seeded from main.
  Branches never collide, and switching restarts nothing.
- **Services that say what broke.** Each service shows its state and the last line it printed; a port clash
  moves to a free port in one click.
- **Agents in the loop.** Hand a crash to Claude with the error attached. Through Pomelo's tools it reads that
  branch's own logs and database.
- **Review and ship across repos.** One message, one commit per repo, push, and the pull request's checks show
  on the workspace.
- **Native and self-contained.** One Rust app with a GPU-drawn UI and the core built in: no daemon, no local
  server, notarized, updates itself.

Open source, AGPL-3.0.
