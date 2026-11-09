# CICIDS2017 — Intrusion Detection & Data Mining

**Python · Jupyter Notebook** · University of Patras · Data Mining coursework

Exploratory network-traffic analysis, cleaning, feature analysis, supervised intrusion classification and clustering using the CICIDS2017 dataset.

## What this project covers

- Python / Jupyter
- network intrusion detection
- data cleaning and EDA
- feature correlation and selection
- Logistic Regression, Decision Tree, Random Forest
- SMOTE
- PCA, K-Means, hierarchical clustering, DBSCAN

## Repository layout

- Redacted course report (PDF) — included in the separate portfolio ZIP archive supplied in the accompanying ChatGPT conversation; not uploaded to this GitHub repository
- Source files:
  - `notebooks/cicids2017_analysis.ipynb`

## Getting started

Install `requirements.txt`, obtain the CICIDS2017 CSV data from the dataset owner, configure the initial notebook paths and run the cells top to bottom. The notebook includes Google Colab-specific setup.

### Data / software dependencies

- CICIDS2017 CSV files; not included in the archive due to dataset size and third-party licensing
- Google Colab / Google Drive path configuration as used in the original notebook

The datasets and any large/generated artifacts have deliberately not been added to version control.

## Technical notes

The original notebook includes two train/test strategies and three classifier families, plus unsupervised clustering experiments.

**Source provenance and execution status:** For a clean repository, stored notebook cell outputs were removed; computation and Markdown cells were retained. Source analysis results and figures remain in the original PDF. This is a presentation cleanup, not a rerun of the analysis.

## Credits

Coursework authored by Spiros Bantis, University of Patras. The original course report (available in the separately provided project archive) remains the reference for the experimental setup and observed results. Refer to the assignment for technical details.


## Report availability

The original coursework report is provided separately as a privacy-redacted PDF in the downloadable project ZIP prepared for this portfolio. Its figures and results have **not** been uploaded to this repository. The source code is available above. The original notebook has been preserved without stored outputs and has not been independently re-executed in this repository; the CICIDS2017 dataset is not bundled.
