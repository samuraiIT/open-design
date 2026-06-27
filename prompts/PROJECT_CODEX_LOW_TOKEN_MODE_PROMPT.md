# Project Codex Low-Token Mode Prompt

Use this prompt when working inside `projects/open-design-src/`.

- Base behavior inherits from root `prompts/CODEX_LOW_TOKEN_MODE_PROMPT.md`.
- Read `AGENTS.md`, `README.md`, and only the relevant module-level `AGENTS.md` before drilling deeper.
- Prefer narrow reads with `rg --files` and `rg -n`; avoid loading the whole monorepo or generated artifacts.
- Keep changes scoped to the touched package, tool, or app surface.
