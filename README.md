# SquadOS (Terminal)

> Create AI squads that work together — right from your terminal.

SquadOS is a multi-agent orchestration framework for [Claude Code](https://claude.com/claude-code). Describe what you need in plain language, and SquadOS creates a squad of specialized AI agents that work together automatically.

## What is a Squad?

A squad is a team of AI agents that collaborate on a task. For example:

**Instagram Content Squad** (included as example):
- 🔍 **Scout** researches trending content
- 💡 **Spark** generates viral content ideas
- ✍️ **Quill** writes the carousel copy
- ✅ **Eagle** reviews quality before delivery

The agents work in an automated pipeline — you only step in at key decision points.

## Quick Start

### Prerequisites

1. **Node.js 20+** — [Download here](https://nodejs.org)
2. **Claude Code** — [Install here](https://claude.com/claude-code)

### Installation

Open your terminal in any project folder and run:

```bash
npx squados-terminal init
```

Then open the folder in Claude Code and type:

```
/squados
```

SquadOS will guide you through setup and show you the main menu.

## Commands

| Command | What it does |
|---------|-------------|
| `/squados` | Open the main menu |
| `/squados help` | Show all commands |
| `/squados create` | Create a new squad |
| `/squados run <name>` | Run a squad |
| `/squados list` | See all your squads |
| `/squados edit <name>` | Modify a squad |

## Creating Your Own Squad

Just describe what you need:

```
/squados create "A squad that writes LinkedIn posts about AI trends"
```

The Architect will ask you a few questions, design the squad, and set it up automatically.

## Examples

```
/squados create "Weekly email newsletter squad for my SaaS product"
/squados create "Social media content calendar squad"
/squados create "Customer support email response squad"
/squados create "Data analysis squad for sales spreadsheets"
/squados create "Blog post production squad"
```

## How It Works

1. You describe what you need
2. The **Architect** agent designs a squad with the right agents
3. You approve the design
4. The squad runs automatically, pausing only for your input at checkpoints
5. Final output is saved to your project

## License

MIT — use it however you want.
