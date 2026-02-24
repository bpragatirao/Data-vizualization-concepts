# House Price Prediction using Regularized Regression

### Project Overview
* **Dataset:** California Housing Dataset
* **Target Variable:** Median House Value
* **Type:** Supervised Regression
* **Aim:** Build and compare linear, Ridge, and Lasso regression models to minimize Mean Squared Error (MSE).

---

### Tasks

#### 1. Exploratory Data Analysis (EDA)
* Summary statistics
* Correlation heatmap
* Distribution plots
* Scatter plots of important predictors

#### 2. Handle Missing Values
* Mean/Median imputation
* KNN imputation
* Compare effects on model performance

#### 3. Detect Outliers
* Z-score method
* IQR method
* Isolation Forest

#### 4. Perform Feature Selection
* Correlation threshold
* Recursive Feature Elimination (RFE)
* Lasso-based selection

#### 5. Model Building
* Linear Regression
* Ridge Regression
* Lasso Regression

#### 6. Hyperparameter Tuning
* Perform tuning using Cross Validation (e.g., `GridSearchCV` or `RandomizedSearchCV`).

#### 7. Model Comparison
Evaluate models using the Mean Squared Error formula:

$$MSE = \frac{1}{n} \sum_{i=1}^{n} (y_i - \hat{y}_i)^2$$

#### 8. Pipeline Design
* Design a complete pipeline and justify your best model choice based on performance metrics.

---