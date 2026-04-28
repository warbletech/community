# Contributing to Warble Cloud

Thanks for considering a contribution. This page covers how to land a PR, what we expect, and how to find a low-friction first task.

> **Code of Conduct** — All contributions are governed by [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md). Be excellent to each other.

## Where do I contribute?

| What | Where |
|---|---|
| Code | Product repos under [github.com/warble-tech](https://github.com/warble-tech) — `warble-core`, `starling`, `reflexion`, etc. |
| Docs | [`warble-core/frontend/src/app/devcentral`](https://github.com/warble-tech/warble-core/tree/main/frontend/src/app/devcentral) and the relevant product repo |
| RFCs | [`rfcs/`](rfcs/) in this repo |
| Showcase entries | [`showcase/`](showcase/) in this repo |
| Working group artifacts | [`working-groups/<wg>`](working-groups/) in this repo |

## Good first issues

Issues labeled [`good first issue`](https://github.com/search?q=org%3Awarble-tech+label%3A%22good+first+issue%22+state%3Aopen&type=issues) across `warble-tech` are the best entry points.

## PR checklist

Before opening a PR:

- [ ] Tests pass locally (`npm test` for frontend, `pytest` for Python services)
- [ ] Type-check is clean (`tsc --noEmit`)
- [ ] No new lint warnings introduced
- [ ] Commit messages follow [Conventional Commits](https://www.conventionalcommits.org/) — e.g. `feat(starling): ...`
- [ ] PR description explains *why*, not just *what*
- [ ] Linked to an issue if one exists

## Review

- Most PRs get a first review within 48 hours.
- Maintainers may request changes; please don't take it personally — we review the same way for our own commits.
- We use **lazy consensus** — if no maintainer objects within the review window, your PR can be merged.

## Signing commits

Commits to all `warble-tech` repos must be signed (GPG, SSH, or via GitHub's signed-by-web). Unsigned commits are blocked at merge time.

## DCO

By contributing, you agree your contributions are licensed under the project's stated license (MIT for code, CC BY 4.0 for docs).

## Getting help

- **Discord** — fastest. [https://discord.gg/warblecloud](https://discord.gg/warblecloud)
- **Office Hours** — Saturdays 7–8pm IST
- **Email** — [hello@warblecloud.com](mailto:hello@warblecloud.com) for anything that doesn't fit the above
