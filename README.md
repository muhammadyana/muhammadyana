# Muhammad Yana Mulyana

**Senior Engineer at [NinjaOne](https://www.ninjaone.com)** · Healthcare platform engineering at
[Hermina](https://github.com/herminadev) · Bandung, Indonesia

Backend and platform engineer working across Ruby on Rails, Go, and Python services in
production healthcare and IT-operations environments. Alongside product work, I build the
retrieval and memory infrastructure that makes AI-assisted development reliable at
multi-repository scale.

[muhammadyana.me](https://muhammadyana.me)

---

## Focus areas

**Platform engineering.** Service backends on Ruby on Rails 8 and Go with the Kratos framework,
paired with React, Next.js, and React Native clients. PostgreSQL, Kubernetes, and AWS underneath.

**Tooling for AI-assisted engineering.** Context and retrieval infrastructure for coding agents:
cross-agent session memory, code knowledge graphs, and MCP servers. The premise is that agent
quality is bounded by the context you can supply, which makes context an engineering concern
rather than a prompting one.

---

## Engineering tooling

**agent-memory** — A cross-agent memory layer. It ingests session history from six coding agents
(Claude Code, Codex, OpenCode, Kimi CLI, DeepSeek, Copilot), normalizes it, resolves each session
to its originating repository, and indexes the result in PostgreSQL with pgvector alongside a
human-readable Obsidian vault. Hybrid retrieval is exposed through a CLI and an MCP server so
every agent operates from shared memory. Over 1,700 sessions indexed to date.
Python, Typer, SQLAlchemy, Alembic, pgvector.

**Code knowledge graph** — An incrementally updated, Tree-sitter-parsed graph of the codebase,
used for impact-radius analysis, caller and callee tracing, and token-efficient review context.

**[codex-lb](https://github.com/muhammadyana/codex-lb)** — Load balancer and proxy for pooled
ChatGPT and Codex accounts, providing usage tracking, API key management, an operations
dashboard, and OpenCode-compatible endpoints. Python, FastAPI, SQLAlchemy, OAuth.

---

## Technical stack

| Area | Technologies |
| --- | --- |
| Backend | Ruby on Rails, Go (Kratos), Python (FastAPI), Node.js |
| Frontend | React, Next.js, Vite, Ant Design, Tailwind CSS |
| Mobile | React Native, Expo |
| Data | PostgreSQL, pgvector, Redis, Elasticsearch |
| Infrastructure | Docker, Kubernetes, AWS, GitHub Actions |
| AI systems | MCP servers, RAG and hybrid retrieval, multi-agent orchestration |

---

## Activity

<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=muhammadyana&theme=github_dark" alt="Repositories per language" />
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=muhammadyana&theme=github_dark" alt="Most committed language" />
</p>

<p align="center">
  <a href="https://git.io/streak-stats"><img src="https://streak-stats.demolab.com?user=muhammadyana&theme=github-dark-blue&hide_border=true&date_format=M%20j%5B%2C%20Y%5D" alt="GitHub contribution streak" /></a>
</p>

<p align="center">
  <a href="https://wakatime.com/@4fbba004-bd97-43a4-889e-7b9531bfc14e"><img src="https://wakatime.com/badge/user/4fbba004-bd97-43a4-889e-7b9531bfc14e.svg" alt="WakaTime hours tracked" /></a>
</p>
