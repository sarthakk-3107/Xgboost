# 🛢️ Oil and Gas Price Forecasting using XGBoost

This project leverages the power of **XGBoost** to forecast prices for various energy commodities like Brent Oil, Crude Oil WTI, Natural Gas, and Heating Oil. It provides insights into historical trends and applies machine learning techniques for time series forecasting.

## 📁 Dataset

The dataset (`oil and gas.csv`) includes the following columns:

- `Date`: Historical date
- `Symbol`: Type of commodity
- `Open`, `High`, `Low`, `Close`: Market prices
- `Volume`: Trading volume
- `Currency`: Pricing currency

## ⚙️ Workflow Overview

1. **Data Loading and Filtering**
   - Focused separately on each commodity.
   - Filtered by symbol (e.g., Brent Oil).

2. **Preprocessing**
   - Dropped unnecessary columns.
   - Converted date strings to datetime format.
   - Filled missing values.

3. **Modeling**
   - Used **XGBoost** for regression modeling.
   - Trained on historical closing prices.
   - Evaluated using metrics like RMSE.

4. **Visualization**
   - Plotted predictions against actual values.
   - Used Matplotlib and Seaborn for insightful visualizations.

## 🧪 Libraries Used

- `pandas`
- `xgboost`
- `scikit-learn`
- `matplotlib`
- `seaborn`

## 🚀 Getting Started

1. Install required libraries:
   ```bash
   pip install -U xgboost scikit-learn pandas matplotlib seaborn
   ```

2. Run the notebook `Xgb.ipynb` in your preferred environment (Jupyter, Colab, etc.).

## 📊 Results

The XGBoost model provides solid predictive performance for short-term forecasting of commodity prices. Future improvements could include:

- Adding technical indicators as features.
- Exploring other ML algorithms for benchmarking.
- Expanding forecasting horizons with rolling windows.

## 🧠 Author

Sarthak Adhangale  
Master’s in Applied AI, Stevens Institute of Technology
