# Brief — Hardware

Product brief for ChapelCloud connected hardware (later emphasis).
Related: [roadmap.md](roadmap.md) · [../plans/business-plan.md](../plans/business-plan.md) · [../../platform/docs/domains.md](../../platform/docs/domains.md)

---

## Intent

Ship purpose-built devices that live in ministry spaces and are managed from the ChapelCloud portal — starting with **campus display management** appliances and **e-paper room displays**.

Year 1 is **research, architecture, and customer discovery only**. No inventory speculation on $0 capital.

---

## Products (directional)

### Campus display management

Appliances that drive and steward screens across campus (sanctuary, classrooms, lobbies, shared rooms, study areas). Public wording stays plain — “campus display management,” not jargon-first.

**Capabilities (directional):**

| Capability | Notes |
|------------|--------|
| Live production video | Ingest / output for live production over the church network (including NDI where that stack fits) |
| Cloud media | Presentations, videos, and scheduled content pushed from the ChapelCloud portal |
| Display control | CEC (and similar) to power, switch inputs, and keep connected displays under remote care |
| Casting | Optional casting for shared rooms and study areas, depending on site configuration and policy |

**Depends on:** sane network design (MSP), device registry on platform, portal media/scheduling UX.

### E-paper room displays

Low-power room signs (calendar / availability); NFC to update via portal.

**Depends on:** org calendar integrations, device registry, physical mounting (often on-site — year 2+ for us).

---

## In scope (year 1)

- Capture requirements from MSP/SaaS conversations  
- Vendor ladder: whitelabel → OSS → commercial  
- Platform device-registry design notes  
- Rough BOM / margin thinking (no purchasing stock)  

## Out of scope (year 1)

- Manufacturing at scale  
- Guaranteed delivery dates to customers  
- Travel for install  
- Large warehouse inventory  

**Resale later:** primarily to existing customers; mostly project procurement.

---

## Success metrics (year 1)

- Written requirements from ≥1 real church conversation  
- Clear dependency list on MSP and platform  
- Explicit year-2 go/no-go criteria (capital, demand, portal readiness)  

---

## Risks

| Risk | Note |
|------|------|
| Selling hardware before portal exists | Avoid; under-promise |
| AV rabbit holes | Stay display-management focused (screens + media + control); do not become a full house-of-worship AV firm overnight |
| Casting / content policy complexity | Configuration and ministry policies matter; document defaults |
| On-site install dependency | Pair with year-2 travel/partner plan |
