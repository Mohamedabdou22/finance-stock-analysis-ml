# Project 4 — Machine Learning (Finance)

**Goal:** Extend Project 3 using ML:
- Correlate inflation with earnings (monthly, 36 months) via linear regression.
- Sector-level multiple regression with inflation & consumer confidence.
- Hypothesis variable for the sector.
- Model comparison for a single stock closing price: Linear, Polynomial, Random Forest, with a point forecast on a target date.

## Contents
- Notebook with models, metrics (MAE/RMSE/R²), and comparison plots.
- `figures/`: exported charts
- `models/`: optional trained artifacts

## Notes
- Chronological splits; naïve baseline included where appropriate.
- No `pip` cells in public notebook; install via `requirements.txt`.


## Figures
- **Results Metrics:** `figures/results_metrics.png`
- **Model Comparison:** `figures/model_comparison_placeholder.png`

> Replace these placeholders by exporting figures from the notebook to `project4-ml/figures/`.

## CI (GitHub Actions)
This repo includes a workflow that installs dependencies and executes both notebooks to ensure they run end-to-end. If your notebooks fetch data from the web, CI requires network access.




## Results Metrics

Below are placeholder results for the predictive models.  
Once you run your notebook, update these metrics to reflect actual performance.

| Model | MAE | RMSE | R² | Notes |
|--------|-----|------|----|-------|
| Naïve (lag-1) | 2.15 | 3.10 | 0.62 | Baseline (yesterday’s value) |
| Linear Regression | 1.98 | 2.85 | 0.70 | Simple linear model |
| Polynomial (deg=2) | 1.85 | 2.60 | 0.74 | Captures mild nonlinearity |
| Random Forest | 1.50 | 2.10 | 0.81 | Best test performance |

> All metrics computed on the held-out test set. Lower MAE/RMSE = better.
