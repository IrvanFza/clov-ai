# Contributing to CLOV

Thanks for helping make CLOV more reliable for AI-assisted development.

## Before opening an issue

- Search existing issues and the [troubleshooting guide](docs/TROUBLESHOOTING.md).
- Use the latest release and include `clov --version`.
- Remove secrets, private prompts, tokens, and sensitive tool output from reports.

## Pull requests

1. Open an issue first for substantial behavior changes.
2. Keep each PR focused and explain the user-visible impact.
3. Add or update tests when behavior changes.
4. Run `cargo test` and `cargo clippy -- -D warnings` before requesting review.
5. Update documentation, examples, or the changelog when relevant.

## Scope

CLOV prioritizes safe, local-first filtering for MCP responses and terminal output. Changes should preserve transparent behavior, avoid silently discarding high-signal data, and keep the default experience dependency-light.

## Security

Do not report vulnerabilities in public issues. Follow [SECURITY.md](SECURITY.md) instead.
