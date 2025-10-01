# Level 2, Task 2: Decision Trees for Classification

## Overview
Built a decision tree classifier to predict Iris species using iris.csv, with pruning to prevent overfitting.

## Dataset
- **Source**: `iris.csv` from /kaggle/input/iris-dataset/.
- **Features**: sepal_length, sepal_width, petal_length, petal_width.
- **Target**: species (setosa, versicolor, virginica)
- **Rows**: 150
- **Note**: No missing values; all features numeric.

## Steps
1. Preprocessed dataset (encoded species).
2. Trained unpruned and pruned (max_depth=2) decision trees.
3. Visualized tree structures.
4. Evaluated with accuracy and F1-score.
5. Saved model and predictions.

## Files
- `level2_task2_decisiontrees.ipynb`: Kaggle notebook with commented code.
- `iris.csv`: Original dataset.
- `decision_tree_model.pkl`: Pruned model.
- `predictions_decision_tree.csv`: Actual vs. predicted species.
- `unpruned_tree.png`: Unpruned tree visualization.
- `pruned_tree.png`: Pruned tree visualization.

## Tools
- Python, pandas, scikit-learn, matplotlib

## How to Run
1. Open Kaggle notebook: [Insert Kaggle link].
2. Or install: `pip install pandas scikit-learn matplotlib`.
3. Run `level2_task2_decisiontrees.ipynb`.

## Results
- Unpruned Accuracy: ~1.0
- Unpruned F1-Score: ~1.0
- Pruned Accuracy: 0.967
- Pruned F1-Score: 0.966
