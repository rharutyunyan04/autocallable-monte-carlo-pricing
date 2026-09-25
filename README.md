# Autocallable note on Expedia: Monte Carlo pricing and risk

This project prices a 3-year autocallable note on Expedia (EXPE) with Monte Carlo simulation and analyses the risk for the investor. The product, the method and the results are explained step by step in `WSD.ipynb`.

## Files

- `WSD.ipynb`: the code and explanations
- `EXPE.csv`: daily closing prices of Expedia used in the notebook (24 Sep 2021 to 24 Sep 2026)

## How to run

```
pip install numpy pandas matplotlib yfinance
```

Open `WSD.ipynb` and run all cells. Keep `EXPE.csv` in the same folder as the notebook, so no internet connection is needed. The full notebook runs in a few seconds.