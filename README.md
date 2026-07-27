## Muhammad Yana Mulyana

Senior Engineer at [@NinjaOne](https://github.com/NinjaOne), based in Bandung, Indonesia.
I also build healthcare platform services at [@herminadev](https://github.com/herminadev),
along with the tooling that keeps AI-assisted development honest across a large
multi-repository codebase.

- **Currently building:** Rails 8 / Ruby 4 and Go (Kratos) service backends, React + Vite +
  Ant Design and Next.js frontends, Expo / React Native mobile, on PostgreSQL and Kubernetes.
- **Currently exploring:** agentic engineering — multi-agent orchestration, retrieval over
  code knowledge graphs, and local-first memory for coding agents.
- **More about me:** [muhammadyana.me](https://muhammadyana.me)

---

### Working with coding agents

Most of my engineering now runs through coding agents, so I spend a lot of time building the
infrastructure that keeps them coherent:

- **agent-memory** — a cross-agent memory layer. It reads session history from six agents
  (Claude Code, Codex, OpenCode, Kimi CLI, DeepSeek, Copilot), normalizes it, matches every
  session to the repository it belongs to, and indexes it in PostgreSQL + pgvector next to a
  human-readable Obsidian vault. Hybrid retrieval is exposed over a CLI and an MCP server, so
  each agent works from the same memory instead of starting cold. Over 1,700 sessions indexed
  so far. Python, Typer, SQLAlchemy, Alembic, pgvector.
- **Code knowledge graph** — a Tree-sitter-parsed, incrementally updated graph of the codebase
  used for impact radius, caller and callee tracing, and token-efficient review context. Cheaper
  and far more structural than scanning files.
- **[codex-lb](https://github.com/muhammadyana/codex-lb)** — load balancer and proxy for pooled
  ChatGPT / Codex accounts: usage tracking, API key management, a dashboard, and
  OpenCode-compatible endpoints. Python, FastAPI, SQLAlchemy, OAuth.

The consistent lesson: agents are only as good as the context you can hand them, and context
is an engineering problem, not a prompting one.

---


### Toolbox

**Backend** Ruby on Rails, Go (Kratos), Python (FastAPI), Node.js

**Frontend** React, Next.js, Vite, Ant Design, Tailwind

**Mobile** React Native, Expo

**Data** PostgreSQL, pgvector, Redis, Elasticsearch

**Infra** Docker, Kubernetes, AWS, GitHub Actions

**AI** MCP servers, RAG and hybrid retrieval, multi-agent orchestration

---

### Stats

<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=muhammadyana&theme=github_dark" alt="Repositories per language" />
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=muhammadyana&theme=github_dark" alt="Most committed language" />
</p>

<p align="center">
  <a href="https://git.io/streak-stats"><img src="https://streak-stats.demolab.com?user=muhammadyana&theme=github-dark-blue&hide_border=true&date_format=M%20j%5B%2C%20Y%5D" alt="GitHub streak" /></a>
</p>

<p align="center">
  <a href="https://wakatime.com/@4fbba004-bd97-43a4-889e-7b9531bfc14e"><img src="https://wakatime.com/badge/user/4fbba004-bd97-43a4-889e-7b9531bfc14e.svg" alt="WakaTime" /></a>
</p>
