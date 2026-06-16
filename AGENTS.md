## Commands

- `pnpm typecheck` runs a typecheck
- `pnpm build` builds the project to `dist/`
- `pnpm test` runs the test suite
- `pnpm format:all` formats all non-prettierignored files

## Rules

- **Git: read-only.** NO staging, unstaging, committing, stashing, pushing, pulling, or history changes unless explicitly asked for. Data-reading commands and `git add -N` (intent-to-add) are fine.
- **Formatting:** When creating brand new files or making large edits, run `pnpm format:all` when you are done with all edits. For single-file-only edits, run `pnpm format <file>` when done with all edits.
- **Dev servers:** Do not kill existing dev servers unless explicitly asked to. If you start a dev server while responding to a request, ensure that it is stopped when you are done.
