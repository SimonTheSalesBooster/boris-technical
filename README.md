# Boris .. Your AI Fractional CTO

Every SaaS tool, API key, and automation is a liability until proven otherwise. Boris audits your tech stack, kills redundancy, and proposes the simplest path to the same outcome.

Built for [Claude Code](https://docs.anthropic.com/en/docs/claude-code). Part of the [Strategy Sprints](https://strategysprints.com) AI advisor system.

---

## What Boris Does

**Stack Health Audit** .. Cost, complexity, and redundancy across every tool, API, and automation you run. If three tools do the same thing, Boris tells you which one to keep and why.

**Token Usage Monitoring** .. Tracks token spend across all your AI agents. Flags runaway costs before they become a problem.

**New Tool Evaluation** .. When a shiny new tool appears, Boris runs a structured 7-day test plan before you commit. No impulse purchases.

**Frontier Scout** .. Watches Anthropic, OpenAI, Google, and 12+ other sources for capabilities that make your current agents obsolete. You hear about it the day it ships.. not three months later.

**Agent Factory** .. When a gap is identified, Boris builds the agent. Skill file, scheduled task, test, integration. One agent per gap, no sprawl.

---

## 3 Strategy Agents

Boris delegates to three specialized agents:

| Agent | Role | Cadence |
|-------|------|---------|
| **Frontier Scout** | Scans 15+ sources for new tech, tools, patterns. Rates each as IMPLEMENT, WATCH, or IGNORE. | Tue / Fri |
| **Agent Ops** | Monitors all scheduled tasks, detects failures, auto-retries, reports health. | Daily |
| **Agent Factory** | Builds new agents when gaps are found. Upgrades and retires existing ones. Weekly hiring round. | Mon + on-demand |

---

## Example Output

```
Boris Technical Advisor -- 2026-04-09

STACK: 28 agents GREEN | 2 YELLOW | 0 RED
FRONTIER: Claude Code now supports background agents natively -- kills 2 custom workarounds

PROPOSALS:
  Replace n8n workflows with native Claude Code hooks -- Feasibility 5/5, hours
  Build affiliate tracking portal -- Feasibility 2/5, 2 weeks

COST FLAG: Token spend up 34% week-over-week.
  Root cause: greg-s6-repurpose running 3x daily instead of 1x.
  Fix: reduce schedule to once daily. Saves ~$12/day.

TECH MOVE: Migrate 4 n8n automations to Claude Code hooks.
  Same outcome, zero external dependency, 90 min to build.

VERDICT: Infrastructure is clean. One cost fix, one migration. No fires.
```

---

## Feasibility Rating Scale

| Rating | Meaning | Build Time |
|--------|---------|------------|
| 5 | Trivial .. existing tools, known patterns | Hours |
| 4 | Straightforward .. clear path, minor unknowns | 1-2 days |
| 3 | Moderate .. requires research or new integration | 3-5 days |
| 2 | Complex .. significant unknowns, dependencies | 1-2 weeks |
| 1 | Major .. new infrastructure, external dependencies | 2+ weeks |

---

## Signature Move

> "You're paying for 3 tools that do the same thing. Here's which one to keep and why."

Boris rates every proposal on feasibility, names dependencies and blockers, flags security surface, and tells you the build time before you commit.

---

## Board of Advisors

Boris is one advisor on a team of specialists:

| Advisor | Domain |
|---------|--------|
| **Boris** | Technical / Fractional CTO |
| [Richard](https://github.com/SimonTheSalesBooster/richard-strategy) | Strategy (Rumelt kernel) |
| [Anthony](https://github.com/SimonTheSalesBooster/anthony-sales) | Sales Execution |
| [Greg](https://github.com/SimonTheSalesBooster/greg-distribution) | Distribution (Isenberg 6) |
| [Jay](https://github.com/SimonTheSalesBooster/jay-advisor) | Strategic Alliances |

---

## Quick Start

```bash
# Install Claude Code
brew install claude

# Clone this repo
git clone https://github.com/SimonTheSalesBooster/boris-technical.git

# Copy the skill into your Claude Code commands
cp boris-technical/SKILL.md ~/.claude/commands/boris-advisor.md

# Run Boris
claude /boris-advisor
```

---

## Talk to Simon

Want to see this running on your business?

[Book a 15-min coffee chat](https://calendly.com/simonseverino/coffee-with-simon)
