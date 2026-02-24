# Automobile Fuel Efficiency Analysis

### Project Overview
* **Dataset:** Auto MPG Dataset (UCI)
* **Target Variable:** Miles per Gallon (MPG)
* **Type:** Regression with Missing Data
* **Aim:** Build a regression model to predict MPG and study the impact of regularization.

---

### Tasks

#### 1. Exploratory Data Analysis (EDA)
* Perform a detailed analysis of numerical features (weight, displacement, acceleration) and categorical features (origin, cylinders).
* Visualize trends between car attributes and fuel efficiency.

#### 2. Handling Missing Data
* **Mean Imputation:** Filling missing `horsepower` values with the average.
* **Regression Imputation:** Predicting missing `horsepower` values using other available features.

#### 3. Outlier and Influence Detection
* Use **Leverage** to identify observations with unusual predictor values.
* Analyze **Studentized Residuals** to find outliers that deviate significantly from the regression line.

#### 4. Model Comparison
* Linear Regression
* Ridge Regression (L2)
* Lasso Regression (L1)

#### 5. Hyperparameter Optimization
* Use **Grid Search with Cross Validation** (`GridSearchCV`) to find the optimal alpha/lambda values for regularization.

#### 6. Regularization Path Visualization
* Plot the **Regularization Path** to show how coefficient values shrink toward zero as the penalty strength increases.

#### 7. Coefficient Interpretation
* Provide a detailed interpretation of the model coefficients to determine which factors (e.g., car weight vs. origin) most significantly impact fuel efficiency.

---