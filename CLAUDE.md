# Commit rules

- Every change must be committed without asking for confirmation first.
- Commit messages carry a version number, starting at v1.1 and incrementing
  by one minor version on each commit (v1.1, v1.2, v1.3, ...).
- The current version is tracked in `.claude-version` at the repo root — read
  it before committing, use that value in the commit message, then write the
  incremented value back before or as part of the same commit.
- Commit message format: `<version> <summary>` (e.g. `v1.3 Fix footer link color`).
