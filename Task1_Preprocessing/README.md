# Task 1: Data Preprocessing for Machine Learning

## Overview
Preprocessed the House Prediction dataset for machine learning, handling missing data, encoding categorical variables, standardizing numerical features, and splitting into training and testing sets.

## Dataset
- **Source**: House Prediction dataset (`4) house Prediction Data Set.csv`) from Codveda Technology.
- **Features**: CRIM, ZN, INDUS, CHAS, NOX, RM, AGE, DIS, RAD, TAX, PTRATIO, B, LSTAT
- **Target**: MEDV (house price)
- **Note**: Simulated missing data in `CRIM` and `RM`.

## Preprocessing Steps
1. **Missing Data**: Filled with median using SimpleImputer.
2. **Categorical Encoding**: Ensured `CHAS` (binary) is integer.
3. **Standardization**: Standardized numerical features using StandardScaler.
4. **Dataset Split**: 80% training (~404 samples), 20% testing (~102 samples).

## Files
- `task1_preprocessing_house.ipynb`: Kaggle notebook.
- `4) house Prediction Data Set.csv`: Original dataset.
- `X_train_preprocessed.csv`, `X_test_preprocessed.csv`: Preprocessed features.
- `y_train.csv`, `y_test.csv`: Target variables.

## Tools
- Python, pandas, scikit-learn

## How to Run
1. Open Kaggle notebook: [Insert Kaggle link].
2. Or install: `pip install pandas scikit-learn`.
3. Run `task1_preprocessing_house.ipynb`.

## Results
- Training set: ~404 samples
- Testing set: ~102 samples
- Ready for regression tasks (e.g., Linear Regression).
