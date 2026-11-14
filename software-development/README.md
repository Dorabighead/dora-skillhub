# Software Development Workflow

A general workflow for coding agents and collaborators. Follow the target repository's `AGENTS.md`, contribution guide, tests, and current user instructions whenever they exist.

## Understand the project

1. Inspect the repository status and relevant project documentation before editing.
2. Trace the behavior involved in the request through the relevant code and existing tests.
3. Identify user changes already present and preserve unrelated work.
4. State assumptions only when needed; verify important behavior from source or execution.

## Make a focused change

1. Choose the smallest coherent implementation that satisfies the request.
2. Match existing naming, structure, formatting, and error-handling patterns.
3. Handle boundary cases and failures explicitly.
4. Avoid unrelated refactors, generated artifacts, secrets, personal data, and machine-specific paths.

## Review and validate

1. Inspect the full diff for scope, correctness, accidental data, and unintended changes.
2. Run relevant checks when requested or required by repository instructions; report exactly what was run and its result.
3. Do not claim a check passed if it was not run.
4. Explain the change, evidence, and any remaining limitation in concise terms.

## Git collaboration

Check branch, status, staged changes, and remote before committing or pushing. Stage only task-related files and review the staged diff. Preserve unrelated work. Push only with appropriate authorization; do not force-push or rewrite history unless explicitly authorized.
