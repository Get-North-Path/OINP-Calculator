# Scoring overview

Public summary of the **Workforce Priority** Expression of Interest grid used by the calculator.

- **Legal source:** Ontario Regulation **422/17** (as amended)
- **Public page:** [ontario.ca Workforce Priority stream](https://www.ontario.ca/page/ontario-workforce-priority-stream)
- **Structural baseline in the product:** scoring grid published **20 July 2026**
- **Worker maximum:** **130**
- **Physician maximum:** **115** (no hourly wage factor)

This page is an overview. Band edges (for example $39.99 vs $40) must match ontario.ca.

**Points ≠ eligibility.** Eligibility is a separate pass / fail layer (experience minimums, language floors, education, status, employer or licence rules).

**Age is not scored** on this grid.

---

## The 11 factors (130)

| # | Factor | Max | Notes |
| --- | --- | --- | --- |
| 1 | Occupation TEER | 9 | TEER 0 to 1: 9 · TEER 2 to 3: 6 · TEER 4 to 5: **0** |
| 2 | NOC category (broad occupational category) | 10 | Health 10 · trades and transport 8 · natural and applied sciences 6 · others 2 to 4 |
| 3 | Hourly wage | 15 | Workers only. $40+: 15 · $35 to $39.99: 12 · $30 to $34.99: 10 · $25 to $29.99: 8 · $20 to $24.99: 5 · below: 0 |
| 4 | Ontario experience | 18 | Time in the **offered position** (or physician practice rules). 24+ months: 18 · 13 to 24: 15 · 6 to 12: 12 |
| 5 | Canadian income (tax history) | 8 | Best year in the last five on a CRA Notice of Assessment. $70k+: 8 · $50 to $69,999: 6 · $30 to $49,999: 4 |
| 6 | Status in Canada | 10 | Valid work permit 10 · valid study permit 5 · neither / abroad 0 |
| 7 | Education level | 10 | Doctorate / selected professional degrees 10 · master’s 8 · bachelor / some certificates 5 to 6 · below college or trade 0 |
| 8 | Canadian credentials | 10 | Two or more Canadian post secondary credentials 10 · one 5 · none 0 |
| 9 | Official language (CLB) | 15 | Scored on the **lowest** of the four abilities. CLB 9+: 15 · 8: 12 · 7: 8 · 6: 4 · 5 or below: 0 |
| 10 | Bilingual (EN + FR) | 10 | Both official languages 10 · one 5 |
| 11 | Job / practice region | 15 | Northern Ontario 15 · Eastern / Central outside GTA / Southwestern 10 · GTA except Toronto 5 · City of Toronto 0 |

Check: `9 + 10 + 15 + 18 + 8 + 10 + 10 + 10 + 15 + 10 + 15 = 130`.

Physicians: drop factor 3 (wage, 15) → **115**.

---

## How the calculator groups them

The UI rolls some rows into totals:

| Group | Factors | Worker max |
| --- | --- | --- |
| Occupation | TEER + category | 19 |
| Wage | hourly wage | 15 |
| Experience | Ontario position / practice | 18 |
| Canadian footprint | tax history + status | 18 |
| Education | level + Canadian credentials | 20 |
| Language | CLB + bilingual | 25 |
| Region | location | 15 |
| **Total** | | **130** |

---

## Language tests

Accepted conversions follow **IRCC** equivalency charts (not Ontario specific tables):

- IELTS General
- CELPIP General
- PTE Core
- TEF Canada
- TCF Canada

You can also enter a known CLB. The weakest skill drives language points.

Tool: [CLB converter](https://oinp.getnorthpath.com/tools/clb-converter)

---

## Levers people can still move

After a first score, the factors that usually still move are:

1. **Hourly wage** (workers) relative to the published bands
2. **Region** of the job or practice (Northern Ontario is the top band)
3. **Language** (especially lifting the weakest ability to the next CLB)
4. **Ontario time** in the position or in medical practice
5. **Canadian credentials** or a stronger education band (slower)

Compare those “what ifs” here: [compare scenarios](https://oinp.getnorthpath.com/calculator/compare-scenarios)

---

## What this page will not do

- Publish a “safe score” or invitation cut off before Ontario runs Workforce Priority draws
- Treat competitor calculators as official
- Mix this grid with **CRS**. Nomination → Express Entry is a later federal step

Long form tables: [oinp.getnorthpath.com/guide/eoi-scoring-factors](https://oinp.getnorthpath.com/guide/eoi-scoring-factors)
