# Mihai Builds

Building open-source developer tools. Local-first, self-hosted, no cloud lock-in.

## Currently shipping

**[Memory Vault](https://github.com/MihaiBuilds/memory-vault)** — A memory layer for LLMs. Postgres + pgvector, hybrid search, MCP integration for Claude. One `docker compose up`, runs entirely on your machine. **v1.0 released 2026-05-07.**

```bash
docker pull ghcr.io/mihaibuilds/memory-vault:latest
```

**[The Brain](https://github.com/MihaiBuilds/the-brain)** — A workflow orchestrator for the MihaiBuilds ecosystem. Python-defined workflows with shell, LLM, Memory Vault, and MCP steps; manual / cron / webhook / file triggers; Postgres-backed state; multi-arch Docker. **v1.0 released 2026-06-15.**

```bash
docker pull ghcr.io/mihaibuilds/the-brain:latest
```

## Principles

- **Local-first** — your data stays on your hardware
- **Self-hosted** — no SaaS lock-in, no telemetry
- **Open source** — MIT licensed, fork it, change it, ship it
- **Boring tech** — Postgres, Python, Docker. No magic.

## Links

- Website: [mihaibuilds.com](https://mihaibuilds.com)
- Blog: [mihaibuilds.com/blog](https://mihaibuilds.com/blog)
- Building in public on [X](https://x.com/MihaiBuilds) and [Reddit](https://reddit.com/user/MihaiBuilds)
