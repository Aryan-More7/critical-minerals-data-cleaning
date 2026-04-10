# Critical Minerals Data Cleaning

Phase 1 of a self-taught data science project built on the IEA
Critical Minerals Dataset.

## What it does

Cleans and restructures a complex multi-sheet Excel file into
analysis ready CSVs used in Phase 2 machine learning.

## Tableau Dashboard

[View live dashboard on Tableau Public](https://public.tableau.com/app/profile/aryan.more3059/viz/RareearthDash_17758144370530/Dashboard1)

## Files

| File | Description |
|---|---|
| `Data_cleansing.ipynb` | Full cleaning code |
| `Critical_Minerals_Dataset.xlsx` | Original raw IEA dataset |
| `demand_clean.csv` | Cleaned demand by mineral and technology |
| `minerals_clean.csv` | Cleaned supply by country |
| `cleantech_demand.csv` | Clean tech demand breakdown |
| `technology_minerals.csv` | Minerals required per technology |

## Outputs

4 clean CSVs used directly in Phase 2:
- `demand_clean.csv` → reshaped and encoded for ML
- `minerals_clean.csv` → supply side analysis

## Related projects

- [Phase 2 — Mineral Demand Predictor](https://github.com/Aryan-More7/mineral-demand-predictor)
  Machine learning model built on this cleaned data. R² 0.807.

## Data source

IEA Critical Minerals Dataset
