# Methodology

How this proposal was built, what's a Pine Hill input vs. a cited external benchmark, and where the numbers can be tightened.

## What changed and why

This repo started as a generic "what does an inside sales rep earn" benchmark. Once Pine Hill's real unit economics came to light — **$80k+ built-to-order units, ~$22k–$24k gross each, 10+ units/rep/month** — it became clear the generic benchmarks (which describe ~$2–5k-gross, low-volume units) were the wrong tier. The repo was re-scoped into a **leadership business case** grounded in our actual numbers, with industry data used only where it's genuinely comparable.

## Two kinds of numbers in here

**1. Pine Hill inputs (from Dakota / our systems):**
- Real build sheet: base unit $76,240 price / $56,000 cost (26.55% margin); factory options $10,150 / $6,400 (36.95%); total $86,390 / $62,400 / $23,990 gross (27.8%).
- Unit range: $50k–$130k at "similar margin percentages."
- Volume: "10+ units per month" per closer.
- Current comp: ~$75k base **+ a 0.06%-of-sale commission** (≈ $5,760/yr) ≈ **$80,760/yr**.
- Lead-flow cost: known to be significant but the exact figure is leadership's to insert.

**2. Cited external benchmarks (public sources, see [`sources.md`](sources.md)):**
- **The anchor:** dealer-standard commission = **20–30% of front-end gross profit, 25% most common** — confirmed across auto, RV, powersports, and farm/heavy equipment (six independent sources).
- Commission paid on **gross profit, not revenue** (~75% of dealers).
- Store-level cost-of-sale KPIs (equipment ~7% of sales; powersports 18–22% of expenses) — a different denominator, used only as supporting context.
- The "$67k median" used as the *counter*-example (wrong tier).
- High-line / RV / equipment top-producer pay context (RV role $97k–$115k; high-line tier $150k–$400k+).

## How the recommendation was derived

1. **Compute per-rep gross production** from our units × volume × margin. Deliberately model a **conservative 20% margin** (below our real ~27%) so the case can't be dismissed as optimistic.
2. **Express current pay as a share of gross produced** (comp ÷ gross) → ~3–4%, against the dealer standard of 20–30% commission on gross. This is the core comparison.
3. **Set the target pay** below the high-line comparables and well below the 25%-of-gross standard — landing at a conservative ~$195k–$300k — so it's defensible against any "you're overpaying" concern.
4. **Back into a per-unit rate** ($1,000–$1,250) that delivers that target at realistic volume, chosen as a *closing* rate (inbound) rather than a hunter's rate.
5. **Stress-test** across margin (18–27%), volume (6–15/mo), and rate ($750–$1,500) — the recommendation holds throughout (company keeps ~90%+ of gross in every case).
6. **Answer the questions leadership will reasonably raise** with the same numbers, in a collaborative framing.

## A note on framing (corrected during build)

An earlier draft anchored on "total comp = 20–35% of gross produced," which traces to a *general* sales-management source rather than a dealer authority. The brief now anchors on the **per-deal commission standard (20–30% of front-end gross, 25% most common)**, which is independently confirmed across four dealer industries and is the hardest figure for a skeptic to dismiss. Three concepts are kept deliberately separate — per-deal commission rate, store-level cost-of-sale, and take-home earnings — so they can't be conflated.

## Conservative-by-design choices

Every modeling choice was made to *understate* the case, so the real situation is even more favorable:
- 20% margin modeled vs. ~27% actual.
- 10 units/mo vs. stated "10+".
- $80k avg vs. units running up to $130k.
- Full $75k base kept (no offsetting cut) when computing the new total.

## What to tighten before the meeting

- **Insert real lead-flow cost** into the [fully-loaded cost-of-sale](economics.md#fully-loaded-with-lead-cost).
- **Confirm average unit price and monthly volume** per rep (we used conservative $80k / 10) — pull from BlackPurl unit-sales data for exact figures.
- **Confirm current comp** structure (~$75k base + a 0.06%-of-sale commission ≈ $80,760).
- Optionally pull Pine Hill's **actual blended gross margin** from the unit-sales tracker to replace the 20%/27% bracket with one real number.

The conclusion does not depend on getting these exact — the sensitivity tables show it holds across the whole realistic range — but exact figures make it airtight.

## Honesty notes

- The "$150k–$400k+ high-line producer" range is industry orientation, not a hard survey of trailer-specific pay (trailer-specific high-ticket comp data isn't published publicly; the closest member-gated sources are noted in [`sources.md`](sources.md)). It's used to show *direction*, not as a precise benchmark.
- Applying the 25%-of-gross standard literally to ~$2.6M of gross gives ~$500k+, shown to establish the ceiling and then set aside — the proposal is intentionally far below it.
- A visual one-pager of this brief is published via GitHub Pages (`index.html`): https://enckequity.github.io/inside-sales-comp-benchmarks/
