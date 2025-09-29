# Task 3: KNN Classifier

## Overview
Implemented a KNN classifier to predict iris `species` using the Iris dataset.

## Dataset
- **Source**: `1) iris.csv` from Codveda Technology.
- **Features**: sepal_length, sepal_width, petal_length, petal_width
- **Target**: species (setosa, versicolor, virginica)
- **Rows**: 150
- **Note**: No missing values; standardized features.

## Steps
1. Preprocessed dataset (encoded species, standardized features).
2. Trained KNN classifier with k=5 and tested k=1–15.
3. Evaluated with accuracy (1.0), confusion matrix, and classification report.
4. Visualized confusion matrix and accuracy vs. k.
5. Saved model and predictions.

## Files
- `task3_knn_iris.ipynb`: Kaggle notebook with commented code.
- `1) iris.csv`: Original dataset.
- `knn_model.pkl`: Trained KNN model (k=5).
- `predictions_knn.csv`: Actual vs. predicted species.
- `knn_accuracy_vs_k.png`, `confusion_matrix.png`: Visualizations.

## Tools
- Python, pandas, scikit-learn, matplotlib, seaborn

## How to Run
1. Open Kaggle notebook: [Insert Kaggle link].
2. Or install: `pip install pandas scikit-learn matplotlib seaborn`.
3. Run `task3_knn_iris.ipynb`.

## Results
- Accuracy: 1.0
- Confusion matrix: [[10, 0, 0], [0, 9, 0], [0, 0, 11]]
- Classification report: Precision, recall, F1-score all 1.0
- Visualizations confirm perfect classification.
