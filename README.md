# Inside Sales Compensation Benchmarks — High-Ticket Specialty Equipment

**What to pay a full-cycle inside sales closer at a high-ticket specialty-equipment / trailer dealer** — base, commission structure, on-target earnings (OTE), and pay mix — benchmarked against **real, cited data** (US government wage data + published sales-comp surveys + dealer-industry sources), with a **US-national baseline and a Northeast / Pennsylvania (Lancaster) regional adjustment**.

> **Role this is built for:** a *full-cycle inside sales closer* — someone who takes the inbound call, quotes, and closes the trailer sale over phone/online. Not a pure appointment-setter (BDR), not a field rep, not a manager.

_Last updated: 2026-06-11. Every figure is sourced — see [`sources.md`](sources.md). How the numbers were triangulated: [`METHODOLOGY.md`](METHODOLOGY.md)._

---

## TL;DR — the recommended package

For a solid full-cycle inside trailer-sales closer in the **Lancaster, PA** market (Pine Hill's region):

| Component | Recommendation | Why |
|---|---|---|
| **Base / draw** | **$38k–$45k** (a recoverable draw against commission is acceptable during ramp) | ~60% of target pay; aligns with how dealers and general inside-sales roles actually pay. |
| **Commission** | **20–25% of front-end GROSS PROFIT per unit**, calculated *after* an ~$800–$1,000 "pack," with an accelerator to ~30% above a monthly unit/gross threshold | This is the near-universal equipment-dealer structure — pay on **margin, not sale price**. |
| **Target OTE** | **~$63k–$72k** for a solid closer | Matches the Lancaster median–60th-percentile total cash for this occupation (BLS). |
| **Top-performer ceiling** | Design so a top closer can reach **$90k–$120k** | 75th–90th percentile of the local occupation. |
| **Pay mix** | **~60 / 40** base : variable at target | More conservative than SaaS's 50/50 because physical-goods margins are thinner. |

**National equivalents** run ~6% higher (apply the regional multiplier in reverse — see [`benchmarks/regional.md`](benchmarks/regional.md)).

---

## Headline benchmark — total cash earnings for this role

Total annual cash (base **+** commission) for **Sales Reps, Wholesale & Manufacturing, Except Technical** (BLS SOC 41-4012 — the official occupation a trailer closer maps to). BLS bundles commission into the wage, so these are **total-cash** figures, not base alone.

| Market | 25th pct (entry) | Median (solid) | 75th pct (strong) | 90th pct (top) | Source |
|---|---|---|---|---|---|
| **US national** | $49,040 | **$66,780** | $97,570 | $134,470 | BLS OEWS May 2024 |
| **Pennsylvania** | $48,980 | $65,490 | $98,250 | $132,960 | BLS OEWS May 2024 |
| **Lancaster, PA MSA** | $48,420 | **$63,060** | $87,520 | $127,790 | BLS OEWS May 2024 |

Independent dealer-industry proxies (powersports / RV floor sales) land in the same band — ~$56k–$57k average, $35k–$80k typical range — confirming the BLS read. Full detail and the inside-sales-survey cross-checks are in [`benchmarks/base-and-ote.md`](benchmarks/base-and-ote.md).

---

## Three things that make this role different from a generic "inside sales" job

1. **Pay on gross margin, not revenue.** A $15,000 trailer at ~18% margin is ~$2,700 of gross. At 25% *of gross* that's ~$675 to the rep; at 25% *of revenue* it's $3,750 — more than the entire margin, which is impossible. Equipment dealers pay **20–30% of front-end gross profit** (truck-trailer survey average: 21%). See [`benchmarks/commission.md`](benchmarks/commission.md).
2. **SaaS comp surveys overstate this role by ~2–3×.** RepVue/Bridge Group/Pavilion data says "$135k–$200k OTE" — but that's software pay, inflated by 70–90% software margins. For a physical-inventory dealer, the right anchors are the non-tech sources (PayScale/Indeed/BLS). This repo flags every SaaS-skewed source. See [`METHODOLOGY.md`](METHODOLOGY.md).
3. **Lancaster pays below the national average.** For this occupation, Lancaster runs ~0.94× US median; across all jobs the metro runs ~0.85×. Use **~0.90–0.94×** on national figures. See [`benchmarks/regional.md`](benchmarks/regional.md).

---

## What's in this repo

```
inside-sales-comp-benchmarks/
├── README.md            ← you are here: summary + recommended package
├── benchmarks/
│   ├── base-and-ote.md  ← base salary + total cash, national/PA/Lancaster, by experience
│   ├── commission.md    ← % of gross margin vs revenue, packs, tiers, accelerators
│   ├── pay-mix.md        ← base-vs-variable split + how aggressive to make it
│   └── regional.md      ← national → Pennsylvania → Lancaster adjustment factors
├── data/
│   └── benchmarks.csv   ← every figure in one machine-readable table
├── sources.md           ← all citations, with source-quality / "skews-SaaS" caveats
└── METHODOLOGY.md       ← how the triangulation was done + what data is missing
```

Every number carries a **low / midpoint / high** range (no fake precision) and a source. Where trailer-specific data genuinely doesn't exist publicly, the repo says so plainly rather than inventing it.

---

## Disclaimer & license

This is a **public benchmark reference compiled from public sources**, not professional compensation, legal, tax, or accounting advice. Figures are point-in-time and should be validated against your own unit economics (actual gross margins, close rates, and volume) before being put into an offer or pay plan. Sources are cited so you can check them yourself.

Content and data: free to use and share (CC BY 4.0 — attribution appreciated). Underlying figures belong to their respective publishers (BLS, PayScale, etc.); see [`sources.md`](sources.md).
