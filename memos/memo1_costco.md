
# Investment Memo: Costco Wholesale Corporation (Ticker: COST)  (Rough Draft/ Template)
**Author:** Saket Chamarti  
**Date:** [2025-05-25]  
**Recommendation:** BUY / HOLD / AVOID   
**Time Horizon:** 3-5 years  
**Price at time of writing:** $[price]

---

## Executive Summary (≤ 1 page)
- Recommendation: **BUY** (example)
- Target price: $[target] over [T] years (upside: X%)
- Thesis bullets (3–5 short bullets):
  1. Strong recurring membership model and pricing power.
  2. Healthy margin expansion potential via private label + e-commerce.
  3. Conservative balance sheet and high cash generation support buy-and-hold.
- Key risks (2–3 bullets):
  - Commodity/food price shocks compress margins.
  - Competition from Amazon/Walmart on low-margin grocery.
  - Membership attrition if economy weakens.

---

## 1. Company Overview
- Business description: warehouses, membership model, private label (Kirkland), e-commerce, international ops.
- Key segments & % revenue breakdown (FY [year]): U.S. retail X%, Mexico Y%, e-commerce Z%
- Management & strategy: CEO, capital allocation track record (buybacks/dividends).

---

## 2. Industry & Competitive Positioning
- Market size & growth rates.
- Competitors: Walmart (Sam’s Club), Amazon, regional grocers.
- Competitive advantages (moat): membership stickiness, low-cost ops, inventory scale, bargaining power with suppliers.
- Barriers to entry.

---

## 3. Financials — Historical Summary (3–4 years)
- Revenue CAGR: [calc]
- Gross margin, operating margin, net margin trends (table + chart)
- Free Cash Flow (FCF) history (table + chart)
- Balance sheet: Net cash / debt to equity
- Key ratios: ROIC, ROE, current ratio, leverage

*(Put tables & charts — code to generate in `notebooks/dcf_notebook.ipynb`)*

---

## 4. Valuation

### 4.1 DCF (Primary valuation)
**Assumptions**:
- Forecast horizon: 5 years
- Revenue CAGR (FY1-FY5): [x%] (justify with past growth and comps)
- Operating margin: [x%] (explain any expected expansion)
- Tax rate: [x%]
- Reinvestment (CapEx + ΔWorking Capital): [estimate]
- Discount rate (WACC): [x%] — show calculation (see Appendix)
- Terminal growth rate: [x%]

**DCF outputs**:
- Projected FCF (table) Years 1..5
- Discount factors & PV of FCF
- Terminal value (Gordon Growth) and PV
- Implied enterprise value and equity value per share
- Sensitivity table: WACC vs Terminal growth (matrix showing implied per-share values)

*(Attach `results/dcf_outputs.xlsx` and summary table)*

### 4.2 Relative multiples
- Peer group: [WMT, COST, BJ, TGT?]
- P/E, EV/EBITDA, P/S comps — current vs historical percentile
- Conclusion from comps: relative cheap/expensive

---

## 5. Factor Exposure & Alpha (Quantitative check)
- Factor regression: Ri - Rf = α + β_mkt*(Mkt-Rf) + β_smb*SMB + β_hml*HML + ε
- Data and period: Daily returns [YYYY-MM-DD to YYYY-MM-DD]; Fama-French 3 factors (source)
- Regression results (table):
  - α (annualized) = [x%], p-value = [p]
  - β_mkt = [x], β_smb = [x], β_hml = [x]
  - R-squared = [x%]
- Interpretation:
  - If α is positive and statistically significant (p < 0.05) → evidence of idiosyncratic outperformance after adjusting for common factors.
  - If α ≈ 0 and returns explained mostly by market/factors → no persistent idiosyncratic alpha.
- Add factor exposure chart (bar of betas) and cumulative alpha chart.

---

## 6. Risk Analysis
- Operational risk: supply chain, membership churn.
- Financial risk: rising interest rates, margin compression.
- Valuation risk: high multiples vs slower growth.
- Scenario analysis:
  - Base case (assumptions)
  - Downside case (e.g., recession: revenue -5% CAGR, margins -200bps)
  - Upside case (faster e-comm adoption)

---

## 7. Catalysts / Timeline
- 12–18 month catalysts that could unlock value (expansion, private-label initiatives, membership increase).
- Put/Call events (earnings dates, membership announcements, macro events).

---

## 8. Recommendation & Position Sizing
- Buy/Hold/Avoid — reasoning.
- Suggested position size rule (e.g., initial position 2%–5% of portfolio; scale with new information).
- Rebalancing rule & stop-loss (if applicable).

---

## Appendix
- Full DCF spreadsheet & inputs
- Factor regression code & output
- Data sources (SEC filings, 10-K/10-Q, Yahoo Finance, Ken French)
- Detailed financial tables & charts
