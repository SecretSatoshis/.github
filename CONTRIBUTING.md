# Contributing to Secret Satoshis

Thank you for helping verify and improve Secret Satoshis' open-source research, data pipelines, charts, and web tools.

## How to contribute

1. **Report data or chart discrepancies:** If a metric, chart, or calculation looks off against primary on-chain or market sources, open a **Data or Chart Discrepancy** issue with the page URL, report date, observed value, and primary reference.
2. **Report bugs:** Use the **Bug Report** issue template with clear reproduction steps.
3. **Submit pull requests:** Fork the repository, create a focused branch from `main`, keep changes well-scoped, and run the repository's local lint, typecheck, and test suite before opening a PR.

## Data integrity principles

- **Don't trust. Verify.** Published daily datasets include a `release_manifest.json` with SHA-256 hashes and report dates so anyone can reproduce and audit figures.
- Prefer primary sources and deterministic tests over ad-hoc manual edits.
- Never commit secrets, API keys, credentials, or large generated artifacts unless explicitly required by the repository's publishing design.

## Licensing

Each repository's `LICENSE` file defines the terms for its contents (most public Secret Satoshis repositories are licensed under GPL-3.0). Third-party data remains subject to its respective publishers' terms. Research published by Secret Satoshis is for informational purposes only and is not investment advice.
