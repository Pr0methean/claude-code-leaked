# Claude Code CLI (Leaked)

This repository contains a leaked copy of the **Claude Code CLI** – the command‑line interface that powers Claude Code, the AI‑assisted coding tool from Claude.ai.

## Project Overview

* **Language**: TypeScript (Node.js / Bun)
* **Build system**: Bun (uses `bun:bundle` for bundling)
* **Core features**:
  * Interactive REPL for running Claude Code sessions
  * Plugin system for extending functionality
  * Remote session support (via `remote/RemoteSessionManager`)
  * Teleport integration for remote workspaces
  * Built‑in analytics and telemetry

## Getting Started [generated and untested]

```bash
# Clone the repository
git clone https://github.com/sheiddy/claude-code-leaked
cd claude-code-leaked

# Install dependencies (Bun is required)
# If you don't have Bun, install it from https://bun.sh
bun install

# Run the CLI
bun run start
```

The CLI exposes a number of commands under the `commands/` directory. Run `bun run help` to see the full list.

## Common Commands

| Command | Description |
|---------|-------------|
| `bun run start` | Launch the interactive REPL |
| `bun run help` | Show available commands |
| `bun run version` | Show CLI version |
| `bun run init` | Generate a `CLAUDE.md` file for the repository |
| `bun run install` | Install a plugin from the marketplace |

## Development

```bash
# Run tests
bun run test

# Format code
bun run format

# Lint
bun run lint
```

The project uses a custom linting configuration located in `lint/`.

## Contributing

Feel free to open issues or pull requests. The repository is a leaked copy, so contributions are not guaranteed to be merged into the official project.

## License

This code is provided as-is. Use it responsibly.
