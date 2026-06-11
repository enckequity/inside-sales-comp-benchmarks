# Methodology

How the numbers in this repo were gathered, reconciled, and turned into recommendations — and, just as importantly, where the data is genuinely missing.

## The core problem

There is **no single clean source** for "what to pay an inside sales closer at a trailer dealer." The data splits into three imperfect pools, each strong where the others are weak:

| Pool | Strong for | Weak for |
|---|---|---|
| **Government wage data (BLS)** | Pay *levels* and *regional* differences; large, unbiased sample | Can't separate base from commission; no plan *structure* |
| **Inside-sales comp surveys** | Plan *structure* — pay mix, quota multiples, commission logic | Heavily **SaaS/tech-skewed**; dollar levels inflated 2–3× |
| **Dealer-industry sources** | Commission *mechanics* — gross-margin basis, packs, accelerators | Sparse, sometimes dated/anecdotal; rarely trailer-specific |

The method is **triangulation**: take each fact from the pool that's most trustworthy for it, then reconcile.

## How each output was derived

**Pay levels (base + total cash).** Anchored to BLS OEWS SOC 41-4012 (the occupation a trailer closer maps to), which gives total-cash percentiles by geography. Because OEWS bundles commission into the wage, *base salary* was separately read from non-SaaS aggregators (PayScale, Salary.com, Indeed) and the two were reconciled (BLS total-cash median ~$67k national ≈ PayScale base ~$53k + commission). Dealer-floor proxies (powersports/RV at ~$56–57k) confirmed the band.

**Commission structure.** Taken almost entirely from Tier-4 dealer sources, which agree the basis is **% of front-end gross profit**, typically 20–30% (truck-trailer survey average 21%), after a pack of ~$800–$1,200. The general-sales "5–10% of revenue" figure was reconciled to this: ~25% of gross on an 18%-margin unit ≈ ~4.5% of revenue, so the two conventions agree once put on the same basis.

**Pay mix & quota multiple.** Structure borrowed from the SaaS surveys (the only place this is measured well), then adjusted *more conservative* (60/40 instead of 50/50) because thin physical-goods margins can't fund SaaS-style aggression.

**Regional adjustment.** Two BLS signals: occupation-specific (Lancaster sales reps = 0.94× US) and all-occupations (Lancaster = 0.85× US). The occupation-specific figure is weighted more heavily because it matches this exact role; the all-occupations figure sets a floor. Result: **0.90–0.94×**.

## The SaaS-skew correction (most important adjustment)

RepVue, Bridge Group, and Pavilion/QuotaPath are built from software sellers. SaaS pay is inflated by 70–90% software margins, recurring contract values, and VC-funded talent competition — **none of which apply to a dealer selling physical inventory at ~15–20% margin.** Their OTEs ($135k–$200k) run ~2–3× what a trailer closer realistically earns. Every SaaS-derived figure in this repo is flagged; SaaS data is used **only for structure**, never for dollar levels. Dollar anchors come from BLS + non-SaaS aggregators + dealer proxies.

## What's missing (be honest about it)

- **No clean public trailer-floor-closer pay figure.** The one trailer-titled number (Glassdoor "Trailer Sales Representative" ~$121k) is contaminated by semi-trailer / commercial-fleet B2B reps and OEM territory managers, and is *not* used at face value.
- **The right trailer-specific sources are member-gated:** NTDA's Dealer Compensation Survey and NATM's workforce surveys (see [`sources.md`](sources.md)). NTDA also skews toward heavy/semi-trailer dealers — larger ticket than utility/cargo. If you can access these through industry membership, they'd sharpen every number here.
- **Proxy categories carry assumptions.** Powersports/RV/auto are the nearest analogs by unit price and retail-floor model, but they aren't trailers. They're used as cross-checks, not primary anchors.
- **Vintage mismatch.** BLS occupation data is May 2024; the all-occupations regional file is May 2023; some dealer sources are older (the gross-margin convention is stable, but absolute dollars drift ~3–4%/yr).

## How to update this repo

When refreshing (annually, when new BLS OEWS drops each spring):

1. Pull the latest BLS OEWS 41-4012 national/PA/Lancaster figures → update [`benchmarks/base-and-ote.md`](benchmarks/base-and-ote.md) and the headline table in [`README.md`](README.md).
2. Re-check PayScale/Indeed/Salary.com base figures (they shift continuously).
3. Recompute the regional multiplier if a new all-occupations metro file is out.
4. Re-pull every figure into [`data/benchmarks.csv`](data/benchmarks.csv) and bump the "Last updated" date.
5. Dealer-structure sources change slowly — re-verify only if a structure claim is challenged.

Most importantly: **validate against Pine Hill's actual numbers** (real per-unit gross margins, close rates, monthly unit volume). Public benchmarks set the frame; your own unit economics set the plan.
