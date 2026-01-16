# claude-demo

This repository demonstrates Claude Code + GitHub Actions workflow.

## Workflow (Issue → Branch → PR → CI → Merge)
- Create an Issue describing the goal and acceptance criteria
- Create a branch from `main` for that issue
- Make changes on that branch
- Open a Pull Request (PR)
- CI (GitHub Actions) runs automatically on push/PR
- Merge only if CI is green

## CI rules (what is enforced)
Our GitHub Actions workflow checks:
- `README.md` exists
- `CLAUDE.md` exists
If any required file is missing, CI fails (red).
