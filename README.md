# ✈️ Air Traffic Passenger & Freight Demand Prediction on Indian Air Traffic Real Time Data

### Industry-Grade Forecasting for Indian Aviation Sector

------------------------------------------------------------------------

## 🚀 Business Problem

India's aviation industry is expanding rapidly, creating challenges in:

-   Airport capacity planning
-   Fleet allocation
-   Route expansion strategy
-   Cargo logistics optimization
-   Infrastructure investment decisions

Inaccurate demand forecasting can lead to: - Underutilized aircraft
capacity
- Revenue leakage
- Operational inefficiencies
- Poor capital allocation

This project develops a **data-driven forecasting system** to predict
air passenger and freight demand in Indian airspace using advanced
machine learning and time-series modeling techniques.

------------------------------------------------------------------------

## 📊 Data Sources

-   **Directorate General of Civil Aviation (DGCA), India** --
    Historical passenger & freight data
-   **World Bank** -- Macroeconomic indicators (GDP, Inflation,
    Population, Exchange Rate, etc.)

### Dataset Overview

-   192 Monthly observations
-   11 engineered features
-   Endogenous + Exogenous variables
-   Cleaned, scaled, and stationarized
-   Correlation and multicollinearity analysis performed

------------------------------------------------------------------------

## 🧠 Solution Approach

### 1️⃣ Data Engineering & Preprocessing

-   Monthly time-step normalization
-   Lag feature creation (6-month & 12-month lags)
-   Rolling averages
-   Log transformation
-   First-order differencing
-   ADF test for stationarity
-   Feature scaling
-   80% training / 20% testing split

------------------------------------------------------------------------

### 2️⃣ Models Evaluated

  Category           Models
  ------------------ ------------------------
  Traditional        SARIMA, VARMAX
  Machine Learning   Random Forest, XGBoost
  Deep Learning      LSTM, GRU

Each model was evaluated using:

-   RMSE (Root Mean Squared Error)
-   MAE (Mean Absolute Error)
-   MAPE (Mean Absolute Percentage Error)
-   R² Score 

------------------------------------------------------------------------

## 🏆 Best Performing Model -- XGBoost

XGBoost demonstrated superior generalization and lower forecasting error
compared to traditional statistical and deep learning models.

### 📌 Domestic Passenger Forecast

-   MAPE: **10.56%**
-   Approximate Forecast Accuracy: **~89%**
-   R² Score: 0.21

### 📌 Domestic Freight Forecast

-   MAPE: **11.93%**
-   Approximate Forecast Accuracy: **~88%**
-   R² Score: 0.42

------------------------------------------------------------------------

## 📈 Business Value Delivered

With forecasting error reduced to ~10--12%:

✔ Supports proactive airport infrastructure planning
✔ Enables optimized fleet and route management
✔ Improves cargo capacity allocation
✔ Assists aviation policy-level strategic decisions
✔ Reduces demand-supply mismatch risk

The model effectively captures non-linear macroeconomic influences on
aviation demand.

------------------------------------------------------------------------

## 🔍 Key Technical Insights

-   Machine Learning models outperformed classical time-series models.
-   Deep learning models underperformed due to limited dataset size (192
    observations).
-   Feature engineering significantly improved predictive performance.
-   Early stopping and regularization prevented overfitting.
-   XGBoost provided the best bias-variance tradeoff.

------------------------------------------------------------------------

## 🛠 Tech Stack

-   Python
-   Pandas & NumPy
-   Statsmodels
-   Scikit-learn
-   XGBoost
-   TensorFlow / Keras
-   Matplotlib / Seaborn

------------------------------------------------------------------------

## 🔮 Future Enhancements

-   Incorporate global macroeconomic indicators
-   Develop hybrid statistical + ML frameworks
-   Deploy via API-based real-time inference system
-   Build executive dashboard for decision-makers
-   Explore Transformer-based time series models

------------------------------------------------------------------------

## 📌 Professional Impact

This project demonstrates:

-   End-to-end ML pipeline development
-   Economic time-series modeling expertise
-   Feature engineering for sequential data
-   Comparative model evaluation
-   Business-aligned forecasting strategy

Applicable to roles in:

-   Aviation Analytics
-   Transport & Logistics Intelligence
-   Infrastructure Forecasting
-   Economic & Demand Modeling
-   Data Science / ML Engineering
