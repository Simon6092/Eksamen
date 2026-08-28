# Exam project

Exam analysis project, Question 3: a portfolio with a risky and a safe
asset, rebalanced with a no-trade band around a target share, solved by
Monte Carlo simulation and used to study the trade-off between trading
costs and staying close to the target.

## Files

- `PortfolioModel.py` — `PortfolioModel`: draws the risky returns
  (`draw_returns()`), simulates the trading rule for a given band width
  (`simulate()`), and reports the six summary numbers asked for in the
  assignment (`summary()`), plus a helper for the value of 1 invested in a
  single asset over time (`asset_value_paths()`).
- `Results.ipynb` — the single self-contained notebook with all results,
  figures and answers to Question 1, 2 and 3.

## Running

Open `Results.ipynb` in the same folder as `PortfolioModel.py`, and run all
cells from the top ("Restart Kernel and Run All"). No other setup is
required beyond `numpy`, `pandas` and `matplotlib`.
