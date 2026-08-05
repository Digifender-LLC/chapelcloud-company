# Vendors

Preferred tools and gear ladder. No passwords or account numbers here — see password manager and [accounts.md](accounts.md).

Related: [../product/brief-msp.md](../product/brief-msp.md) · [../product/brief-saas.md](../product/brief-saas.md)

---

## Selection ladder (network / security hardware)

When proposing gear to a church, prefer in order:

1. **Whitelabel / private-label** — quality and support acceptable; ChapelCloud-branded experience where honest  
2. **Open-source / open-friendly** — OPNsense, Linux-based appliances, etc., when the customer can be supported  
3. **Ubiquiti** — strong default for many church sizes  
4. **Other commercial** (Meraki, enterprise, Axis, etc.) — when budget, existing campus standard, or scale requires it  

Always match **church size and budget**. Document why a rung was skipped.

**Procurement:** mostly project-based for the customer. Limited stock/resale later for existing customers only — no speculative warehouse in year 1.

---

## Security systems (cameras, access, alarms)

- Prefer platforms with solid remote management and audit logs  
- Clarify privacy expectations in writing (who can view live/recorded video)  
- Year 1: design + remote management; physical install via customer local labor or year 2+  

Exact SKUs TBD per engagement; keep a short “approved for proposal” list in the password-manager vault notes as it stabilizes.

---

## SaaS / integrations (defaults TBD)

Maintain an integration catalog (living doc or section below as picks harden):

| Domain | Candidate approach | Notes |
|--------|-------------------|--------|
| Hosting | Cloudflare Pages / adjacent | Aligns with home-site stack |
| Giving | Hosted checkout partners | Stay out of PCI CHDscope |
| Bookkeeping | Fund-aware tools | Advise/integrate year 1 |
| Email / DNS | Existing registrar + Cloudflare | See accounts.md |
| Identity (later) | Portal auth on platform | Scaffold only |

---

## MSP tooling (choose when first retainer lands)

Evaluate with zero/low capital in mind:

| Need | Examples to evaluate | Pick criteria |
|------|----------------------|---------------|
| RMM | Free tiers / pay-per-endpoint tools | Cost, Linux/Windows mix, remote shell |
| Helpdesk / ticketing | Free tier (e.g. email-first at start) | Sunday visibility, simplicity |
| Documentation | Markdown in private git + customer-facing PDFs | Already our culture |
| Password / secrets | Family password manager | Shared vault discipline |
| Video training | Existing meet tools | Recordability |

Update this table with **Chosen:** once decided (ADR if contentious).

---

## Cloud / company stack (current)

| Vendor | Use |
|--------|-----|
| GitHub `chapelcloud` | Code + company docs |
| Cloudflare | DNS + Pages |
| Domain registrar | chapel.cloud |

---

## Anti-patterns

- Locking a church into gear we cannot support remotely  
- Recommending the shiny enterprise stack to a 50-person church  
- Taking markup on hardware without clear value (just weights)
