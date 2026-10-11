# Warble Cloud — Governance

How decisions get made in the Warble Cloud open community.

## Roles

### Members

Anyone who participates — asks questions in Office Hours, opens issues, comments on PRs, joins Discord. No formal application. Just show up.

### Contributors

Members who have landed at least one merged PR or issue resolution across any [warbletech](https://github.com/warbletech) repo. Contributors get the **Contributor** role on Discord.

### Maintainers

Contributors who have demonstrated sustained, high-quality contributions in a specific area and have been nominated by an existing maintainer. Maintainers can:

- Approve and merge PRs in their area
- Triage issues
- Drive RFCs to a decision
- Vote in community-wide decisions

Current maintainers are listed in each repo's [`MAINTAINERS.md`](https://github.com/warbletech).

### Working Group leads

Each working group has 1–2 leads who set the cadence, agenda, and represent the WG in cross-WG decisions. Leads are nominated within the WG and confirmed by Stewards.

### Stewards

A small group (3–5) responsible for the overall health of the community: dispute resolution, code-of-conduct enforcement, and final tie-breaking on contested decisions. Stewards serve 1-year terms and rotate. Initial Stewards are Warble Cloud's founding maintainers.

## Decision making

Decisions are made by **lazy consensus**: a proposal is accepted if no one objects within the proposal's review window (typically 7 days for RFCs, 48 hours for routine PRs).

If consensus cannot be reached:

1. The proposal is escalated to the relevant Working Group.
2. If still unresolved, escalated to Stewards.
3. Stewards vote; simple majority decides. Stewards must publicly state their reasoning.

## RFC process

Significant changes go through [`rfcs/`](rfcs/). See [`rfcs/README.md`](rfcs/README.md) for the template and lifecycle.

## Adding/removing maintainers

- **Adding** — Any maintainer can nominate a contributor. Lazy consensus among existing maintainers in the area. Confirmed in a PR to the relevant `MAINTAINERS.md`.
- **Removing** — A maintainer can step down at any time by opening a PR. Removal for inactivity (>6 months) or CoC violations is a Steward decision.

## Modifying governance

This document can only be changed via an RFC with explicit Steward approval.

## Conflicts of interest

Maintainers and Stewards employed by the same company should not constitute a majority of any decision-making group. Steward elections will rebalance if a single employer would otherwise hold majority.
