# ChapelCloud — Business Plan

Internal operating document. Not a fundraising pitch.
Last updated: 2026-08-05

Related: [gtm.md](gtm.md) · [goals-2026.md](goals-2026.md) · [../decisions/0002-christian-operating-principles.md](../decisions/0002-christian-operating-principles.md) · [../product/roadmap.md](../product/roadmap.md)

---

## 1. Summary

ChapelCloud is a **family-owned**, Christian-operated company that serves churches and God-focused organizations with:

1. **SaaS** — hosting, giving/donations, bookkeeping, and integrations (primary year-1 wedge)
2. **Remote Managed IT (MSP)** — network, security systems, monitoring, volunteer training
3. **Hardware** — NDI production appliances and e-paper displays (year-2 emphasis; design/prep only in year 1)

We are **pre-formation**, bootstrapping with **zero outside capital**. Year-1 success is reputation and trust in the church community, covering operating costs, and starting a **conversion flywheel** across offers — not building a Tithely competitor or flying nationwide for campus renovations.

**Domain:** chapel.cloud  
**Contact:** hello@chapel.cloud  
**Brand voice:** mission-first, clear, calm ([brand guidelines](../../brand/guidelines/README.md))

---

## 2. Mission, vision, and faith posture

### Mission

Help churches and ministries steward technology faithfully so staff and volunteers can focus on people and the Gospel — not broken Wi‑Fi, opaque giving tools, or Sunday-morning panic.

### Vision

Become a trusted name in church technology: the team ministries call when they need cloud tools, remote IT care, security that protects people and property, and (later) purpose-built hardware managed from one portal.

### Faith posture

We are **fully Christian** in how we work — ethics, pricing honesty, excellence, and care for neighbors. That should be **evident without being overwhelming**. Public surfaces stay calm and welcoming; a non-believer should feel respected, not recruited into a cult aesthetic. See [ADR-0002](../decisions/0002-christian-operating-principles.md).

**Scriptural decision tests** (KJV; used as operating principles, not marketing slogans):

| Principle | Reference | How we apply it |
|-----------|-----------|-----------------|
| Faithful stewardship | 1 Cor 4:2; 1 Pet 4:10 | Treat church data, budgets, and uptime as entrusted gifts |
| Work as unto the Lord | Col 3:23–24; Rom 12:11 | Quality and diligence over flashy SaaS hype |
| Just weights | Prov 11:1 | Market-rate honesty; custom discounts disclosed, never bait-and-switch |
| Visible good works | Matt 5:16 | Excellence that points beyond us; quiet witness |
| Count the cost | Luke 14:28 | Zero-capital plans stay lean and finishable |

### Primary customers

- **Primary:** churches and God-focused organizations of any size
- **Also welcome:** other nonprofits (especially where our stack and ethics fit)
- **Not year-1 focus:** for-profit enterprises, full on-site campus renovations, travel projects

---

## 3. Current stage and constraints

| Fact | Implication |
|------|-------------|
| Pre-formation LLC | Form entity when first paid invoice is imminent |
| $0 capital | Free/cheap stack only; partner/integrate before build; no travel budget |
| Family-owned | Roles and Sunday on-call must be sustainable |
| Founder experience | 5+ churches as volunteer tech; CompTIA Sec+; career tech background |
| Delivery | **National remote-first**; travel out of year 1 |
| Near-term lead | One nonprofit needs website + donations |

These constraints are features of year 1, not temporary embarrassment. Counting the cost means we ship what we can finish well.

---

## 4. Market

### Problem

Churches often run on:

- Consumer-grade gear and volunteer tribal knowledge
- Fragmented SaaS (giving here, calendar there, site elsewhere)
- No Sunday-aware support when live stream or Wi‑Fi fails mid-service
- Security (cameras, access, alarms) sold by vendors who do not understand ministry rhythms
- Budget pressure — especially smaller congregations — with insurance and cyber expectations rising

Managed services broadly are a large, growing market; churches sit in the SMB / nonprofit slice where a full-time IT hire is often six figures and MSPs or specialists are the practical alternative. Pure church ChMS vendors (Tithely, Pushpay, Planning Center, Subsplash, etc.) excel at people/giving/apps; few also own the network closet and incident response.

### Opportunity for ChapelCloud

Own the **intersection**:

- Cloud tools and integrations that fit ministry workflows
- Remote MSP fluency with church calendars and volunteer teams
- Path into hardware and a unified portal later

We do **not** win year 1 by out-featuring national ChMS platforms. We win by trust, responsiveness (including Sundays), and connecting software ↔ infrastructure.

---

## 5. Offers

### 5.1 SaaS (year-1 priority)

| Surface | Year-1 approach |
|---------|-----------------|
| Website hosting | Managed hosting for church/nonprofit sites (leverage Cloudflare / existing stack) |
| Giving / donations | Integrate proven processors and giving partners; we manage setup, branding, and support handoff |
| Bookkeeping | Integrate or advise on fund accounting tools; own ledger product only when justified |
| Integrations | Catalog of preferred tools; ChapelCloud as the glue and steward |
| Platform (build) | Scaffold only: orgs, auth, billing hooks, device registry — modules that create MSP stickiness |

**Out of year 1:** full custom ChMS, mobile app suite, competing feature-for-feature with Tithely/Pushpay.

Detail: [brief-saas.md](../product/brief-saas.md)

### 5.2 Remote Managed IT / MSP (year-1 secondary, still active)

Remote-capable services:

- Network assessment and design (Wi‑Fi, switching, firewall, segmentation for guest/staff/AV)
- Security systems design and remote management (cameras, access control, alarms)
- Monitoring, patching, backup guidance, RMM/MDM where cost allows
- Runbooks and **volunteer training** (video / live remote)
- Incident response with **Sunday service-hour** coverage tiers

**Out of year 1:** travel, on-site cable pulls, full campus “rip and replace” projects.

Detail: [brief-msp.md](../product/brief-msp.md)

### 5.3 Hardware (later)

- NDI production appliances — portal config + monitoring
- E-paper room / wayfinding displays

Year 1: architecture notes, vendor research, customer discovery only. Stock/resell later mainly for existing customers; mostly project procurement.

Detail: [brief-hardware.md](../product/brief-hardware.md)

### Vendor ladder (network / security gear)

1. Whitelabel / private-label where quality and support allow  
2. Open-source / open-hardware friendly stacks  
3. Ubiquiti and similar mid-market  
4. Size/budget exceptions (Meraki, enterprise, etc.) when the church needs them  

---

## 6. Conversion flywheel

```
Lead → SaaS trust ⇄ MSP retainer → (year 2+) Hardware / larger projects
```

Intentional paths:

- SaaS customers who trust us with giving/site invite us into network and security
- MSP customers who love remote care ask us to host the site and unify tools
- Later: pleasant renovation/hardware experiences convert to ongoing MSP (travel/reno year 2+)

Every engagement should leave a clear next invitation — never pressure, always stewardship.

---

## 7. Competitive stance

| Competitor type | Their strength | Our response |
|-----------------|----------------|--------------|
| ChMS / giving platforms | Depth, brand, apps | Integrate, don’t clone; win on infrastructure + Sunday care |
| Generalist MSPs | Scale, tooling | Church fluency, ministry ethics, calm Christian identity |
| AV / security installers | On-site install | Year 1 remote design/management; on-site later or via partners |
| DIY volunteers | Cost | We train and elevate volunteers; we are not replacing vocation, we are supporting it |

---

## 8. Go-to-market (summary)

Remote-first: content, referrals, church networks, and excellent delivery for the first nonprofit lead. Full playbook: [gtm.md](gtm.md).

---

## 9. Pricing and revenue philosophy

- Publish **market-rate “starting at”** ranges where helpful.
- Offer **per-customer custom quotes** so every church size can fit us into budget.
- **Cross-subsidy:** larger churches may pay closer to (or above) list so we can serve smaller ministries at accessible rates — documented per quote, never hidden fees (Prov 11:1).
- Year-1 financial goal: **cover costs**; no fixed revenue target. Reputation is the primary KPI.
- Prefer recurring SaaS + MSP retainers for stability; project work secondary and remote-only in year 1.

Subsidy is intentional outreach, not unstructured undercharging that burns out the family. See ADR-0002.

---

## 10. Operations

### Delivery model

- Remote assessment (questionnaires, video walkthroughs, config exports)
- Remote change windows scheduled around ministry calendars
- Training via recorded + live sessions
- No travel year 1; if a church requires on-site, defer or partner — do not absorb travel cost on $0 capital

### Support

- **7 days / week**, including **Sunday service hours**
- Severity tiers: service-down / worship-blocking vs backlog
- Family on-call rotation with documented limits (see [people](../people/README.md))
- Honesty in SLAs over heroics we cannot sustain

### Stack (lean)

Already in motion: GitHub `chapelcloud`, Cloudflare + Pages, chapel.cloud. Prefer tools with free tiers or usage-based cost that customers fund.

### Legal / risk (pre-formation)

Checklist in [legal/README.md](../legal/README.md). Form entity, get insurance, and use clear MSAs before material liability (especially security cameras / access control advice).

---

## 11. Organization

Family-owned. Founder leads technical delivery, architecture, and customer trust. Additional family capacity for admin, content, and on-call as defined in [people/README.md](../people/README.md). Hire only when recurring revenue covers the role.

---

## 12. Financial realism (year 1)

| Item | Approach |
|------|----------|
| Capital | $0 raise; sweat equity |
| Costs | Domain, Cloudflare, optional RMM/helpdesk — keep minimal; pass-through hardware/licenses |
| Revenue | First hosting/giving engagement; then MSP retainers |
| Break-even | Operating costs covered |
| Avoid | Inventory speculation, travel, building full ChMS before demand |

---

## 13. Risks and mitigations

| Risk | Mitigation |
|------|------------|
| Burnout from 7-day support | Severity tiers, rotation, backlog discipline |
| Scope creep into travel/reno | Written year-1 out-of-scope; say no kindly |
| Competing with ChMS giants | Integrate; own the infrastructure wedge |
| Liability (security/cameras) | Contracts, insurance, documented design limits |
| Underpricing forever | Custom quotes with subsidy notes; review quarterly |
| Pre-formation ambiguity | Form LLC before paid work; bank + invoicing ready |

---

## 14. Year-1 milestones

See [goals-2026.md](goals-2026.md). Headline:

1. Entity + insurance + MSA templates when first invoice is near  
2. Deliver website + donations for the waiting nonprofit  
3. Publish calm Christian + MSP positioning (site brief → later site update)  
4. Land first remote MSP retainer  
5. Document integration catalog and vendor ladder  
6. Measurable name recognition in target church networks (referrals, content reach)

---

## 15. Year 2+ (directional only)

- Travel and full campus network renovations  
- Hardware manufacturing/config + portal monitoring  
- Deeper owned SaaS modules where integrations are insufficient  
- Possible regional partners for on-site install under ChapelCloud design

---

## Document control

Update this plan when stage changes (entity formed, first MSP customer, capital available, or travel policy changes). Prefer ADRs for discrete decisions; keep this file as the narrative spine.
