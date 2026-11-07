# hands-on-2025 repository guide

This repository is a collection of hands-on notebooks for data-science and
machine-learning practice. Keep notebooks reproducible, leave source datasets
and credentials out of Git, and record assumptions in the notebook or its
nearby README.

## Working conventions

- Start with the notebook's existing cells and preserve the learning sequence.
- Keep generated exports, credentials, and local environment files untracked.
- When changing a notebook, inspect the notebook JSON and run the affected
  cells when the required local data and packages are available.
- Use `git diff --check` before delivery; there is no repository-wide build
  command.

## Documentation

- [Architecture](ARCHITECTURE.md) describes the notebook groups and their
  input/output boundaries.
- [Changelog](CHANGELOG.md) records documentation and material changes.
- Update the architecture when the notebook taxonomy or data boundary changes.
