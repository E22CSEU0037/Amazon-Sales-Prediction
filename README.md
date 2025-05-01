### 📈 Amazon Sales Forecasting Using Machine Learning

This project focuses on forecasting monthly sales for Amazon using a combination of time series analysis and ensemble machine learning techniques. Accurate sales predictions are critical for e-commerce businesses to improve inventory planning, reduce operational costs, and make informed marketing and budgeting decisions.

### 🔍 Project Overview

- **Goal:** Predict monthly sales using historical data to support business decision-making.
- **Techniques Used:** Time series preprocessing, feature engineering, ARIMA/SARIMA/Prophet models, ensemble learning (Extra Trees, XGBoost), and stacking.
- **Performance:** Achieved an R² score of 0.99 and 100% forecast accuracy within a 30% tolerance using a stacked regression model.

### 🧰 Key Features

- Data preprocessing: Handling missing values, resampling, outlier treatment
- Feature engineering: Lag features, rolling means, seasonal encoding (sin/cos)
- Time series models: ARIMA, SARIMA, Prophet
- Machine learning models: Extra Trees Regressor, XGBoost
- Model evaluation: MAE, RMSE, R² Score, custom accuracy within tolerance thresholds
- Forecast visualization: Plots with confidence intervals and future sales predictions

### 📊 Use Cases

- Demand forecasting for e-commerce platforms
- Inventory optimization
- Marketing campaign planning
- Business trend analysis

### 🛠️ Tech Stack

- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Scikit-learn
- XGBoost
- Statsmodels (ARIMA/SARIMA)
- Prophet (by Meta)
