# quant-stack

**Quantitative research & portfolio analytics repo**  
Author: Saket Chamarti  
Purpose: reproducible quant research, backtesting, valuation memos, and deployable portfolio analytics.

---

## Project overview

This repository contains:
- `memos/` — polished investment memos (PDFs).
- `notebooks/` — Jupyter notebooks for DCF, factor regression, backtesting demos.
- `src/` — modular Python code for portfolio construction, factor models, and stress tests.
- `data/` — (not checked in) raw price data, factor files (Fama-French), model outputs.
- `tests/` — unit tests for logic (backtest integrity checks).
- `infra/` — simple IaC skeleton (Terraform / CloudFormation) or deployment recipes.
- `requirements.txt` — python package list.

Goal: ship three memos + live Streamlit demo + cloud-deployable scoring pipeline.

---

## Quick start (develop locally)

1. Clone:
```bash
git clone git@github.com:<your-org>/quant-stack.git
cd quant-stack
