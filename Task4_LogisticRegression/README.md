# Task 4: Logistic Regression for Binary Classification

## Overview
Implemented a logistic regression model to predict customer churn using churn-bigml-80.csv, optimizing for balanced performance.

## Dataset
- **Source**: `churn-bigml-80.csv` from /kaggle/input/churn-dataset/.
- **Features**: Account length, Number vmail messages, Total day minutes, etc.
- **Target**: Churn (True/False)
- **Rows**: 2,666
- **Note**: No missing values; encoded categorical variables and standardized features.

## Steps
1. Preprocessed dataset (encoded Churn, standardized numerical features).
2. Trained logistic regression with class_weight='balanced'.
3. Evaluated with accuracy, precision, recall, and ROC curve.
4. Saved model and predictions.

## Files
- `level2_task1_logisticregression.ipynb`: Kaggle notebook with commented code.
- `churn-bigml-80.csv`: Original dataset.
- `logistic_model.pkl`: Trained model.
- `predictions_logistic.csv`: Actual vs. predicted churn with probabilities.
- `roc_curve.png`: ROC curve visualization.

## Tools
- Python, pandas, scikit-learn, matplotlib

## How to Run
1. Open Kaggle notebook: [Insert Kaggle link].
2. Or install: `pip install pandas scikit-learn matplotlib`.
3. Run `level2_task1_logisticregression.ipynb`.

## Results
- Accuracy: 0.758
- Precision: 0.348
- Recall: 0.722
- ROC AUC: 0.79
- Coefficients and odds ratios show feature impact (e.g., International plan 11.4x odds).
