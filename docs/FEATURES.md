# Features

Everything the public OINP Calculator ships today. Paths are English (unprefixed). Other locales use `/{locale}` (example: `/fr/guide/what-is-oinp`).

Base URL: [https://oinp.getnorthpath.com](https://oinp.getnorthpath.com)

---

## Calculators

| Page | Path | Notes |
| --- | --- | --- |
| All pathways hub | `/` | Worker or physician; full 11 factor form |
| Skilled TEER 0 to 3 | `/calculator/skilled-teer-0-3` | Management, professional, technical job offers |
| Essential TEER 4 to 5 | `/calculator/essential-teer-4-5` | Essential occupations; TEER factor is 0 (practical ceiling ~121 / 130) |
| Physicians | `/calculator/physicians` | No job offer; max **115** |
| Compare scenarios | `/calculator/compare-scenarios` | Up to three profiles, per factor diffs |

See [PATHWAYS.md](PATHWAYS.md).

---

## Tools

| Tool | Path | What it does |
| --- | --- | --- |
| CLB converter | `/tools/clb-converter` | IELTS, CELPIP, PTE Core, TEF, TCF → CLB / NCLC and language points |
| NOC and TEER finder | `/tools/noc-teer-finder` | Search NOC 2021 unit groups; TEER + occupation points |
| Wage lookup | `/tools/wage-lookup` | Median wage by occupation / region; wage point context |
| Tax bracket estimator | `/tools/tax-bracket-estimator` | Convert pay to annual; map to OINP income tax history bands |
| CRS calculator | GetNorthPath site | Federal CRS, not this grid: [getnorthpath.com/tools/crs-calculator](https://www.getnorthpath.com/tools/crs-calculator) |

---

## Guides

| Guide | Path |
| --- | --- |
| What is OINP | `/guide/what-is-oinp` |
| Workforce Priority stream | `/guide/ontario-workforce-priority-stream` |
| EOI scoring factors | `/guide/eoi-scoring-factors` |
| Eligibility requirements | `/guide/eligibility-requirements` |
| How to apply | `/guide/how-to-apply` |
| Job offer requirements | `/guide/job-offer-requirements` |
| Language / CLB | `/guide/language-clb-requirements` |
| Competitive EOI score | `/guide/competitive-eoi-score` |
| Northern Ontario bonus | `/guide/regional-bonus-northern-ontario` |
| Wage points | `/guide/wage-points-explained` |
| Income tax history points | `/guide/income-tax-history-points` |
| Education and credentials | `/guide/education-credential-points` |
| OINP vs Express Entry | `/guide/oinp-vs-express-entry` |
| OINP vs other PNPs | `/guide/oinp-vs-other-pnp` |
| EOI draw history | `/guide/eoi-draws-history` |
| Documents checklist | `/guide/documents-checklist` |
| Processing times | `/guide/processing-times` |
| Refusals and next steps | `/guide/refusal-appeals` |
| Nomination to PR | `/guide/nomination-to-pr` |

---

## Occupations

| Occupation | Path |
| --- | --- |
| Registered nurses | `/occupations/registered-nurses` |
| Software developers | `/occupations/software-developers` |
| Personal support workers | `/occupations/personal-support-workers` |
| Truck drivers | `/occupations/truck-drivers` |
| Cooks and food service | `/occupations/cooks-food-service` |
| Construction and trades | `/occupations/construction-trades` |
| Early childhood educators | `/occupations/early-childhood-educators` |
| Physicians | `/occupations/physicians` |

---

## Regions

Regional points are based on **job / practice location**, not where you live today.

| Region | Path | Typical regional points |
| --- | --- | --- |
| Northern Ontario | `/regions/northern-ontario` | 15 / 15 |
| Ottawa (Eastern) | `/regions/ottawa` | 10 |
| Waterloo Kitchener | `/regions/waterloo-kitchener` | 10 |
| Windsor | `/regions/windsor` | 10 |
| Hamilton | `/regions/hamilton` | 10 |
| Toronto | `/regions/toronto` | 0 |

GTA outside Toronto is **5** on the published grid (Mississauga, Brampton, Markham, and similar). See [SCORING.md](SCORING.md).

---

## Other pages

| Page | Path |
| --- | --- |
| FAQ | `/faq` |
| News | `/blog` |
| vs ImmigraTools | `/compare/immigratools` |
| vs ImmiCalculator | `/compare/immicalculator` |
| vs CRSCalculate | `/compare/crscalculate` |
| Book a consult | `/#consult` |

Machine indexes: `/sitemap.xml`, `/robots.txt`, `/llms.txt`.

---

## Languages

| Code | Language | URL shape |
| --- | --- | --- |
| `en` | English | `/…` (no prefix) |
| `fr` | French (Canadian) | `/fr/…` |
| `es` | Spanish | `/es/…` |
| `pt` | Portuguese | `/pt/…` |
| `ar` | Arabic (RTL) | `/ar/…` |
| `ur` | Urdu (RTL) | `/ur/…` |
| `hi` | Hindi | `/hi/…` |
| `pa` | Punjabi | `/pa/…` |
| `tl` | Tagalog | `/tl/…` |
| `zh` | Chinese | `/zh/…` |

NOC **job titles** in search tools stay English (official StatCan list) even when the chrome is translated.

---

## What we deliberately do not add

- Paywalls on the core calculator
- Invented invitation cut offs before Ontario publishes draws
- Age as a scoring factor (not on this grid)
- Affiliation badges that imply this is an Ontario or IRCC product
