# OpenCode

The open source AI coding agent.

## Installation

```bash
# YOLO
curl -fsSL https://opencode.ai/v2/install | bash

# Package managers
npm i -g @opencode/cli@latest
brew install anomalyco/tap/opencode-v2
```

## Quick Start

```bash
bun install
bun run --cwd packages/cli src/index.ts
```

## Web UI

```bash
bun run --cwd packages/app dev
```

Authentication (API keys) is handled by you via `opencode auth login`.

License: MIT