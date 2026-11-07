# Netflix Buyback Stress Test

An interactive stress test of Netflix's share buybacks.

Netflix says it returns only *excess* cash to shareholders: cash above a minimum of about two months of revenue. This page tests that claim on FY2025 numbers. How far can cash flow fall before buybacks at the 2025 pace break Netflix's own minimum-cash rule?

**Live page:** https://su102s.github.io/netflix-buyback-stress-test/

## Key findings

| Content spending | Cash-flow drop | Result |
|---|---|---|
| Kept at 2025 level | ~3% | Cash falls below the 2-month floor → **pause** buybacks |
| Cut to signed contracts only | ~20% | Free cash flow no longer covers 2026 debt + buybacks → **slow down** |
| Cut to signed contracts only | ~25% | Cash falls below the floor → **pause** |

Even with no shock, buybacks at the 2025 pace plus the 2026 debt maturity exceed free cash flow (0.93× coverage).

## What's on the page

- A plain-language explanation of the stress test, using a household budget as the analogy
- A simulator with adjustable cash-flow shock, content cuts, buyback pace and payments for unannounced titles
- A waterfall of where the cash goes, the minimum-cash floor, and a chart of where the verdict changes
- Context on whether the buybacks created value: EPS decomposition and the perpetual growth implied by the buyback price

## Data

Figures come from Netflix's Form 10-K filings (FY2021–FY2025) and the Q3 2023 shareholder letter. The full method, simplifications and sources are listed on the page.

This project extends my section of a university corporate-finance group project. For educational purposes only; not investment advice.
