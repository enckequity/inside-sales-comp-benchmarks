# Methodology

How this proposal was built, what's a Pine Hill input vs. a cited external benchmark, and where the numbers can be tightened.

## What changed and why

This repo started as a generic "what does an inside sales rep earn" benchmark. Once Pine Hill's real unit economics came to light — **$80k+ built-to-order units, ~$22k–$24k gross each, 10+ units/rep/month** — it became clear the generic benchmarks (which describe ~$2–5k-gross, low-volume units) were the wrong tier. The repo was re-scoped into a **leadership business case** grounded in our actual numbers, with industry data used only where it's genuinely comparable.

## Two kinds of numbers in here

**1. Pine Hill inputs (from Dakota / our systems):**
- Real build sheet: base unit $76,240 price / $56,000 cost (26.55% margin); factory options $10,150 / $6,400 (36.95%); total $86,390 / $62,400 / $23,990 gross (27.8%).
- Unit range: $50k–$130k at "similar margin percentages."
- Volume: "10+ units per month" per closer.
- Current comp: ~$75k salary.
- Lead-flow cost: known to be significant but the exact figure is leadership's to insert.

**2. Cited external benchmarks (public sources, see [`sources.md`](sources.md)):**
- Dealer cost-of-sale norm: salesperson comp = **20–35% of gross produced**.
- Commission paid on **gross margin, not revenue** (~75% of dealers).
- The "$67k median" used as the *counter*-example (wrong tier).
- High-line / RV / equipment top-producer pay context ($150k–$400k+).

## How the recommendation was derived

1. **Compute per-rep gross production** from our units × volume × margin. Deliberately model a **conservative 20% margin** (below our real ~27%) so the case can't be dismissed as optimistic.
2. **Express current pay as cost-of-sale** (comp ÷ gross produced) → ~3–4%, vs. the 20–35% industry norm. This is the core argument.
3. **Set the target pay** below the high-line comparables and far below the literal 20–35% guideline — landing at a conservative ~$195k–$300k — so it's defensible against any "you're overpaying" pushback.
4. **Back into a per-unit rate** ($1,000–$1,250) that delivers that target at realistic volume, chosen as a *closing* rate (inbound) rather than a hunter's rate.
5. **Stress-test** across margin (18–27%), volume (6–15/mo), and rate ($750–$1,500) — the recommendation holds throughout (company keeps ~90%+ of gross in every case).
6. **Pre-empt the three known objections** with the same numbers.

## Conservative-by-design choices

Every modeling choice was made to *understate* the case, so the real situation is even more favorable:
- 20% margin modeled vs. ~27% actual.
- 10 units/mo vs. stated "10+".
- $80k avg vs. units running up to $130k.
- Full $75k base kept (no offsetting cut) when computing the new total.

## What to tighten before the meeting

- **Insert real lead-flow cost** into the [fully-loaded cost-of-sale](economics.md#fully-loaded-with-lead-cost).
- **Confirm average unit price and monthly volume** per rep (we used conservative $80k / 10) — pull from BlackPurl unit-sales data for exact figures.
- **Confirm current comp** structure (we assumed ~$75k salary, minimal/no commission today).
- Optionally pull Pine Hill's **actual blended gross margin** from the unit-sales tracker to replace the 20%/27% bracket with one real number.

The conclusion does not depend on getting these exact — the sensitivity tables show it holds across the whole realistic range — but exact figures make it airtight.

## Honesty notes

- The "$150k–$400k+ high-line producer" range is industry orientation, not a hard survey of trailer-specific pay (trailer-specific high-ticket comp data isn't published publicly; the closest member-gated sources are noted in [`sources.md`](sources.md)). It's used to show *direction*, not as a precise benchmark.
- The literal "20–35% of gross = $500k–$900k" is shown to establish the ceiling, then explicitly set aside as unrealistic — the proposal is intentionally far below it.
