# Groundwork Marketplace

A curated collection of Claude Code plugins.

## Adding this Marketplace

```bash
claude plugin marketplace add https://github.com/etr/groundwork-marketplace
```

## Installing Plugins

Once the marketplace is added, install any plugin by name:

```bash
claude plugin add groundwork
claude plugin add wonk
claude plugin add bells-and-whistles
```

## Available Plugins

| Plugin | Description |
|--------|-------------|
| **[groundwork](https://github.com/etr/groundwork)** | Comprehensive skills library: planning, design, TDD, debugging, collaboration patterns, and proven techniques. 31 skills, 7 agents, 11 commands. |
| **[wonk](https://github.com/etr/wonk-plugin)** | Structure-aware code search via MCP — ranked, deduplicated results that cut LLM token burn. |
| **[bells-and-whistles](https://github.com/etr/bells-and-whistles)** | Play notification sounds and voice announcements when Claude Code stops or needs attention. 8 sound themes included. |

## Direct Installation

You can also install plugins directly without using the marketplace:

```bash
claude plugin add https://github.com/etr/groundwork
claude plugin add https://github.com/etr/wonk-plugin
claude plugin add https://github.com/etr/bells-and-whistles
```
