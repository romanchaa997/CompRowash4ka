# Contributing to CompRoW@sh4ka

Thank you for your interest in contributing to CompRoW@sh4ka. This document explains how to get involved, what to expect from the process, and how to keep collaboration productive and respectful.

---

## Table of Contents

1. [Code of Conduct](#code-of-conduct)
2. [Ways to Contribute](#ways-to-contribute)
3. [Getting Started](#getting-started)
4. [Issue Workflow](#issue-workflow)
5. [Pull Request Process](#pull-request-process)
6. [Writing Standards](#writing-standards)
7. [Review & Merge](#review--merge)

---

## Code of Conduct

All contributors are expected to follow our [Code of Conduct](CODE_OF_CONDUCT.md). In short: be respectful, be constructive, and assume good intent. Harassment, discrimination, or bad-faith participation will not be tolerated.

If you witness or experience a violation, contact the maintainers at **conduct@comprow.sh** (once live) or via a private GitHub issue.

---

## Ways to Contribute

| Type | Examples |
|---|---|
| **Documentation** | Improve or translate docs, fix typos, add examples |
| **Standards Drafting** | Propose additions or amendments to published standards |
| **Code** | Tooling, scripts, automation, CI/CD improvements |
| **Research** | Security research write-ups, vulnerability reports |
| **Community** | Organizing events, moderating channels, helping newcomers |

---

## Getting Started

1. **Fork** the repository to your own GitHub account.
2. **Clone** your fork locally: `git clone https://github.com/<your-handle>/CompRowash4ka.git`
3. **Create a branch** for your work: `git checkout -b feat/your-feature-name`
4. Make your changes following the [Writing Standards](#writing-standards) below.
5. **Commit** with a clear, conventional message (see below).
6. **Push** your branch and open a Pull Request against `main`.

### Commit Message Convention

We follow [Conventional Commits](https://www.conventionalcommits.org/):

```
<type>(<scope>): <short description>

[optional body]
[optional footer]
```

Common types: `docs`, `feat`, `fix`, `chore`, `refactor`, `test`.

Examples:
- `docs(vision): expand mission statement`
- `feat(tooling): add smart contract lint script`
- `fix(roadmap): correct Q3 milestone date`

---

## Issue Workflow

1. **Search existing issues** before opening a new one.
2. Use the appropriate issue template (Bug Report or Feature Request).
3. Provide as much context as possible — vague issues are hard to act on.
4. Issues are triaged within **5 business days**.
5. If you want to work on an issue, comment to claim it before starting — this avoids duplicated effort.

---

## Pull Request Process

1. Fill out the Pull Request template completely.
2. Link the PR to the related issue using `Closes #<issue-number>`.
3. Ensure all CI checks pass before requesting review.
4. PRs require **at least one approving review** from a maintainer before merging.
5. Keep PRs focused — one logical change per PR. Large PRs are harder to review and slower to merge.
6. Respond to review comments within **7 days**; PRs with no activity may be closed.

---

## Writing Standards

- **Language**: Ukrainian for community-facing narrative docs; English for technical specs and code comments. Bilingual is welcome.
- **Tone**: Professional but accessible. Avoid jargon where a plain term works just as well.
- **Formatting**: Use Markdown. Headers, tables, and lists are encouraged for readability.
- **File naming**: `kebab-case.md` for new documents.
- **Links**: Prefer relative links within the repo; use absolute links for external resources.

---

## Review & Merge

- Maintainers will leave clear, actionable feedback.
- Once approved, a maintainer will merge the PR — contributors do not merge their own PRs.
- Merged contributions are credited in the project changelog (coming soon).

---

*Thank you for helping build the open Web3 security commons.*
