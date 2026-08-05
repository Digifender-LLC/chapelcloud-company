# ChapelCloud — company

Private source of truth for ChapelCloud business plans, product direction, decisions, and ops notes.

Marketing site lives in [`home-site`](https://github.com/chapelcloud/home-site). Engineering starts in [`platform`](https://github.com/chapelcloud/platform). Brand assets live in [`brand`](https://github.com/chapelcloud/brand).

## Layout

| Path | What belongs here |
|------|-------------------|
| [`plans/`](plans/) | Business plan, GTM, yearly goals, fundraising notes |
| [`product/`](product/) | Roadmap, personas, feature briefs |
| [`decisions/`](decisions/) | Architecture / business decision records (ADRs) |
| [`legal/`](legal/) | Drafts and checklists (no secrets or tax IDs) |
| [`ops/`](ops/) | Vendors, account inventory, runbooks |
| [`people/`](people/) | Roles, hiring plan (no sensitive PII) |

## Conventions

- Prefer Markdown. Link out rather than pasting secrets.
- One decision per file under `decisions/` (see template).
- Do not commit API keys, passwords, bank details, or tax documents — store values in a password manager / cloud secrets and link the *process* here.
