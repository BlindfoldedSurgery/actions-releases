# actions-actions

This repository contains a set of reusable workflows geared towards supporting the maintenance of
such reusable workflows.

The project follows semantic versioning. You can depend on tags for specific versions of use a
major version tag (e.g. `v1`).

Every commit on the main branch leads to a new release. Releases are managed by
[commitizen][commitizen], which relies on [conventional commits][ccommit]. To make sure you don't
accidentally create commits with an unconventional message, install a pre-commit hook using
`make pre-commit`.

[commitizen]: https://commitizen-tools.github.io/commitizen/

[ccommit]: https://www.conventionalcommits.org/en/v1.0.0/

## Example

```yaml
jobs:
  commitizen:
    uses: BlindfoldedSurgery/actions-actions/.github/workflows/commitizen.yml@v1
```

## Available Workflows

### commitizen

Checks whether commit messages in a PR abide by the conventional commit rules.

Automatically calls cz bump for changes on the default branch and creates an (auto-merged) PR
with the bump.
