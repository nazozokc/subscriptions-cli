# subtrack

A CLI tool to manage your subscription services from the terminal.

## Features

- List all subscriptions in a formatted table
- Add a subscription interactively (name, price, currency, cycle, tags)
- Delete a subscription by ID

## Usage

```bash
# List all subscriptions
bunx subtrack list

# Add a new subscription (interactive prompts)
bunx subtrack add

# Delete a subscription by ID
bunx subtrack delete <id>

# List tags subscriptions
bunx subtrack tags <tags>
```

> [!TIP]
> The binary name is `subtrack`. Run via `bunx subtrack <command>` after `bun install`.

## Data

Subscriptions are stored in `~/.config/subtrack/subtrack.db`.

## Development

```bash
# Install dependencies
bun install

# Run directly
bun run src/index.ts
```

## Install

```bash
bun install
```

Then link globally if you want:

```bash
bun link
```

Now you can use `sb` directly from anywhere.
