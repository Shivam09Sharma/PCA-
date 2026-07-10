# S&P 500 Factor Analysis: Uncovering Market Drivers with PCA

## Project Overview
This project applies quantitative financial analysis and unsupervised machine learning to the S&P 500. The objective is to move beyond basic stock metrics and identify the hidden macroeconomic factors that drive broad market movements.

## Methodology
1. **Exploratory Data Analysis (EDA):** Calculated daily returns, volatility, and cumulative growth for major market leaders (AMZN, MSFT, NVDA).
2. **Correlation Analysis:** Mapped the price relationships and statistical correlations between these tech equities.
3. **Principal Component Analysis (PCA):** Scaled the analysis to the broader S&P 500 dataset to extract unobservable market factors. Processed a wide matrix of daily returns, handled missing data, and standardized inputs for the machine learning pipeline.

## Key Insights
* **Tech Cohesion:** Demonstrated strong positive correlation and clustered growth trends among top technology equities during the observed timeframe.
* **The Market Factor:** PCA revealed that a single principal component (PC1) explains a dominant percentage of variance across the entire index. This validates the quantitative finance theory of a primary, broad-market macroeconomic driver influencing highly correlated equities.

## Technologies Used
* **Python** (Pandas, NumPy)
* **Scikit-Learn** (PCA, StandardScaler)
* **Matplotlib** (Data Visualization)
