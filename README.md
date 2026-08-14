# .github

This repository holds RMI's organization-wide GitHub community health defaults. Files here apply to every repository in the org that doesn't provide it's own.

## What Lives Here

- `CONTRIBUTING.md`: default contributor guide.
- `PULL_REQUEST_TEMPLATE.md`: a default PR template, aligned with the process guidance in [`practices/process/pull_request.md`](https://github.com/RMI/practices/blob/main/process/pull_request.md).

## How This Repo Relates to `practices`

- `practices`[https://github.com/RMI/practices] is the source of truth for guidance: the "why" and "how" behind our engineering standards.
- `.github` is the operational surface: templates and defaults GitHub picks up automatically when a repo doesn't override them.

## Overriding defaults

Any repository can override these by shipping it's own file at the same path. 
Repository maintainers own that decision - see: [practices/principles/maintainer.md](https://github.com/RMI/practices/blob/main/principles/maintainer.md)
## Contributing

Changes here affect every repository in the RMI org. Open a PR and get review from @RMI/spd before merging.
