# Governance

## Roles

- **Maintainers** merge pull requests, triage issues, cut releases and decide the direction of the project. The maintainers are listed in
  `.github/CODEOWNERS`.
- **Contributors** are everyone who files an issue, reviews or sends a pull request.

## How decisions are made

Small changes (bug fixes, documentation, tests) are decided in the pull request by a maintainer's review. Changes that add or change public
API, behavior, supported platforms or dependencies need an issue first. Maintainers aim for consensus; when there is none, the lead
maintainer decides and writes the reason in the issue.

## Versioning and releases

All packages are released together under one version number following semantic versioning. Public API is what the package `exports` maps
and the documentation expose; anything under an `internal` path is private and may change in any release. Deprecated API keeps working for at
least one minor release and logs a warning that names the replacement. A release is cut by a maintainer from the main branch after the full
test suite, the size and tree-shaking budgets, the type tests and the release verification pass, and is published with npm provenance.

## Long-term support

- **Latest minor:** receives every fix.
- **Previous minor:** receives security fixes and fixes for regressions for six months after the next minor ships.
- **Previous major:** receives security fixes for twelve months after the next major ships. Each major ships with a migration guide and, where
  the change can be mechanical, a codemod (`create-shadow-app codemod`).
- **Deprecations:** announced in a minor release with a runtime warning and a changelog entry, kept for at least two minor releases, and removed
  only in a major release. Security fixes are the one exception that may change behavior in a minor release.
- **Platforms:** Node.js 22 (from 22.12) and newer LTS lines while they are in active or maintenance support, the latest two versions of the
  evergreen browsers, and the Vite and TypeScript ranges listed in SUPPORT.md. A platform that leaves its own support window is dropped in the
  next minor release after it does, with one release of notice.

## Size and quality budgets

Bundle size budgets only go down. A change that raises a budget needs a maintainer's explicit approval and a written reason in the pull request.
