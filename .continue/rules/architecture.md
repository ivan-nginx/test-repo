# Architecture rules

## Current repository state

- The repository currently contains only `LICENSE`, `README.md`, `.continue/rules/`, and `.github/` automation files.
- No application source code is present yet.
- Do not infer a runtime stack until source files or explicit project documentation are added.

## Repository structure

- Keep documentation and automation at the repository root unless a concrete application structure is introduced.
- Store Continue-specific project guidance in `.continue/rules/`.
- Keep CI/CD configuration in `.github/workflows/`.
- When source code appears, update these rules before making broad architectural changes.

## Roles

- Use only programmer or documentation maintainer roles unless the task explicitly requires another role.

## Context policy

- Prefer reading targeted files over scanning the entire repository.
- Treat these rules as the primary compact context source for future AI work.
- Keep rules short and decision-oriented; avoid duplicating full documentation.

## Dependency boundaries

- Do not introduce cross-component dependencies until components are defined.
- If backend, frontend, bot, or shared packages are added, document allowed import directions here.
- Generated files, build artifacts, dependency folders, and coverage output should not be used as architectural context.
