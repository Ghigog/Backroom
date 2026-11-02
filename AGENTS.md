# AGENTS.md

Backroom is a very young repository: it has no application code, build, lint or test setup yet. Update this file as directories are added.

## Where things are

- `README.md` — project title; the only documentation so far.
- `.github/workflows/` — CI automation. `formic-agent.yml` runs the Formic coding agent; it is installed and replaced by Formic, so don't edit it by hand.
- `AGENTS.md` — this file. `CLAUDE.md` only contains `@AGENTS.md`, so Claude Code reads the same instructions; edit this file, not `CLAUDE.md`.

## Working here

- There are no project checks to run yet. When you add code, add its test/lint commands here.
- Keep changes small and match the surrounding files.
