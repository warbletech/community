# Working Groups

A Working Group (WG) is a focused, persistent effort on one slice of Warble Cloud. Each WG has:

- A **charter** — what's in scope, what's out
- 1–2 **leads** — set agenda, run meetings, represent the WG
- A **public meeting cadence** — at least once a month
- An **issue label** in the relevant product repo (e.g. `wg/agents`)

## Active WGs

| WG | Scope | Lead(s) | Meets |
|---|---|---|---|
| [agents](agents/) | Reflexion, Brain, agent runtimes | _open_ | TBD |
| [k8s](k8s/) | Starling, ShrikeOps, FRAKMA | _open_ | TBD |
| [finops](finops/) | FinOps Agent, cost reasoning | _open_ | TBD |
| [devx](devx/) | DevCentral, docs, onboarding | _open_ | TBD |

## Starting a new WG

1. Open an [RFC](../rfcs/) titled `WG: <name>` with a draft charter
2. Find at least one volunteer lead
3. Get Steward approval (lazy consensus, 7 days)
4. Add a folder under `working-groups/<name>/` with the charter and a meeting log

## Leaving / handing off

WG leads can step down at any time by opening a PR. If a WG has no lead for 60 days, it goes dormant and is archived.
