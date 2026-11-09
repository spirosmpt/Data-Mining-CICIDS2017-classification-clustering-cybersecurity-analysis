# CICIDS2017 — Intrusion Detection and Data Mining

**Python · Jupyter · Cybersecurity Analytics**

Data-mining coursework analyzing network-flow traffic in the CICIDS2017 dataset, from exploratory analysis and preprocessing to supervised intrusion classification and unsupervised clustering.

## Techniques
- Data cleaning, missing values, exploratory analysis and feature correlations
- Logistic Regression, Decision Tree and Random Forest
- SMOTE class balancing
- PCA dimensionality reduction
- K-Means, hierarchical clustering and DBSCAN

## Reproducing the analysis
The prepared notebook is `notebooks/cicids2017_analysis.ipynb`. The original runs used Google Colab and Google Drive paths; edit the paths for your own environment and obtain the CICIDS2017 CSV files directly from the dataset provider. Large datasets and saved notebook outputs are intentionally not included.

> **Evaluation caveat:** Results should be interpreted in the context of the preprocessing and train/test split used in each experiment. For realistic intrusion detection, avoid data leakage by applying learned preprocessing and SMOTE only on training data.

**Current repository status:** Documentation initialized. The notebook and redacted course report are being transferred from the prepared project archive.

## Author
Spiros Bantis · Electrical & Computer Engineering · University of Patras
