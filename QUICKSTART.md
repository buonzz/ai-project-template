---
agent: quickstart
priority: 0
---

# Quick Start

## Step 1 — Describe Your Project

Open:
- [`PROJECT_OVERVIEW.md`](./PROJECT_OVERVIEW.md)
- [`GLOSSARY.md`](./GLOSSARY.md)

Fill them out in plain English.

## Step 2 — Define Features

Open:
- [`FEATURES.md`](./FEATURES.md)
- [`USER_STORIES.md`](./USER_STORIES.md)

Describe what users should be able to do.

## Step 3 — Define Rules

Open:
- [`BUSINESS_RULES.md`](./BUSINESS_RULES.md)
- [`SECURITY_CHECKLIST.md`](./SECURITY_CHECKLIST.md)

Add constraints and safety requirements.

## Step 4 — AI Agent Auto-Discovery (No Setup Needed)

This template includes two agent configuration files at the project root:

| File | Auto-discovered by |
|------|-------------------|
| [`CLAUDE.md`](./CLAUDE.md) | Claude Code |
| [`AGENT.md`](./AGENT.md) | Cursor, Windsurf, GitHub Copilot |

These files tell the AI assistant:
- What your project is about
- Which spec files to read for context
- What rules to follow
- What workflow to use

**You don't need to configure anything.** Just open your AI coding tool in this project directory — it will automatically read the agent file and discover your specs.

### If your tool doesn't auto-discover

Manually provide these files to the AI:
- [`CLAUDE.md`](./CLAUDE.md) or [`AGENT.md`](./AGENT.md) (start here)
- [`PROJECT_OVERVIEW.md`](./PROJECT_OVERVIEW.md)
- [`TECH_STACK.md`](./TECH_STACK.md)
- [`BUSINESS_RULES.md`](./BUSINESS_RULES.md)
- [`SECURITY_CHECKLIST.md`](./SECURITY_CHECKLIST.md)
- [`FEATURES.md`](./FEATURES.md) or relevant spec in [`specs/`](./specs/)

## Step 5 — Give Context to AI

If your tool does not support [`CLAUDE.md`](./CLAUDE.md) or [`AGENT.md`](./AGENT.md), provide the files to:
- ChatGPT
- Claude
- Cursor
- Windsurf
- Amazon Q
- Copilot

## Step 6 — Review Everything

Never blindly trust generated code.
