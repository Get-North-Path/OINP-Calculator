# What the OINP Calculator does

The **GetNorthPath OINP Calculator** is a free web app that estimates your **Ontario Immigrant Nominee Program** Expression of Interest (EOI) score for the **Workforce Priority** stream.

Live: [oinp.getnorthpath.com](https://oinp.getnorthpath.com)

It is a **mini SaaS**: a focused product with calculators, helper tools, long form guides, occupation and region pages, news, and an optional path into a GetNorthPath consultation. It is **not** a full immigration case management system. That lives on [getnorthpath.com](https://www.getnorthpath.com). See [ABOUT.md](../ABOUT.md).

---

## Problem it solves

On **26 June 2026** Ontario closed the previous OINP streams (Employer Job Offer, Graduate, and Express Entry streams) and replaced them with **Workforce Priority**. The published grid is **11 factors, 130 points** (115 for self employed physicians).

Many third party calculators still score the **closed** streams. Applicants then optimize the wrong factors (including age, which this grid does not score).

This product implements the **July 2026** framework so you can:

1. See a live estimate while you change wage, region, language, and experience
2. Keep **eligibility** (pass / fail gates) separate from **points** (rank in the pool)
3. Read the same topics in guides, occupation pages, and tools without leaving the site

---

## Product surfaces

```
oinp.getnorthpath.com
├── Calculators     score a profile (skilled / essential / physician / compare)
├── Tools           CLB, NOC, wage, tax history band
├── Guides          how the stream works after June 2026
├── Occupations     nurses, developers, PSWs, trades, …
├── Regions         Toronto through Northern Ontario
├── Compare         vs other public calculators
├── FAQ + news      questions and program updates
└── Consult CTA     optional free GetNorthPath call
```

Details: [FEATURES.md](FEATURES.md) · [PATHWAYS.md](PATHWAYS.md) · [SCORING.md](SCORING.md)

---

## What it is

- A **points estimator** aligned to Ontario’s published Workforce Priority grid
- A **content site** (guides, FAQ, news, occupation and region notes)
- A **lead in** to GetNorthPath if you want a human consult
- Available in **10 languages** (English default; others prefixed, e.g. `/fr/…`)

## What it is not

- Not an official Ontario or IRCC tool
- Not a guarantee of an invitation, nomination, or permanent residence
- Not legal advice
- Not the same as **eligibility**. You can have a high score and still fail a minimum (language, experience, employer, licence)
- Not a **CRS / Express Entry** calculator. A nomination may later add **600 CRS** points; that is a federal step. Use GetNorthPath’s [CRS calculator](https://www.getnorthpath.com/tools/crs-calculator) for that grid
- Not AORTrack. [AORTrack](https://track.getnorthpath.com) tracks **PR processing timelines** after you apply federally

---

## How a typical visit goes

1. Land on the hub calculator or a pathway URL
2. Search a **NOC** (or pick physician)
3. Fill wage, Ontario experience, education, language, region, and status
4. Read the running total and any **eligibility warnings**
5. Optionally compare a second scenario (higher wage, Northern Ontario, better CLB)
6. Optionally open a guide, the draws log, or book a free consult

No account is required to score.

---

## Accuracy stance

| Source | Role |
| --- | --- |
| Ontario Regulation **422/17** (as amended) | Legal scoring / stream rules |
| [ontario.ca Workforce Priority page](https://www.ontario.ca/page/ontario-workforce-priority-stream) | Public explanation of the grid |
| IRCC language equivalency charts | Test scores → CLB / NCLC |
| Statistics Canada NOC 2021 | Occupation codes, titles, TEER |

If this app and ontario.ca disagree, **ontario.ca and the regulation win**.

---

## Privacy and leads

Scoring happens in the browser session. Optional consult / alert forms may collect contact details so GetNorthPath can follow up. Those submissions are covered by GetNorthPath [Privacy](https://www.getnorthpath.com/privacy) and [Terms](https://www.getnorthpath.com/terms).

---

## Related GetNorthPath products

| Product | Job |
| --- | --- |
| **OINP Calculator** (this) | Ontario PNP points and education |
| **GetNorthPath platform** | End to end application workspace ($299 CAD) |
| **AORTrack** | Community PR milestone timelines |
| **CRS calculator** | Federal Express Entry ranking |

© GetNorthPath Inc. Not affiliated with IRCC or the Government of Ontario.
