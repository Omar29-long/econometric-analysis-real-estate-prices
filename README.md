# econometric-analysis-real-estate-prices
Applied econometric analysis of real estate price determinants (Sorbonne Data Analytics)
# Econometric Analysis of Real Estate Price Determinants

This project analyzes the determinants of residential real estate prices using applied econometric methods.
It was developed as part of the Sorbonne Data Analytics curriculum (Université Paris 1 Panthéon-Sorbonne).

## Objective
The goal is twofold:
- identify and interpret the main determinants of housing prices
- compare explanatory and predictive econometric approaches

## Dataset
- 150 residential property transactions (2015–2023)
- Variables include structural characteristics, location indicators, and neighborhood attributes
- Target variable: sale price (in thousands of euros)

## Methodology
The analysis follows a progressive econometric approach:
1. Descriptive statistics and exploratory data analysis
2. Linear regression (simple and multiple)
3. Model diagnostics (heteroskedasticity, multicollinearity, autocorrelation)
4. Structural break analysis (Chow test – COVID period)
5. Endogeneity analysis using instrumental variables (2SLS)
6. Regularization methods (Ridge, Lasso)
7. Out-of-sample prediction and confidence intervals

## Tools
Python, Pandas, NumPy, statsmodels, scikit-learn, Matplotlib

## Key Results
- Housing surface is the main price determinant
- Significant structural break detected in 2020 (COVID effect)
- Ridge regression outperforms OLS for prediction
- Evidence of endogeneity for neighborhood quality variables

## Limitations
- Moderate sample size
- Instrument validity relies on economic assumptions
- Results should be interpreted as decision-support insights

## Author
Omar Zeroual
