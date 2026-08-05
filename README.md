# ChapelCloud — company

Private source of truth for ChapelCloud business plans, product direction, decisions, and ops notes.

Marketing site lives in [`home-site`](https://github.com/chapelcloud/home-site). Engineering starts in [`platform`](https://github.com/chapelcloud/platform). Brand assets live in [`brand`](https://github.com/chapelcloud/brand).

## Layout

| Path | What belongs here |
|------|-------------------|
| [`plans/`](plans/) | [Business plan](plans/business-plan.md), [GTM](plans/gtm.md), [goals](plans/goals-2026.md), site briefs |
| [`product/`](product/) | [Roadmap](product/roadmap.md), [personas](product/personas.md), SaaS/MSP/hardware briefs |
| [`decisions/`](decisions/) | Architecture / business decision records (ADRs) |
| [`legal/`](legal/) | Drafts and checklists (no secrets or tax IDs) |
| [`ops/`](ops/) | Vendors, account inventory, runbooks |
| [`people/`](people/) | Roles, on-call model, hiring triggers (no sensitive PII) |

**Start here:** [plans/business-plan.md](plans/business-plan.md) · [decisions/0002-christian-operating-principles.md](decisions/0002-christian-operating-principles.md)

## Conventions

- Prefer Markdown. Link out rather than pasting secrets.
- One decision per file under `decisions/` (see template).
- Do not commit API keys, passwords, bank details, or tax documents — store values in a password manager / cloud secrets and link the *process* here.
