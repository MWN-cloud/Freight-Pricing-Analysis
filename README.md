# Freight Pricing Analysis

## Overview
Predicts `posted_rate` for loads using a model trained on `train_test.csv`.


## How to Reproduce
Open `Freight_Pricing_Analysis.ipynb` in Jupyter and run all cells. This produces:
- `validation_predictions.csv`
- `december_chart_inputs.csv` with predictions filled in

## How to Score
The command line/terminal produces;
 `candidate_december.png`.

## Notes
Model: Gradient Boost Regressor 

Prophet time series used to predict market index and quote signal
