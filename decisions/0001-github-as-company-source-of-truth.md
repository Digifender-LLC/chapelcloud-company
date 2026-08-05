# ADR-0001: GitHub as company source of truth

- **Status:** Accepted
- **Date:** 2026-08-05

## Context

ChapelCloud needs a single place for business plans, product notes, and code. Spreadsheets and chat threads do not version well and get lost.

## Decision

Store company documents and engineering in the `chapelcloud` GitHub org. Start with `company`, `brand`, `platform`, and `home-site`. Prefer Markdown in private repos over ad-hoc cloud docs for durable material.

## Consequences

- Easy audit trail and review via PRs.
- Secrets must stay out of git (password manager / cloud secrets only).
- Contributors need GitHub access to read the business brain.
