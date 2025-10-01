# Level 2, Task 3: K-Means Clustering

## Overview
Applied K-Means clustering to churn-bigml-80.csv for customer segmentation.

## Dataset
- **Source**: `churn-bigml-80.csv` from /kaggle/input/churn-dataset/.
- **Features**: Account length, Number vmail messages, Total day minutes, etc.
- **Rows**: 2,666
- **Note**: No missing values; encoded categorical variables and standardized features.

## Steps
1. Preprocessed dataset (encoded plans, standardized features).
2. Determined optimal k with elbow method (k=3) and silhouette score (0.269).
3. Applied K-Means with k=3.
4. Visualized clusters.
5. Evaluated with silhouette score.
6. Saved model and results.

## Files
- `level2_task3_kmeans.ipynb`: Kaggle notebook with commented code.
- `churn-bigml-80.csv`: Original dataset.
- `kmeans_model.pkl`: Trained model.
- `cluster_assignments.csv`: Cluster labels.
- `elbow_plot.png`: Elbow method visualization.
- `silhouette_plot.png`: Silhouette score visualization.
- `cluster_plot.png`: Cluster scatter plot.

## Tools
- Python, pandas, scikit-learn, matplotlib

## How to Run
1. Open Kaggle notebook: (https://www.kaggle.com/code/esraamamdouh1/kmeans).
2. Or install: `pip install pandas scikit-learn matplotlib`.
3. Run `level2_task3_kmeans.ipynb`.

## Results
- Optimal k: 3
- Silhouette Score: 0.269
