# AI Project Template

A lightweight specification-first starter kit for responsible AI-assisted software development.

Designed for:
- Business owners
- Product managers
- Hobbyists
- Non-technical founders
- AI-assisted development teams

## Goal

Help humans and AI agents collaborate safely, clearly, and professionally.

## How It Works

This template uses **markdown specification files** to define your project before writing code. AI coding assistants automatically discover these files through [`CLAUDE.md`](./CLAUDE.md) and [`AGENT.md`](./AGENT.md) — the standard agent configuration files that Claude Code, Cursor, Windsurf, and Copilot read at the project root.

### What makes this template agent-compatible?

| File | Purpose | Auto-discovered by |
|------|---------|-------------------|
| [`CLAUDE.md`](./CLAUDE.md) | Agent context for Claude Code | Claude Code |
| [`AGENT.md`](./AGENT.md) | Agent context for Cursor, Windsurf, Copilot | Cursor, Windsurf, Copilot |
| [`PROJECT_OVERVIEW.md`](./PROJECT_OVERVIEW.md) | Project identity and goals | Referenced by agent files |
| [`TECH_STACK.md`](./TECH_STACK.md) | Approved technologies | Referenced by agent files |
| [`BUSINESS_RULES.md`](./BUSINESS_RULES.md) | Non-negotiable business logic | Referenced by agent files |
| [`SECURITY_CHECKLIST.md`](./SECURITY_CHECKLIST.md) | Security requirements | Referenced by agent files |
| [`AI_AGENT_RULES.md`](./AI_AGENT_RULES.md) | Behavioral rules for AI | Referenced by agent files |
| [`FEATURES.md`](./FEATURES.md) | Feature definitions | Referenced by agent files |
| [`specs/`](./specs/) | Individual feature specs | Referenced by agent files |

## Recommended Workflow

1. Fill out the markdown files
2. Define business rules clearly
3. Define features before coding
4. AI agents auto-discover specs via [`CLAUDE.md`](./CLAUDE.md) or [`AGENT.md`](./AGENT.md)
5. Review generated code carefully

## Quick Start

See [`QUICKSTART.md`](./QUICKSTART.md) for step-by-step instructions.

## Important

AI coding tools are assistants — not autonomous senior engineers.
Always review generated code for:
- security
- correctness
- edge cases
- privacy concerns
- maintainability
