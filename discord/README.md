# Discord — Warble Cloud server

Server invite: **[warblecloud.com/discord](https://warblecloud.com/discord)** (resolves via on-domain redirect — target lives in `NEXT_PUBLIC_DISCORD_INVITE`).

## Files in this folder

| File | Where it goes |
|---|---|
| [`welcome.md`](welcome.md) | Pin to `#welcome` channel |
| [`rules.md`](rules.md) | Pin to `#rules` channel |
| [`onboarding-bot-replies.md`](onboarding-bot-replies.md) | Auto-replies for onboarding bot (MEE6 / Carl-bot) |
| [`first-post.md`](first-post.md) | Your first `#announcements` post when you go live |

## Server structure

See [the Discord setup playbook in warble-core CLAUDE notes](https://github.com/warbletech/warble-core) — channel layout, roles, GitHub webhook wiring.

## Vanity URL plan

Goal: `discord.gg/warblecloud` (= `discord.com/invite/warblecloud`).
Requires **Server Boost Level 3** (14 boosts). Until then, run with the regular permanent invite and update `NEXT_PUBLIC_DISCORD_INVITE` env var when ready — `/discord` short-link auto-follows.
