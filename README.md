# AI Governance Plugins

A Claude Code plugin marketplace for AI governance and multi-agent decision-making tools.

## Available Plugins

### Board of Directors

A circular AI governance system where specialized AI agents serve as board members, deliberating and voting on project decisions. You serve as CEO/Chairman with veto power.

**Features:**
- 6 director agents (CTO, CFO, CPO, CLO, CMO, Secretary) with equal voting weight
- 6 specialist advisers (Security, Performance, UX, DevOps, Data, AI Ethics)
- Full meeting lifecycle with parallel deliberation, cross-examination, and formal voting
- Persistent board memory with decision history and institutional knowledge
- 4 board composition templates (Default, Startup, Web App, API Service)
- Chairman veto power with recorded rationale

**Commands:** `/board-setup`, `/board-meeting`, `/board-decide`, `/board-vote`, `/board-status`, `/board-review`, `/board-minutes`

## Installation

### Add this marketplace

```
/install-plugin marketplace ai-governance-plugins
```

Or add this repository URL as a marketplace source in Claude Code.

### Install a plugin

```
/install-plugin ai-governance-plugins/board-of-directors
```

### Quick start

After installing the Board of Directors plugin:

```
/board-setup           # Initialize your board
/board-meeting <topic> # Convene a meeting
/board-decide <question> # Quick decision
```

## Contributing

This marketplace is open to AI governance-related plugins. To submit a plugin:

1. Create your plugin as a GitHub repository with a `.claude-plugin/plugin.json`
2. Open an issue on this repo with the plugin URL and description
3. We'll review and add it to the marketplace

## License

MIT
