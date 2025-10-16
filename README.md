# Finance Stock Analysis and Machine Learning

<p align="center">
  <a href="https://colab.research.google.com/github/Mohamedabdou22/finance-stock-analysis-ml/blob/main/project4-ml/n01527876_project4.ipynb" target="_blank">
    <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10-blue"/>
  <img src="https://img.shields.io/badge/License-MIT-green"/>
  <img src="https://img.shields.io/badge/Status-Completed-brightgreen"/>
</p>

<p align="center">
  <img src="project4-ml/figures/results_metrics.png" alt="Results Snapshot (Test Set)" width="600"/>
  <br>
  <em>Figure 1: Model performance comparison on test set.</em>
</p>

---

**Author:** Mohamed Abdou  
**Tools:** Python, Pandas, Matplotlib, scikit-learn, yfinance  
**Topics:** Exploratory Data Analysis (EDA), Financial Ratios, Linear Regression, Polynomial Regression, Random Forest, Predictive Modeling  

This repository contains two connected projects from my Data Science coursework at the **University of North Florida**:

- **Project 3 (EDA):** explores Microsoft's and peer tech stocks’ price-to-earnings ratios, revenues, and the impact of COVID-19.  
- **Project 4 (Machine Learning):** extends that analysis with regression models and model comparisons.

> Classroom note: Any package installs are expected to be done in the environment, not inside notebooks.  
> Public versions of these notebooks do **not** run `pip` cells.

---

## 🧩 Structure

- `project3-eda/` – EDA notebook and figures  
- `project4-ml/` – ML notebook, figures, and model artifacts  
- `data/` – pointers to data sources (no raw data checked in)

---

## ⚙️ How to Run

```bash
python -m venv .venv
# Windows:
.venv\Scripts\activate
# macOS/Linux:
source .venv/bin/activate

pip install -r requirements.txt
jupyter lab

Open the notebooks in `project3-eda/` and `project4-ml/`.

## Data Sources
- Yahoo Finance via `yfinance`
- U.S. Bureau of Labor Statistics (CPI)
- Conference Board Consumer Confidence Index

## License
MIT License © 2025 Mohamed Abdou
