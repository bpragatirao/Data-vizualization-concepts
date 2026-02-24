# Medical Insurance Cost Prediction

### Project Overview
* **Dataset:** Medical Cost Personal Dataset (Kaggle)
* **Target Variable:** Insurance Charges
* **Type:** Mixed Feature Regression
* **Aim:** Predict medical insurance charges using regression models with categorical encoding.

---

### Tasks

#### 1. Exploratory Data Analysis (EDA)
* **Histograms:** To understand the distribution of insurance charges.
* **Boxplots by Category:** Analyzing charges against categorical features like `smoker`, `region`, and `sex`.
* **Correlation Analysis:** Identifying relationships between numerical features like `bmi`, `age`, and the target.

#### 2. Categorical Encoding
* **One-Hot Encoding:** Converting nominal categories into binary columns.
* **Target Encoding:** Comparing model performance when using the mean of the target variable for categories.

#### 3. Influence & Outliers
* Detect influential data points using **Cook’s Distance** to see how individual observations impact the regression model.

#### 4. Model Comparison
* Linear Regression
* Polynomial Regression (capturing non-linear relationships)
* Lasso Regression (L1 Regularization)

#### 5. Evaluation
Evaluate models using the **Coefficient of Determination ($R^2$)**:

$$R^2 = 1 - \frac{SS_{res}}{SS_{tot}}$$

#### 6. Residual Diagnostics
* Perform residual analysis to check for homoscedasticity and normality of errors.

#### 7. Final Pipeline
* Construct a final optimized pipeline that integrates encoding, scaling, and the best-performing regression model.

---