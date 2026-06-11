# Commission Structure

This is the most important file in the repo. For a high-ticket equipment dealer, **how** commission is calculated matters more than the headline rate — and the structure is very different from a generic "X% of sales" plan.

---

## The one rule: pay on GROSS PROFIT, not revenue

The dominant, near-universal structure at equipment dealers is a **percentage of front-end gross profit (margin)** per unit — **not** a percentage of sale price/revenue, and **not** a flat per-unit amount. The evidence converges across truck-trailer, farm, RV, powersports, and auto dealers:

| Source | Finding | Date |
|---|---|---|
| Trucks Parts & Service (dealer survey) | **75.4% of dealers** base commission on **gross margin**; ~60% pay **20–30%**; survey **average = 21% of gross**. Rookies often $30k–$50k year one. | [link](https://www.truckpartsandservice.com/economic-trends/indicators/article/14989063/how-do-your-sales-compensation-plans-compare) |
| Farm Equipment | Most common: **25% of gross margin** (or 25% of gross + small base). New equipment often **15–20%**, used **35–40%**. | [link](https://www.farm-equipment.com/blogs/6-opinions-columns/post/11512-why-sales-compensation-based-on-gross-margin) (2012) |
| RV industry | Reps earn **~20% of gross profit** — "not the actual sale price… calculated on what the dealership earns." Others cite 20–30% of gross. | [link](https://www.rvrank.com/post/average-commission-sales/) |
| Auto (high-volume proxy) | **20–30% of gross profit per vehicle**; mini/minimum $100–$200 when margin is near zero. | [link](https://autofinder.com/insights/how-much-commission-does-a-car-salesman-make) (2026) |
| Powersports | Most common = **% of gross profit per unit**; alternatives include % of selling price, graduated %, % of department profit. | [link](https://powersportsbusiness.com/archives/2004/04/19/developing-a-compensation-plan/) |

### Why margin ≠ revenue (the math)

A **$15,000 trailer at ~18% gross margin = ~$2,700 gross profit.**

| Plan | Calculation | Rep earns | Viable? |
|---|---|---|---|
| 25% of **gross profit** | 25% × $2,700 | **~$675** | ✅ Yes — leaves the dealer ~$2,025 of gross to cover overhead + profit |
| 25% of **revenue** | 25% × $15,000 | $3,750 | ❌ No — exceeds the *entire* gross margin |

Any plan quoting "20–30%" is almost certainly talking about **gross profit**. If you ever express commission as a % of *revenue*, the rate has to drop to low single digits (and even then it ignores margin, so a discounted deal still pays full freight — exactly the behavior you don't want). **Pay on margin and the rep's incentive lines up with the dealer's: protect the gross, don't discount to close.**

---

## The "pack" — deducted before commission is calculated

Dealers subtract a fixed **"pack"** from each deal's gross *before* applying the commission rate, to cover overhead/reconditioning. Typical pack: **$800–$1,200** (some "hard packs" ~$500). [AutoFinder](https://autofinder.com/insights/how-much-commission-does-a-car-salesman-make) / [Nimble Compensation](https://www.nimblecompensation.com/resources/what-is-a-pack)

**Example** — $2,700 gross, $1,000 pack, 25% rate → ($2,700 − $1,000) × 25% = **$425** (not $675).

The pack is the main reason an advertised "% of gross" overstates real take-home. Decide your pack deliberately and disclose it in the pay plan — surprise packs are the #1 source of sales-floor distrust.

---

## Commission-rate cross-check (general / manufacturing)

Outside the dealer world, general inside-sales and manufacturing commission rates run **5–10%**, "frequently calculated on gross profit rather than total revenue." [SalesCookie 2026](https://blog.salescookie.com/2026/05/01/sales-commission-rates-by-industry-2026/) / [Manufacturers-Representatives.com](https://www.manufacturers-representatives.com/article.cfm?ArticleNumber=7). SaaS, by contrast, pays ~11.5% of contract value ([Bridge Group 2024](https://blog.bridgegroupinc.com/2024-ae-metrics-compensation-benchmark)) — but on near-pure-margin software, so it's not comparable.

Note the two "20–25%" vs "5–10%" figures aren't in conflict: **20–25% is of *gross profit*** (dealer convention); **5–10% is of *revenue*** (general-sales convention). On an 18%-margin trailer, 25% of gross ≈ 4.5% of revenue — so they roughly agree once you put them on the same basis.

---

## Tiers & volume accelerators (common, recommended)

Accelerators reward volume and protect against sandbagging. Real examples:

- **Auto, tiered by units:** "Sell **5** cars → **20%** of front-end gross. Sell **12** → **25%**." [Netchex](https://netchex.com/blog/how-commission-based-pay-works-for-auto-sales-staff/)
- **Powersports, graduated:** "**10%** of the first $1,000 of gross, **20%** of everything above." [Powersports Business](https://powersportsbusiness.com/archives/2004/04/19/developing-a-compensation-plan/)
- **Farm equipment, by inventory type:** new **15–20%**, used **35–40%**; some dealers withhold part of the commission until aged inventory actually sells. [Farm Equipment](https://www.farm-equipment.com/blogs/6-opinions-columns/post/11512-why-sales-compensation-based-on-gross-margin)

Apply the accelerator to the **whole month's gross** once a threshold is crossed, so the rep feels the jump.

---

## Recommended commission design (trailer inside closer)

1. **Basis:** % of **front-end gross profit** per unit, after an **~$800–$1,000 pack**.
2. **Base rate:** **20–25%** of post-pack gross (truck-trailer survey average is 21%).
3. **Accelerator:** step to **~30%** once the rep crosses a monthly threshold (e.g., N units or $X cumulative gross), applied to the full month.
4. **Mini/floor:** a **$100–$200 minimum** per unit so thin-margin deals still pay something.
5. **Optional differential:** a higher rate on aged/used or harder-to-move inventory to steer effort.
6. **Sanity-check against OTE:** at ~22% of post-pack gross, the rep needs to generate roughly **$5–$6 of gross for every $1 of commission** — combined with base, that lands a solid closer near the ~$63k–$72k Lancaster OTE in [`base-and-ote.md`](base-and-ote.md). Validate the threshold against Pine Hill's *actual* per-unit margins before locking it in.
