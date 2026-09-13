# Contributing

Thank you for helping improve this portfolio site.

## Before You Start

- Open an issue for significant content, design, or build changes.
- Keep personal information, credentials, and private project data out of commits.
- Do not add proprietary source code or confidential company material.

## Local Development

Requirements: Hugo Extended `0.162.0`, Go `1.21+`, Node `22`, and `pnpm`.

```bash
pnpm install
hugo server -D
```

Build the production site with:

```bash
hugo --gc --minify
```

## Pull Requests

- Use a focused branch and a descriptive title.
- Explain what changed and why.
- Include screenshots for visual changes.
- Run the Hugo production build before opening the pull request.
- Keep generated output, secrets, and unrelated formatting changes out of the pull request.

By contributing, you agree that your work can be distributed under the project license.
