# S&P 500 CRM Analytics

This project analyses S&P 500 shares using weekly risk-return features and adapted Recency, Frequency and Monetary (RFM) features. It compares Ward hierarchical clustering and K-Means, reviews sector composition, and tests how removing Monetary affects the RFM clusters.

## Files

- `CW1_CRM.ipynb` — data preparation, feature engineering, clustering and analysis
- `cw1_data_snapshots.zip` — exported data snapshots
- `data_mart_diagram.jpg` — proposed analytics data mart diagram

## Running the notebook

Open `CW1_CRM.ipynb` in Google Colab and run the cells from top to bottom. The notebook uses Python libraries including pandas, NumPy, yfinance, Matplotlib, Seaborn, SciPy and scikit-learn. Data retrieval requires internet access.

The notebook uses the S&P 500 constituent list from Wikipedia and market data retrieved from Yahoo Finance via yfinance. Since the current constituent list is applied retrospectively to the 2021–2024 study period, the analysis may be affected by survivorship bias.
