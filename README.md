# Spin Starter

**Spin Starter** is set of pre-configured [Dev Containers](https://containers.dev/) to help you getting started with the [Spin Framework](https://spinframework.dev).

## What's Included

The **Spin Starter** Dev Containers come with support for building Spin applications using these programming languages:

- JavaScript & TypeScript
- Go (using TinyGo)
- Rust
- Python

The latest stable release of `spin` CLI is installed and the following plugins are ready to use:

- `cloud`
- `aka`
- `kube`

## Using the Dev Containers

This repo provides multiple dev container definitions under `.devcontainer/`:

- `.devcontainer/all-in-one` – All-in-one: Spin + Rust + (Tiny)Go + JS/TS + Python
- `.devcontainer/rust` – Rust + Spin
- `.devcontainer/go` – (Tiny)Go + Spin
- `.devcontainer/js/ts` – JavaScript/TypeScript + Spin
- `.devcontainer/python` – Python + Spin

When opening this repo in VS Code or GitHub Codespaces:

1. Open the command palette → **Dev Containers: Rebuild and Reopen in Container**
2. When asked to **Select a dev container configuration**, choose the one you want.

*Choosing a Dev Container configuration is also possible when creating a GitHub Codespace. Check the context menu and use the 'NEW WITH OPTIONS...' command in GitHub WebUI.*
