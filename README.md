# DATA 110 Capstone: Bank Account Fraud EDA

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/momacaes9/data110/blob/main/Data_110_Capstone_Project.ipynb)

Capstone project for **DATA 110 (Intro to Data Science)** at UNC Chapel Hill, Fall 2026.

Exploratory analysis of the **Bank Account Fraud** dataset (synthetic bank account applications labeled with `fraud_bool`):

- Overview of the data with `df.info()` and `df.head()`
- Box plots of `velocity_6h` (application velocity over 6 hours) for fraud vs. non-fraud, with and without outliers
- Correlation heatmap of the numeric features

## Run it

1. Open the notebook in Colab with the badge above.
2. Download the Bank Account Fraud CSV (Kaggle: "Bank Account Fraud Dataset Suite", NeurIPS 2022) to your Google Drive.
3. Update `data_path` in the first code cell and run all cells.

The dataset is not stored in this repo (`*.csv` is gitignored).

**Stack:** Python · pandas · seaborn · matplotlib · Google Colab
