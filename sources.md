# Sources

Every figure in this repo traces to one of the sources below. Each is tagged with a **quality tier** and a **SaaS-skew flag** so you can weight it appropriately. Compiled 2026-06-11.

## Quality tiers

- **Tier 1 — Government wage data.** Large samples, consistent methodology, no commercial agenda. Best for *levels* and *regional differences*. Limitation: bundles base + commission together.
- **Tier 2 — Salary aggregators (general).** Crowd/employer-reported, not tech-skewed. Good for separating base from commission. Limitation: self-selection, title conflation.
- **Tier 3 — Sales-comp surveys (SaaS-skewed).** Good for *structure* (pay mix, quota multiples, commission logic). **Overstate dollar levels ~2–3× for an equipment dealer** — do not use for dollar figures.
- **Tier 4 — Dealer-industry sources.** Trade press / dealer surveys. Best for *commission structure* (gross-margin basis, packs, accelerators). Limitation: often older, sometimes anecdotal.

---

## Tier 1 — Government wage data (BLS)

| Source | Used for | URL | Date |
|---|---|---|---|
| BLS OEWS 41-4012 national profile | National total-cash percentiles | https://www.bls.gov/oes/current/oes414012.htm | May 2024 |
| BLS OEWS national data file | National 41-4012 + 41-1012 figures | https://www.bls.gov/oes/special-requests/oesm24nat.zip | May 2024 |
| BLS OEWS state data file | Pennsylvania 41-4012 figures | https://www.bls.gov/oes/special-requests/oesm24st.zip | May 2024 |
| BLS OEWS metro data file | Lancaster MSA 41-4012 figures | https://www.bls.gov/oes/special-requests/oesm24ma.zip | May 2024 |
| BLS Occupational Outlook Handbook | Corroboration of national median | https://www.bls.gov/ooh/sales/wholesale-and-manufacturing-sales-representatives.htm | May 2024 |
| BLS OEWS all-occupations (Lancaster MSA) | Regional cost-of-labor multiplier | https://www.bls.gov/oes/2023/may/oes_29540.htm | May 2023 |
| BLS OEWS all-occupations (US) | Regional cost-of-labor baseline | https://www.bls.gov/oes/2023/may/oes_nat.htm | May 2023 |
| BLS OEWS all-occupations (PA) | State cost-of-labor cross-check | https://www.bls.gov/oes/2023/may/oes_pa.htm | May 2023 |
| PA L&I QCEW — Lancaster County 2024 | Regional wage cross-check | https://www.pa.gov/content/dam/copapwp-pagov/en/dli/documents/cwia/products/qcew/qcew%20lancaster%20county.pdf | Sept 2025 |

> **BLS access note:** for May 2024+, BLS retired static per-area HTML tables in favor of the interactive viewer (data.bls.gov/oes) and downloadable XLSX files; direct server fetches of bls.gov return 403. The May 2024 state/metro figures here come from the official downloadable XLSX files (dated 2025-03-11). The May 2023 static pages still resolve as clickable citations.

## Tier 2 — Salary aggregators (general, not SaaS-skewed)

| Source | Used for | URL | Date |
|---|---|---|---|
| PayScale — Inside Sales Representative | Base + total pay | https://www.payscale.com/research/US/Job=Inside_Sales_Representative/Salary | 2026-05-19 |
| Salary.com — Inside Sales Representative I | Base benchmark | https://www.salary.com/research/salary/benchmark/inside-sales-representative-i-salary | 2026-03-01 |
| Indeed — Inside Sales Representative | Base + commission split | https://www.indeed.com/career/inside-sales-representative/salaries | 2026 |
| Glassdoor — Inside Sales Representative | Total comp (partial tech-mix) | https://www.glassdoor.com/Salaries/inside-sales-representative-salary-SRCH_KO0,27.htm | 2026 |
| ZipRecruiter — Powersports Sales | Dealer-floor proxy earnings | https://www.ziprecruiter.com/Salaries/Powersports-Sales-Salary | 2026 |
| RV Rank — RV sales commission/earnings | Dealer-floor proxy | https://www.rvrank.com/post/average-commission-sales/ | 2026 |
| Glassdoor — Camping World RV Sales Associate | Dealer-floor proxy | https://www.glassdoor.com/Salary/Camping-World-RV-Sales-Associate-Salaries-E19691_D_KO14,32.htm | 2026 |

## Tier 3 — Sales-comp surveys (SaaS-skewed — structure only)

| Source | Used for | URL | Date | Skew |
|---|---|---|---|---|
| RepVue — Account Executive salary | OTE ceiling (flagged) | https://www.repvue.com/salaries/account-executive | 2026-06 | SaaS/tech |
| RepVue — SDR salary | Non-closer contrast | https://www.repvue.com/salaries/sales-development-representative | 2026-06 | SaaS/tech |
| Bridge Group — 2024 SaaS AE Benchmark | Pay mix, quota:OTE, commission % | https://blog.bridgegroupinc.com/2024-ae-metrics-compensation-benchmark | 2024 | B2B SaaS only |
| Xactly — Pay mix in sales comp | Pay-mix concept | https://www.xactlycorp.com/blog/compensation/pay-mix-sales-compensation | current | concept (neutral) |
| QuotaPath — Quota:OTE ratio | Quota multiple | https://www.quotapath.com/calculating-ote/ | current | SaaS |
| SalesCookie — Commission rates by industry 2026 | General/mfg commission % | https://blog.salescookie.com/2026/05/01/sales-commission-rates-by-industry-2026/ | 2026-05-01 | No (mfg/distribution) |

## Tier 4 — Dealer-industry sources (commission structure)

| Source | Used for | URL | Date |
|---|---|---|---|
| Trucks Parts & Service — dealer comp survey | 75.4% pay on gross margin; avg 21% | https://www.truckpartsandservice.com/economic-trends/indicators/article/14989063/how-do-your-sales-compensation-plans-compare | recent |
| Farm Equipment — gross-margin pay rationale | 25% of gross; new/used differential | https://www.farm-equipment.com/blogs/6-opinions-columns/post/11512-why-sales-compensation-based-on-gross-margin | 2012 |
| Powersports Business — developing a comp plan | % of gross per unit; draw; graduated tiers | https://powersportsbusiness.com/archives/2004/04/19/developing-a-compensation-plan/ | 2004 |
| AutoFinder — car-salesperson commission | 20–30% of gross; mini; pack | https://autofinder.com/insights/how-much-commission-does-a-car-salesman-make | 2026 |
| Nimble Compensation — what is a "pack" | Pack mechanics/amounts | https://www.nimblecompensation.com/resources/what-is-a-pack | current |
| Netchex — commission pay for auto sales | Draw; tiered-by-units example | https://netchex.com/blog/how-commission-based-pay-works-for-auto-sales-staff/ | current |
| Manufacturers-Representatives.com — commission formulas | General rep commission rates | https://www.manufacturers-representatives.com/article.cfm?ArticleNumber=7 | current |
| Proactive Training Solutions — dealership pay-plan design | Total-comp-as-%-of-production guidance | https://proactivetrainingsolutions.com/dealership-pay-plan-design-compensation/ | current |

## Member-gated (the *right* trailer-specific sources, not publicly retrievable)

These would be the most on-point sources but are behind member walls — noted so you know they exist and can pursue them through industry membership:

- **NTDA (National Trailer Dealers Association) — Dealer Compensation Survey:** https://ntda.site-ym.com/page/DealerSurveys *(skews toward heavy/semi-trailer dealers — larger ticket than utility/cargo)*
- **NATM (National Association of Trailer Manufacturers) — workforce surveys:** https://www.natm.com/dealer-outreach

## Regional / context sources

| Source | Used for | URL | Date |
|---|---|---|---|
| AreaVibes — Lancaster cost of living | COL index (context) | https://www.areavibes.com/lancaster-pa/cost-of-living/ | 2026 |
| Salary.com — Lancaster cost of living | COL index (context) | https://www.salary.com/research/cost-of-living/lancaster-pa | 2026-05-26 |
| ERI — Lancaster cost of living | COL index (context) | https://www.erieri.com/cost-of-living/united-states/pennsylvania/lancaster | 2026 |
| OnPay — PA minimum wage | Wage floor | https://onpay.com/insights/minimum-wage-by-state-summary/pennsylvania/ | 2026 |
| PA Governor newsroom — minimum-wage bill | Legislative status | https://www.pa.gov/governor/newsroom/2026-press-releases/pa-house-passes-bill-to-increase-minimum-wage-following-gov-shap | 2026 |
