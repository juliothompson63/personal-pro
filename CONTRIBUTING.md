# Contributing

Thank you for considering a contribution to Personal Pro.

## Before starting

1. Open an issue describing the bug or proposed improvement.
2. Check existing issues and pull requests to avoid duplicated work.
3. For substantial changes, discuss the approach before implementation.

## Development setup

Requirements: Node.js 20 or newer and pnpm.

```bash
pnpm install
pnpm dev
```

Create a local `.env.local` only when testing Supabase integration. Never commit credentials, access tokens, service-role keys, or real user data.

## Pull requests

- Keep changes focused and explain the user problem they solve.
- Include clear steps to reproduce and verify the change.
- Run `pnpm build` before opening a pull request.
- Update documentation when behavior or setup changes.
- Use screenshots for meaningful interface changes when practical.

## Reporting security issues

Do not publish secrets or exploitable vulnerabilities in public issues. Follow [SECURITY.md](SECURITY.md).
