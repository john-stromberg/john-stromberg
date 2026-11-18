I build analytical applications and workflows with python, R, and various AI tools

**[Project portfolio →](https://john-stromberg.github.io/)** ·
**[GitHub](https://github.com/john-stromberg)** ·
**[econkit](https://github.com/john-stromberg/econkit)**

---

## Featured

**[econkit](https://github.com/john-stromberg/econkit)** — R toolkit for applied
economic analysis in asset management and banking. Macro and market data become
recession risk, regime signals, scenario stress, rate/credit analytics, and
governed reports (optional plumber API).

```r
remotes::install_github("john-stromberg/econkit")
library(econkit)
d <- ek_get_series()
predict(ek_recession_model(d, horizon = 12)) |> tail()
```

**value-creation** (`pevc`) — Private · source available on request

Python toolkit for middle-market PE operating partners and deal teams: load portfolio-company financials, diagnose value leakage, size a value creation plan (VCP), and translate it into sponsor returns via library, CLI, and Streamlit dashboard.

- Diagnostics, pricing, working capital, commercial retention, contracts, pipeline, and operations / OEE
- Initiative register and VCP planning with LBO returns and Monte Carlo risk
- Excel analysis packs and audience-specific investment package drafts

## Project collections

| Collection | Focus | Stack |
| --- | --- | --- |
| [Portfolio Analytics](https://github.com/john-stromberg/portfolio-analytics) | Optimization, rebalancing, risk, hedging, attribution (23 projects) | Python / .NET |
| [Fixed Income Analytics](https://github.com/john-stromberg/fixed-income-analytics) | Bonds, municipals, MBS, immunization, credit spreads (8 projects) | Python |
| [Quantitative Research in R](https://github.com/john-stromberg/quant-research-r) | Factors, forecasting, causal inference, allocation (12 projects) | R |
| [Advisor Platform](https://github.com/john-stromberg/advisor-platform) | Meeting prep, proposals, compliance, cashflow, withdrawals (9 projects) | .NET |
| [Wealth Planning Apps](https://github.com/john-stromberg/wealth-planning-apps) | Calculators, dashboards, financial data pipeline (4 projects) | Python / Streamlit |

Each collection keeps projects independent — their own README, dependencies,
tests, and entry points.

## Stack I use often

`Python` · `R` · `.NET` · `Streamlit` · `Quarto` · portfolio & rates analytics ·
model governance patterns

---

Browse the site at **[john-stromberg.github.io](https://john-stromberg.github.io/)**
or open any collection README for setup details.
