# Clarethium organization profile

This repository hosts the public-facing organization profile for [github.com/Clarethium](https://github.com/Clarethium).

The file at `profile/README.md` is rendered as the organization's landing page on GitHub.

## Editing

Edits to `profile/README.md` should:

- Stay focused on the organization's mission and active projects
- Avoid duplicating documentation that lives in project repositories
- Update project status when projects launch, change status, or sunset

## Layout

```
.github/
└── profile/
    └── README.md      # The organization's public README
```

This is GitHub's standard organization profile pattern: a special repository named `.github` with a `profile/README.md` file.

## Project list

When adding or removing projects from the org, update `profile/README.md` to reflect the change.

Current active projects:

Methodology reference artifacts (the three stones):
- [touchstone](https://github.com/Clarethium/touchstone): Touchstone Standard and reference implementation
- [lodestone](https://github.com/Clarethium/lodestone): canonical operator methodology manuscript
- Whetstone: at [clarethium-app](https://github.com/Clarethium/clarethium-app); rename to `whetstone` planned

Companion tooling:
- [cma](https://github.com/Clarethium/cma): executable compound-practice loop, terminal-side companion to Lodestone

Applied vehicles:
- [frame-check-mcp](https://github.com/Clarethium/frame-check-mcp): applied tool for frame validation in AI outputs
