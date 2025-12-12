# ROOTED Experiences — Vertical Application

This repository powers the **Experiences vertical** for ROOTED.

It is a **curated, governed layer** of guided activities built on:

- `rooted-core` (providers, events, experiences, landmarks)
- `rooted-platform` (governance & safety rules)

Experiences does NOT introduce new markets.  
It reuses existing vendor/institution tiers and tools.

---

## 🧗 What ROOTED Experiences Is

ROOTED Experiences exists to:

- Highlight **guided activities** (tours, classes, adventures)
- Tie experiences back to **approved ROOTED providers**
- Surface **trust & safety** badges clearly
- Use ROOTED’s **seasonal and conditions** engines for guidance

Examples:

- Farm tours
- Workshops
- Outdoor adventures
- Culture-linked experiences

Experiences is:

- ✅ Trust-first
- ✅ Tied to real providers
- ✅ Season + conditions aware
- ❌ Not a random “activity aggregator”

---

## 🔒 Governance Boundaries

This repository:

- ❌ Does **NOT** create new RFQ/bid/bulk systems
- ❌ Does **NOT** redefine Kids Mode
- ❌ Does **NOT** bypass sanctuary / nonprofit protections
- ❌ Does **NOT** change subscription or billing rules

It must obey:

- `ROOTED_PLATFORM_CONSTITUTION.md`
- `ROOTED_VERTICAL_ACCESS_CONTRACT.md`
- `DISCOVERY_RULES.md` + `GEO_RULES.md`
- `MODERATION_SYSTEM.md` (everything is moderated)

Kids & sanctuary laws still apply:

- Kids experiences = education-only, no pricing or booking in Kids UI
- Sanctuaries remain non-commercial, even if they host experiences

---

## 🎯 Vertical Scope

Experiences focuses on:

- Experience **discovery grids & cards**
- **Provider-attached** experience pages
- **Conditions & safety** callouts for each experience (via `vertical_conditions_v1`)
- Clear separation between:
  - Free / included experiences
  - Paid experiences routed through lawful flows

No direct modification of:

- Billing
- RFQ/bids
- Core access controls

---

## ✅ Allowed Work Here

- Designing experience cards & filters
- Building experience detail pages
- Adding safe inquiry flows that call existing core APIs
- Seasonal & conditions-driven UX enhancements
- Accessibility and mobile experience tuning

## ❌ Forbidden Work Here

- “Shadow” booking systems that bypass core
- New payment flows that skip `BILLING_ARCHITECTURE.md`
- Kids-facing UIs with prices or purchases
- Surfacing unmoderated content

---

## 🔗 Source of Authority

Experiences is **a lens**, not a new platform.

Backend authority remains:

- `rooted-core` for behavior
- `rooted-platform` for law

If an Experience conflicts with platform rules →  
**platform rules win**.
