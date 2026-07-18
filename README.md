# secrets-precommit

> Block committed secrets before they ever hit history.

**Status:** 🚧 In development

## Overview

Pre-commit bundle wiring gitleaks and trufflehog with sensible defaults.

## Features

- One-line pre-commit config for gitleaks + trufflehog
- Curated allowlist to cut false positives
- Baseline for existing repos (accept-known)
- CI job mirroring the local hook
- Docs for onboarding a repo

## Stack

pre-commit + gitleaks + trufflehog.

## Usage

```yaml
# .pre-commit-config.yaml
- repo: https://github.com/cybercapybara/secrets-precommit
  rev: v1
```

## License

MIT
