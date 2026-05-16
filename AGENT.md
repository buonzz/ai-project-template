# AGENT.md — AI Agent Context

This file is automatically read by Cursor, Windsurf, GitHub Copilot, and compatible AI coding assistants.

## Project Overview

This project uses a **specification-first** approach. All requirements, rules, and architecture decisions are documented in markdown files before any code is written.

## Required Reading — Load These Files for Context

Before generating or modifying code, read the following files in order:

### 1. Project Identity
- [`PROJECT_OVERVIEW.md`](./PROJECT_OVERVIEW.md) — What this project is, who it serves, and its goals
- [`TECH_STACK.md`](./TECH_STACK.md) — Approved technologies and frameworks
- [`GLOSSARY.md`](./GLOSSARY.md) — Domain-specific terminology

### 2. Rules & Constraints
- [`BUSINESS_RULES.md`](./BUSINESS_RULES.md) — Non-negotiable business logic rules
- [`SECURITY_CHECKLIST.md`](./SECURITY_CHECKLIST.md) — Security requirements that must never be violated
- [`AI_AGENT_RULES.md`](./AI_AGENT_RULES.md) — Behavioral rules for the AI assistant

### 3. Feature Specifications
- [`FEATURES.md`](./FEATURES.md) — Detailed feature definitions with requirements and edge cases
- [`USER_STORIES.md`](./USER_STORIES.md) — User-centric feature descriptions
- [`specs/`](./specs/) — Individual feature specs (one per feature)

### 4. Design & UX
- [`UI_UX_GUIDELINES.md`](./UI_UX_GUIDELINES.md) — Design principles and visual style

## Agent Workflow

When asked to implement or modify code:

1. **Read** the relevant spec files first (see above)
2. **Understand** the requirements, edge cases, and constraints
3. **Plan** the implementation before writing code
4. **Implement** following the tech stack and business rules
5. **Verify** against the security checklist
6. **Ask** for clarification if requirements are ambiguous

## Critical Rules

- Never hardcode secrets, API keys, or credentials
- Never bypass authentication or authorization
- Never expose private data in logs, responses, or client code
- Always validate and sanitize user input
- Always handle edge cases documented in specs
- Ask before deleting files or making breaking changes
- Prefer simple, readable solutions over complex ones
- Generate tests for critical paths

## File Structure

```
.
├── CLAUDE.md              # Agent context (Claude Code)
├── AGENT.md               # This file — agent context (Cursor, Windsurf, Copilot)
├── README.md              # Project overview for humans
├── PROJECT_OVERVIEW.md    # Project identity and goals
├── TECH_STACK.md          # Technology decisions
├── GLOSSARY.md            # Domain terminology
├── BUSINESS_RULES.md      # Business logic constraints
├── SECURITY_CHECKLIST.md  # Security requirements
├── AI_AGENT_RULES.md      # AI behavioral rules
├── FEATURES.md            # Feature definitions
├── USER_STORIES.md        # User stories
├── UI_UX_GUIDELINES.md    # Design guidelines
├── QUICKSTART.md          # Getting started guide
├── specs/                 # Individual feature specs
│   ├── authentication.md
│   ├── dashboard.md
│   └── payments.md
└── examples/              # Example specs for reference
    ├── bad-feature-spec.md
    └── good-feature-spec.md
```
