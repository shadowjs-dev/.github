# AGENTS.md: working on .github

This repository holds the organization's profile and the community files every ShadowJS repository inherits: the code of conduct, the
contribution and security guides, the support and governance pages, and the issue and pull request templates. It has no code and no build.
The code lives in one repository per package; see the table in [README.md](README.md).

## How to change it

1. Edit the Markdown or YAML file; keep the text short and in American English. Links use `https`, and a link to a file in this repository is relative.
2. A change to a policy (conduct, security, governance, support) needs an issue first, so the maintainers can discuss it.
3. Open a pull request against `main` from a branch (`docs/<topic>`). One concern per pull request; commit under your own identity, with a short type prefix (`docs:`, `chore:`), and no trailers or notes about tools.
4. A maintainer (see `.github/CODEOWNERS`) reviews and squash-merges it.

## Where to look next

- [README.md](README.md): the table of repositories.
- [SKILL.md](SKILL.md): which package solves which problem, for a coding agent that builds with ShadowJS.
- [CONTRIBUTING.md](CONTRIBUTING.md): how to choose the repository for a change.
- Each package repository has its own AGENTS.md: https://github.com/shadowjs-dev/shadow
