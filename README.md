# Breast Cancer Classification & Clustering

ML assignment applying supervised classification and unsupervised clustering 
to the Breast Cancer Wisconsin (Diagnostic) dataset.

## Dataset
[Breast Cancer Wisconsin (Diagnostic) Data Set](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data) 
— 569 samples, 30 numeric features derived from cell nuclei measurements, 
binary diagnosis label (Malignant / Benign).

## Methods
- **Preprocessing:** StandardScaler, stratified 75/25 train-test split
- **Classification:** Random Forest (100 estimators)
- **Clustering:** K-Means (k=2) with PCA (2 components) for visualization

## Results
- Classification accuracy: 97%
- Clusters from K-Means aligned closely with the true diagnosis labels 
  (see `crosstab` output in notebook)

## Files
- `MachineLearningAssignment.ipynb` — full analysis
- `data.csv` — dataset (from Kaggle)