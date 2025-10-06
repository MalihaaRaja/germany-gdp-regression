# Germany GDP Per Capita – Linear Regression (1960–2030)

This project fits a linear regression to Germany's GDP per capita data and predicts values for 2026–2030.  
It includes a Jupyter notebook and small CSV datasets.

## Contents
- `notebooks/germany_gdp.ipynb` – data exploration, model fit, plots
- `data/germany_percapita_income.csv` – full simplified dataset (1820–2020)
- `data/germany_gdp_percapita_after_1960.csv` – filtered dataset (>= 1960)
- `requirements.txt` – Python dependencies

## Quickstart
```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
jupyter notebook notebooks/germany_gdp.ipynb


