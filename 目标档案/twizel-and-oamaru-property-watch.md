# Twizel and Oamaru property watch

Goal ID: goal_ae6eb5127bc8
Goal slug: twizel-and-oamaru-property-watch

## Description
Weekly tracking of second-hand housing in Twizel and Oamaru, New Zealand, covering new listings, sales, bedroom counts, prices, and locations. Every Monday morning (NZ time) a Chinese-language report compares the market against the baseline snapshot and flags only real changes.

## Scope & format rules (set by Kin, 2026-11-16)
- **Houses only**: second-hand residential properties with a dwelling. Land/sections/bare blocks are NEVER collected or reported — no land listings, land sales, or land price changes. (Platform totals may be quoted with an "all types" caveat, but per-property lists are houses only.)
- **Per-property detail is mandatory**: every new listing and sale is listed individually with address, asking/sold price, bedrooms, bathrooms, floor area (when published), land area, and listing/sale date; price cuts and sale-method changes likewise per property.
- **Detail standard**: the delivered report body must match the full detailed format kept in ~/workspace/market-watch/nz-property/snapshot.md (per-town sections, per-property lists, stats, rates & market environment, hot/cold verdict) — never a summary-only digest. The dashboard syncs the full text.
- B&B-investment lens: flag likely B&B-suitable homes (many beds/baths, holiday locations) in one line; yield conclusions follow Kin's own model only.
