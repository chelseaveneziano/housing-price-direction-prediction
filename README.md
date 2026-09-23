# housing-price-direction-prediction
Predicts home price direction across 15 U.S. metros using FRED + Zillow data. Random Forest, 88% accuracy.

# Home Price Direction Prediction

Predicts whether home prices will rise or fall the following month across the 15 largest U.S. metro areas, using macroeconomic indicators (mortgage rates, unemployment, inflation) from FRED and home value data from Zillow's ZHVI.

## Project Overview
This is a binary classification project (Random Forest and logistic regression) built for DSC 680 at Bellevue University. Full write-up, methodology, and results are documented in the accompanying white paper.

## Data Sources
- [FRED API](https://fred.stlouisfed.org) — mortgage rates, unemployment, CPI
- [Zillow Research](https://www.zillow.com/research/data/) — Home Value Index (ZHVI)

## Contents
- `housing_price_prediction.ipynb` — full data pipeline, feature engineering, and modeling
- `data_dictionary.csv` — field definitions for the final dataset
- White paper (submitted separately)

## Results
Random Forest achieved 88% accuracy and an F1 score of 0.91 on held-out test data (2022 onward), substantially outperforming a logistic regression baseline.
