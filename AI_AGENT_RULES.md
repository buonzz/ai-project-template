# AI Agent Rules

These rules are referenced by [`CLAUDE.md`](./CLAUDE.md) and [`AGENT.md`](./AGENT.md).
AI coding assistants must follow these rules when generating or modifying code.

## File Operations

- Ask before deleting files or directories
- Ask before renaming or restructuring files
- Do not modify spec files (`.md` files in `specs/`, `PROJECT_OVERVIEW.md`, `BUSINESS_RULES.md`, etc.) unless explicitly asked
- Keep generated code in the appropriate source directories (e.g., `src/`, `app/`, `lib/`)

## Code Quality

- Prefer simple, readable solutions over complex ones
- Avoid unnecessary dependencies
- Keep functions small and focused
- Use meaningful variable and function names
- Follow the conventions of the chosen tech stack
- Generate tests for critical paths (auth, payments, data validation)

## Security

- Never hardcode secrets, API keys, tokens, or credentials
- Never bypass authentication or authorization systems
- Never expose private data in logs, error messages, API responses, or client-side code
- Always validate and sanitize user input
- Always use parameterized queries or an ORM for database access
- Follow the [`SECURITY_CHECKLIST.md`](./SECURITY_CHECKLIST.md) requirements

## Communication

- Ask for clarification when requirements are ambiguous
- If a spec is missing details needed for implementation, ask before assuming
- Explain trade-offs when multiple implementation approaches exist
- Flag potential security or performance concerns in generated code

## Workflow

1. Read the relevant spec files first (referenced in [`CLAUDE.md`](./CLAUDE.md) or [`AGENT.md`](./AGENT.md))
2. Understand requirements, edge cases, and constraints before coding
3. Plan the implementation approach
4. Implement following the tech stack and business rules
5. Verify against the security checklist
6. Ask before making assumptions about unspecified behavior
