# S&P 500 CRM Analytics

Coursework project applying customer relationship management and clustering methods to S&P 500 share data. The notebook calculates share-level risk-return and trading-activity features, compares clustering methods, and examines cluster composition.

## Repository contents

- `CW1_CRM.ipynb` — analysis notebook, including data preparation, validation, feature engineering, clustering and visualisations.
- `algorithm_comparison.csv` — comparison of clustering algorithm results.
- `cluster_assignments.csv` — share-level cluster labels.
- `common_feature_table.csv` — feature values for shares included in the common analysis set.
- `exclusion_log.csv` — shares excluded from the analysis and the recorded reasons.
- `feature_table.csv` — calculated share-level features.
- `monetary_profile_comparison.csv` — comparison of monetary profiles across selected cluster solutions.
- `package_versions.csv` — software package versions recorded for the analysis.
- `run_metadata.csv` — analysis run and study-period metadata.
- `sector_composition.csv` — sector composition of the selected clusters.
- `validation_summary.csv` — summary of data and feature validation checks.
- `weekly_returns.csv` — weekly share and benchmark return data used in the risk-return analysis.

## Data and reproducibility

The notebook retrieves market data using Yahoo Finance through `yfinance` and obtains S&P 500 constituent information as documented in the notebook. The CSV files in the repository are supporting analysis outputs.

The large daily data snapshots were omitted from the repository because of their file size. As a result, rerunning the notebook may require internet access and a fresh data download. Data availability can change; some tickers may fail to download and are handled as exclusions in the notebook.

## Running the notebook

Open `CW1_CRM.ipynb` in Google Colab or Jupyter Notebook and run the cells from top to bottom. The notebook records its package versions and includes the data validation and exclusion steps.

## Data-use note

This project is for coursework and analytical demonstration. Cluster assignments are descriptive and should not be treated as investment advice.
