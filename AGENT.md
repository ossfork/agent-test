# Agent Instructions

> ALWAYS SKIP `CLAUDE.md`

These instructions apply to this directory and its descendants.

## Goal - Test Agent Behavior

- Observability is first priority under this repo.
- Show thinking chains/instructions/usages when calling both internal and external commands/skills/mcp/tool calls/etc.

## Working Principles

- Make focused, minimal changes that directly address the task.
- Prefer existing project conventions over introducing new patterns.
- Do not rewrite unrelated code or reformat files outside the requested scope.
- Preserve user changes. Do not revert files unless explicitly asked.

## Code Changes

- Keep implementations simple and readable.
- Add comments only when they clarify non-obvious behavior.
- Avoid adding new dependencies unless they are clearly justified.
- Update documentation when behavior, setup, or usage changes.

## Verification

- Run the most relevant available checks before finishing.
- If checks cannot be run, state why and describe the remaining risk.
- For bug fixes, prefer adding or updating focused tests when practical.

## Communication

- Summarize what changed and how it was verified.
- Call out assumptions, tradeoffs, and any follow-up work that remains.
