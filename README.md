> ⚠️ **Consolidated into [shesh-core](https://github.com/gaganjainse/shesh-core)** — this module now lives in the shesh-core monorepo (same package name, same console script). Archived 2026-08-13.

# 🔐 shesh-secrets

Resolve secrets from **env**, **gopass**, **KeePassXC** (secret-service), or
**0600 files** — secrets are never stored in MCP config. Reference format:
`env:VAR`, `gopass:path`, `keepassxc:attr=value`, `file:/path`.

- License: GPL-3.0
- Layer: Brain
- Part of: [Shesh ecosystem](https://github.com/gaganjainse/shesh-ecosystem)

## MCP tools
`get_secret(reference)`, `resolve_config(mapping)`

## Develop
```bash
uv run pytest -q && uv run ruff check . && uv run shesh-secrets-mcp
```

## Security

Security posture and vulnerability reporting: [canonical ecosystem security
policy](https://github.com/gaganjainse/shesh-ecosystem/blob/main/SECURITY.md).
