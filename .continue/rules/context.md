# Context map

```text
.
├── LICENSE
├── README.md
├── .continue/
│   └── rules/
│       ├── architecture.md
│       ├── context.md
│       └── git.md
└── .github/
    ├── cliff.toml
    └── workflows/
        ├── cliff.yml
        └── commit-labeler.yml
```

## External documentation

- Before changing repository automation, check the relevant official docs first.
- This repository currently contains no application stack, so do not assume runtime libraries or frameworks yet.
- Add stack-specific links here once code appears.

### Current references

- Continue docs: https://docs.continue.dev
- GitHub Actions docs: https://docs.github.com/actions
- actions/checkout: https://github.com/actions/checkout
- actions/github-script: https://github.com/actions/github-script
- Python docs: https://docs.python.org/3/
- git-cliff docs: https://git-cliff.org/docs/
- git-cliff GitHub Action: https://github.com/orhun/git-cliff-action
- GitHub CLI docs: https://cli.github.com/manual/
- GH API docs: https://docs.github.com/rest

### Usage notes

- `.github/workflows/cliff.yml` and `.github/workflows/commit-labeler.yml` should follow the linked GitHub Actions patterns.
- `.github/workflows/cliff.yml` also uses shell scripting, Python standard library modules, and GitHub CLI calls, so check the Python, GH CLI, and GitHub REST docs when editing it.
- `.github/cliff.toml` should follow git-cliff configuration and changelog formatting guidance.
- If a future task introduces code, extend this section with the new library and service docs.
