# Finding the Most Parsimonious Model: Analyzing SplitYield, Happiness Score, and House Prices

## Introduction

This exercise focuses on building and evaluating regression models for three different datasets: SplitYield, Happiness Score, and House Prices. The primary goal was to identify the most parsimonious model—a model that balances simplicity (fewest predictors) with predictive accuracy.

## Datasets

### SplitYield Dataset:
- **Focus**: Agricultural yield predictions.
- **Dependent variable**: `yield_value`.
- **Independent variables**: Features like soil properties, weather metrics, and fertilizer type.

### Happiness Score Dataset:
- **Focus**: Global happiness levels across countries.
- **Dependent variable**: `Happiness Score`.
- **Independent variables**: Factors such as GDP, social support, and health.

### House Prices Dataset:
- **Focus**: Predicting house prices in a residential area.
- **Dependent variable**: `SalePrice`.
- **Independent variables**: Features like `OverallQual`, `YearBuilt`, `GrLivArea`, and `GarageCars`.

## Objectives

### Model Parsimony:
- **Goal**: Identify models that minimize complexity while retaining strong predictive performance.
- **Approach**: Use statistical metric like AIC (Akaike Information Criterion) to assess parsimony.

### Model Evaluation:
- **Metrics**: 
    - RMSE (Root Mean Squared Error)
    - MAE (Mean Absolute Error)
    - R² (Coefficient of Determination)

### Validation:
- **Objective**: Validate models on unseen data to ensure generalizability.

## Methods

### Data Cleaning:
- Handled missing values (e.g., replacing nulls with logical defaults or statistical values).
- Ensured datasets were free of inconsistencies or errors.

### Exploratory Data Analysis (EDA):
- Visualized relationships between predictors and target variables.
- Checked for multicollinearity and feature importance.

### Regression Modeling:
- Built multiple regression models using OLS (Ordinary Least Squares), GLM (Generalized Linear Model) and GLMM (Generalized Linear Mixed Model ).
- Compared models with different sets of predictors to find the most parsimonious one.

### Model Evaluation:
- Assessed residual plots, predicted vs. actual plots, and evaluation metrics.
- Performed normality tests (e.g., Shapiro-Wilk) and other statistical validations.

## Conclusion
- The exercise demonstrated the trade-offs between model complexity and performance.
- By focusing on parsimony, we ensured the models are interpretable and avoid overfitting.
- **Future work** could involve exploring non-linear models, feature engineering, or automated feature selection techniques.

## How to Run the Code

1. **Install the required libraries:**

    see in the files

2. **Run the notebook or script for each dataset**:
    - SplitYield: `Splityield.ipynb`
    - Happiness Score: `Happiness.ipynb`
    - House Prices: `House Prices.ipynb`

3. Results (including evaluation metrics and plots) are saved or printed during execution.

## Key Takeaways

- Parsimonious models strike a balance between simplicity and accuracy, making them ideal for practical applications.
- Proper data cleaning, feature selection, and validation are essential steps for effective modeling.
