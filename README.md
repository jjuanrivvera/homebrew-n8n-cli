# homebrew-n8n-cli

Homebrew tap for [**n8nctl**](https://github.com/jjuanrivvera/n8n-cli) — a portable, single-binary CLI for the [n8n](https://n8n.io) public API.

## Install

```bash
brew install jjuanrivvera/n8n-cli/n8nctl-cli
```

or

```bash
brew tap jjuanrivvera/n8n-cli
brew install n8nctl-cli
```

Then:

```bash
n8nctl init          # connect an instance (stores the API key in your OS keyring)
n8nctl workflows list
```

## What is n8nctl?

A no-Node, multi-instance client for the n8n public REST API: manage workflows,
executions, credentials, tags, variables, projects and users across many
instances, with backup/restore and cross-instance workflow promotion.

See the [main repository](https://github.com/jjuanrivvera/n8n-cli) and the
[documentation site](https://jjuanrivvera.github.io/n8n-cli/).

---

The cask in this tap is updated automatically by
[GoReleaser](https://goreleaser.com) on each release of `n8nctl`.
