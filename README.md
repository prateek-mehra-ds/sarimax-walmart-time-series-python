# **🛒 Walmart Sales Forecasting | Time Series with SARIMAX**

This project focuses on forecasting weekly store sales for Walmart over the next 12 weeks using time series modeling techniques, 
primarily SARIMAX. It involves detailed preprocessing per store, stationarity testing, and hyperparameter tuning using statistical 
and programmatic methods.

# 📌 Project Objective

To accurately forecast weekly sales for each Walmart store using time series forecasting and deliver
insights to support business decisions such as inventory planning and promotional strategy.

# 📊 Key Features

✅ Built SARIMAX models tailored to each store's sales data

✅ Conducted ADF and KPSS tests to assess and ensure stationarity

✅ Used ACF and PACF plots to determine the optimal order (p, d, q)

✅ Automated hyperparameter tuning with itertools

✅ Created separate models and forecasts for each store

# 🧠 Methodology

1. Data Preprocessing

Grouped sales data by individual stores

Handled missing values and removed noise

Ensured consistent weekly intervals for each store’s dataset

2. Stationarity Checks

Applied Augmented Dickey-Fuller (ADF) and KPSS tests

Differenced non-stationary series accordingly

3. Modeling

Visualized ACF/PACF plots to estimate model order

Tuned SARIMAX parameters using grid search with itertools

Trained models per store and forecasted next 12 weeks

4. Evaluation

Compared performance via metrics like AIC/BIC

Analyzed forecast stability and seasonal patterns

# 🗂️ Dataset

Walmart historical sales data

Includes weekly sales, store IDs, promotions, and holidays

Dataset is assumed to be pre-downloaded or accessed via script

# 🧪 Libraries Used

pandas – Data preprocessing

numpy – Numerical operations

statsmodels – SARIMAX modeling, ADF & KPSS tests

matplotlib / seaborn – Data visualization

itertools – Model order search automation

# 💡 Future Enhancements

Add exogenous variables (e.g., holidays, promotions)

Implement model comparison (Prophet, LSTM)

Create a dashboard to visualize forecasts
