# Energy Efficiency Prediction of Buildings

### Project Overview
* **Dataset:** Energy Efficiency Dataset (UCI)
* **Target Variable:** Heating Load
* **Type:** Multivariate Regression
* **Aim:** Predict heating load using regression and evaluate the effects of regularization.

---

### Tasks

#### 1. Statistical Analysis and Visualization
* **Boxplots:** To identify distribution and potential outliers.
* **Pairplots:** To visualize relationships between building features.
* **Correlation Matrix:** To identify linear dependencies.

#### 2. Multicollinearity Assessment
* Check for multicollinearity using the **Variance Inflation Factor (VIF)**.
$$VIF_i = \frac{1}{1 - R_i^2}$$

#### 3. Preprocessing
* Handle missing values (if any).
* Normalize features to ensure regularization penalties are applied fairly.

#### 4. Model Comparison
* Linear Regression
* Ridge Regression
* Elastic Net (combining L1 and L2 penalties)

#### 5. Validation
* Perform **K-Fold Cross Validation** to ensure model stability across different data subsets.

#### 6. Bias-Variance Analysis
* Analyze the bias-variance tradeoff graphically by plotting training and validation errors against model complexity.

#### 7. Pipeline Integration
* Build an optimized pipeline to automate scaling, VIF filtering, and model training.

---