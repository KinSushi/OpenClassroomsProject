# Contributing to OpenClassroomsProject

> **Solo learning repository** — this guide documents the workflow conventions used across all projects in this portfolio. It serves as a personal reference and demonstrates professional Git hygiene.

---

## Branching

Branch from `main`. Use the following naming pattern:

```
feature/projet04-ohmyfood-sass-structure
feature/projet06-sophie-bluel-modal-js
fix/projet03-card-overflow-768px
docs/update-readme-project-status
chore/add-gitignore-ds-store
```

| Branch type | Pattern | Purpose |
|---|---|---|
| Feature | `feature/projXX-short-description` | New project or major feature |
| Fix | `fix/projXX-description` | Bug correction |
| Docs | `docs/description` | README, comments, CONTRIBUTING |
| Chore | `chore/description` | Config, file moves, cleanup |

---

## Commits

This repository follows [Conventional Commits](https://www.conventionalcommits.org/).

**Format**

```
<type>(<scope>): <imperative summary — max 50 chars>

[optional body — what and why, max 72 chars per line]

[optional footer — issue refs, breaking changes]
```

**Types used in this project**

| Type | Usage |
|---|---|
| `feat` | New project, page, or feature |
| `fix` | Bug correction (responsive, JS, accessibility) |
| `style` | CSS-only changes with no logic impact |
| `refactor` | Code restructuring without behavior change |
| `docs` | README, CONTRIBUTING, inline comments |
| `chore` | File moves, .gitignore, config files |
| `perf` | Image compression, load time improvements |

**Real examples from this repo**

```bash
feat(projet03): add responsive hebergement card grid
fix(projet03): correct filter button overflow on 320px
style(projet03): align card image heights with object-fit
docs(readme): restructure as full OC portfolio with projects table
chore: add .github/CONTRIBUTING.md workflow reference
```

---

## Pull Requests

Even for a solo project, PRs document what changed and why.

**PR title** — same format as a commit: `feat(projet04): initial SASS structure`

**PR description template**

```markdown
## What
Brief description of what this PR adds or changes.

## Why
Context — why this change was needed.

## How to test
Steps to verify the change works as expected.

## Screenshots (if UI change)
Before / After
```

---

## Code Style

- **HTML** — semantic elements only; no `<div>` where a semantic tag exists
- **CSS** — all new custom values go through CSS variables in `:root`; no magic numbers
- **Files** — kebab-case names (`projet-03-reservia/`, `styles.css`)
- **Images** — compressed before commit; `alt` attribute always set

---

## Resources

- [Conventional Commits specification](https://www.conventionalcommits.org/)
- [Git workflow reference](https://github.com/KinSushi/git-workflow-demo)
- [GitHub profile](https://github.com/KinSushi)
