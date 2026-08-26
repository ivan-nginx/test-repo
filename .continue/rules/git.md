# Git rules

## Current state

- The repository uses GitHub Actions and changelog automation in `.github/`.
- Keep commit history small and focused.

## Working rules

- Make one logical change per commit when possible.
- Prefer small diffs over broad refactors.
- Do not commit generated artifacts, dependency folders, build output, or secrets.
- Update docs and rules together with behavior changes.
- If a change affects CI, update the relevant workflow and note the impact in the PR or commit message.
- Preserve existing release or changelog automation unless the task explicitly changes it.
