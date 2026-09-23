# Linear Regression Mastery
# Linear Regression Mastery: From Foundations to Advanced Econometrics & Machine Learning

A modular repository covering the complete syllabus of Linear Regression in **R** — from foundational OLS and diagnostic assumptions to modern machine learning regularization, Generalized Linear Models (GLMs), and advanced econometric causal inference.

## Repository Architecture & Contents

```text
linear-regression-mastery/
│
├── 01_foundations_ols/                        # Module 1: Foundations & OLS (Ordinary Least Squares)
│   ├── 01_simple_linear_regression.R          # Mathematical derivation, fitting, and coefficients
│   ├── 02_multiple_linear_regression.R        # Matrix and vector interpretation of multiple models
│   └── 03_statistical_inference.R           # t-tests, F-statistics, p-values, and confidence intervals
│
├── 02_diagnostics_assumptions/                # Module 2: Gauss-Markov Assumptions & Diagnostics
│   ├── 01_residual_analysis.R                 # Visual residual analysis and homoscedasticity checks
│   ├── 02_normality_tests.R                   # Shapiro-Wilk, Q-Q plots, and skewness/kurtosis tests
│   ├── 03_heteroscedasticity_robust_se.R      # Breusch-Pagan test and Huber-White robust standard errors
│   ├── 04_autocorrelation_durbin_watson.R     # Durbin-Watson test for sequential data
│   └── 05_multicollinearity_vif.R             # Variance Inflation Factor (VIF) and correlation matrix
│
├── 03_feature_engineering_nonlinearity/       # Module 3: Non-Linearity & Feature Engineering
│   ├── 01_polynomial_regression.R             # Polynomial terms and variable interactions
│   ├── 02_splines_and_gam.R                   # Generalized Additive Models (GAM) for non-linear relationships
│   └── 03_log_transformations.R               # Log-Log, Log-Lin, and Lin-Log models interpretation (Elasticity)
│
├── 04_regularization_ml/                      # Module 4: Machine Learning & Regularization
│   ├── 01_ridge_regression_l2.R             # Ridge penalty (L2): variance reduction and multicollinearity control
│   ├── 02_lasso_regression_l1.R             # Lasso penalty (L1): sparse variable selection
│   ├── 03_elastic_net.R                       # Hybrid L1 + L2 combination
│   └── 04_cross_validation_hyperparams.R      # K-Fold cross-validation for Lambda ($\lambda$) optimization
│
├── 05_generalized_linear_models/              # Module 5: Generalized Linear Models (GLM)
│   ├── 01_logistic_regression.R               # Logistic regression (Odds Ratios, ROC Curve, and AUC)
│   ├── 02_poisson_negative_binomial.R         # Count data modeling and overdispersion handling
│   └── 03_ordinal_multinomial_logistic.R      # Regression for ordered and multiple discrete categories
│
├── 06_econometrics_causal_inference/          # Module 6: Econometrics & Causal Inference
│   ├── 01_panel_data_fixed_random_effects.R   # Panel data analysis (Fixed and Random Effects)
│   ├── 02_difference_in_differences.R         # Difference-in-Differences (DiD) for impact evaluation
│   └── 03_instrumental_variables_2sls.R       # Instrumental Variables and Two-Stage Least Squares (2SLS)
│
└── 07_time_series_forecasting/                # Module 7: Time Series & Trends
    ├── 01_trend_and_seasonality.R             # Linear trend decomposition with seasonal dummies
    └── 02_autoregressive_distributed_lag.R    # ARDL models and temporal lag structures
``` 

## Tech Stack & Dependencies
* Language: R (>= 4.0)

* Core Modeling: stats, broom

* Regularization & Machine Learning: glmnet, caret

* Econometrics & Diagnostics: lmtest, car, plm

* Visualization: ggplot2, patchwork

## Getting Started
Clone the repository and explore the modules progressively to build a solid production-grade pipeline portfolio.
