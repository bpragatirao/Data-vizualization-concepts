# Stock Market Return Prediction

### Project Overview
* **Dataset:** S&P 500 Historical Data
* **Target Variable:** Next-day Closing Price
* **Type:** Time-series Regression
* **Aim:** Predict next-day closing prices using regression models with time-series validation.

---

### Tasks

#### 1. Trend Analysis
* Perform time-series visualization to identify trends, seasonality, and volatility.
* Analyze the stationarity of the price data.

#### 2. Feature Engineering
* **Lag Features:** Creating $t-1, t-2, \dots$ features to capture historical dependencies.
* **Rolling Statistics:** Computing moving averages and rolling standard deviations.

#### 3. Anomaly Detection
* Use **Rolling Z-score** to identify price anomalies or flash crashes within a specific time window.

#### 4. Validation Strategy
* Use **TimeSeriesSplit** (walk-forward validation) instead of standard k-fold to maintain the temporal order of data.

#### 5. Model Building & Comparison
* Linear Regression
* Ridge Regression
* Lasso Regression

#### 6. Evaluation Metric
* Evaluate performance using **Root Mean Squared Error (RMSE)**:

$$RMSE = \sqrt{\frac{1}{n} \sum_{i=1}^{n} (y_i - \hat{y}_i)^2}$$

#### 7. Error Analysis
* Discuss the risks of **overfitting** in a time-series context, specifically focusing on data leakage and look-ahead bias.

#### 8. Predictive Pipeline
* Design a final automated pipeline that handles window-based feature generation and sequential model training.

---