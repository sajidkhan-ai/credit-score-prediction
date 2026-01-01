# 🏦 Credit Score Prediction & Risk Modeling (Profit-Optimized)

# Overview

- This project builds a credit risk prediction model for subprime mortgage lending, focused on maximizing profit under asymmetric business costs rather than accuracy.

    - Profit from good customer: $100

    - Loss from bad customer: $500

# Business Objective

- Maximize lending profitability by predicting default risk and choosing an optimal approval threshold.

# Approach

- Logistic Regression (baseline, interpretable)

- Domain-driven feature binning

- Cost-sensitive threshold optimization

- Model validation using ROC-AUC & KS

- Comparison with Random Forest

# Key Results

- Optimal default probability threshold: 0.12

- Profit improved from $1,200 → $31,500

- Bad loan recall: 84%

- Logistic Regression outperformed Random Forest

# Tech Stack

- Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn

# Key Takeaways

- Accuracy is not the right metric for credit risk

- Business cost optimization is critical

- Interpretable models can outperform complex ones

# Author

- Sajid Khan
