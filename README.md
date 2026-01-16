# claude-demo
This repository demonstrates Claude Code + GitHub Actions workflow.

## Development Workflow (Company Flow)

This repository follows a standard company-style development workflow:

1. **Issue**  
   Every change starts with a GitHub Issue.  
   The issue clearly describes the goal, scope, and acceptance criteria.

2. **Branch**  
   A dedicated branch is created for each issue.  
   No direct work is done on the `main` branch.

3. **Pull Request (PR)**  
   Changes are submitted via a Pull Request.  
   This allows review and automated checks before merging.

4. **CI (Continuous Integration)**  
   GitHub Actions automatically runs checks on every PR.  
   If CI fails, the PR cannot be merged.

5. **Review**  
   Code and documentation changes are reviewed before approval.

6. **Merge**  
   Only after CI passes and review is complete, changes are merged into `main`.

---

## CI Rules (GitHub Actions)

This repository uses GitHub Actions to enforce basic repository rules.

### What CI checks

- Required files must exist:
  - `README.md`
  - `CLAUDE.md`

### Why CI exists

- Prevents unsafe or undocumented changes
- Ensures consistent repository standards
- Blocks merging when rules are violated

**Important:**  
If CI fails, merging into `main` is not allowed.
