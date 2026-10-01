## Home Price Direction Prediction

Predicts whether home prices will rise or fall the following month across the 15 largest U.S. metro areas, using macroeconomic indicators (mortgage rates, unemployment, inflation) from FRED and home value data from Zillow's ZHVI.

## Project Overview

This is a binary classification project comparing a Random Forest model against a logistic regression baseline. The pipeline pulls data from the FRED API and Zillow Research, engineers features from the macroeconomic series, and evaluates the models on held-out data from 2022 onward.

## Data Sources

- [FRED API](https://fred.stlouisfed.org): mortgage rates, unemployment, CPI
- [Zillow Research](https://www.zillow.com/research/data/): Home Value Index (ZHVI)

## Contents

- `housing_price_prediction.ipynb`: full data pipeline, feature engineering, and modeling
- `data_dictionary.csv`: field definitions for the final dataset

## Results

Random Forest achieved 88% accuracy and an F1 score of 0.91 on held-out test data (2022 onward), substantially outperforming a logistic regression baseline.
