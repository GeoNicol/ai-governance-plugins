# AI Governance Plugins

A Claude Code plugin marketplace for structured, multi-agent decision-making.

## Board of Directors

Your project gets a board room. Specialized AI agents sit around the table as directors — each with deep domain expertise in technology, finance, product, legal, or growth. They deliberate on your decisions with evidence-based arguments, debate disagreements, vote on motions, and record everything as institutional memory.

You are the CEO and Chairman. You set the agenda, hear the arguments, and have final say. The board works for you.

### How it works

```
/board-setup                                    # Analyze your project and compose your board
/board-meeting Should we migrate to TypeScript?  # Full deliberation with all directors
/board-decide Which database for the new service? # Quick decision with relevant directors
```

A meeting runs through four phases:

1. **Convene** — Directors receive the agenda, load project context and past decisions
2. **Deliberate** — Each director presents their position with evidence (in parallel), then rebuts disagreements
3. **Vote** — FOR / AGAINST / ABSTAIN with rationale, tallied by the Secretary
4. **Record** — Chairman approves or vetoes, minutes are saved with full rationale and dissenting opinions

### The board

| Director | Domain | Lens |
|----------|--------|------|
| CTO | Architecture, scalability, code quality | Technical feasibility and engineering excellence |
| CFO | Costs, ROI, resource allocation | Financial impact and sustainability |
| CPO | User experience, product strategy | User value and product-market fit |
| CLO | Legal, compliance, licensing, privacy | Risk, regulation, and liability |
| CMO | Growth, adoption, developer experience | Market positioning and reach |
| Secretary | Minutes, persistence, action items | Procedural integrity (non-voting) |

Six specialist advisers (Security, Performance, UX, DevOps, Data, AI Ethics) can be called into any meeting when the board needs deeper expertise.

### Key features

- **Circular organization** — all directors have equal voting weight, no hierarchy
- **Parallel deliberation** — directors form positions simultaneously for fast meetings
- **Persistent memory** — decisions, rationale, and dissenting opinions recorded as JSON in `.claude/board/`
- **Project-aware setup** — detects your stack and recommends the right board composition
- **Chairman veto** — you approve, veto, defer, or amend any decision
- **4 templates** — Default, Startup, Web App, API Service

### All commands

| Command | What it does |
|---------|-------------|
| `/board-setup` | Initialize your board with project-aware composition |
| `/board-meeting <topic>` | Full board meeting with deliberation and voting |
| `/board-decide <question>` | Quick decision with 2-3 relevant directors |
| `/board-vote <motion>` | Formal vote on a specific motion |
| `/board-status` | Board dashboard with recent activity |
| `/board-review` | Multi-perspective code review |
| `/board-minutes` | Browse past meeting records |

## Installation

Add this marketplace in Claude Code:

```
/plugin
```

Then enter `GeoNicol/ai-governance-plugins` as the marketplace source and install the Board of Directors plugin.

## License

MIT
