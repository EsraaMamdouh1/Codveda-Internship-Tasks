# Task 2: Simple Linear Regression

## Overview
Implemented a simple linear regression model to predict stock `close` prices using the stock prices dataset.

## Dataset
- **Source**: `2) Stock Prices Data Set.csv` from Codveda Technology.
- **Features**: open, high, low, volume
- **Target**: close
- **Rows**: 497,472
- **Note**: Handled missing values (open: 11, high: 8, low: 8) with median imputation and standardized features.

## Steps
1. Preprocessed dataset (dropped symbol/date, imputed missing values, standardized features).
2. Trained linear regression with `open` and all features.
3. Evaluated with MSE and R².
4. Visualized predicted vs. actual prices.
5. Saved model and predictions.

## Files
- `task2_linearregression_stock.ipynb`: Kaggle notebook with commented code.
- `2) Stock Prices Data Set.csv`: Original dataset.
- `linear_model_open.pkl`: Trained model (open feature).
- `predictions_open.csv`, `predictions_all.csv`: Actual vs. predicted prices.
- `pred_vs_actual_open.png`: Visualization.

## Tools
- Python, pandas, scikit-learn, matplotlib

## How to Run
1. Open Kaggle notebook: [Insert Kaggle link].
2. Or install: `pip install pandas scikit-learn matplotlib`.
3. Run `task2_linearregression_stock.ipynb`.

## Results
- Single Feature (open): MSE = 2.6418, R² = 0.9997.
- All Features: MSE = 0.5216, R² = 0.9999.
- Visualization shows predicted vs. actual prices.
