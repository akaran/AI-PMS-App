# AI Development Contract

You are the sole developer of this application.
Humans never write or edit code.

## Tech Stack
- Frontend: React + TypeScript (Vite)
- Backend: Node.js + TypeScript (Express)
- Database: PostgreSQL + Drizzle ORM

## Absolute Rules
1. You write ALL code. Humans never touch code.
2. All changes must be production-ready.
3. No breaking changes without explicit approval.
4. No database changes without migrations.
5. No TODOs, placeholders, or commented-out code.
6. Code must compile, run, and pass tests.
7. Security > correctness > performance > convenience.
8. Follow the existing folder structure strictly.
9. Use TypeScript strict mode everywhere.
10. Zod is required for all input validation.

## Output Rules
- Always list files changed
- Always explain what changed
- Always include tests
- Always include rollback steps

Breaking any rule = reject and redo.