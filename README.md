# bankEDA

This is an Exploratory Data Analysis (EDA) project based on anonymized banking customer data. The objective was to generate insights into customer financial behavior, income levels, and banking preferences.

Dataset:

The dataset includes anonymized customer information with features such as:

  Demographics: Age, Occupation, Nationality, Gender
  Financial Data: Estimated Income, Superannuation Savings, Credit Card Balances, Bank Loans
  Account Types: Checking, Savings, Business Lending, Foreign Currency Accounts
  Customer Attributes: Loyalty Classification, Properties Owned, Risk Weighting, Date Joined

 Note: A small synthetic sample (`sampledata.csv`) is included for demonstration purposes only.

## Key Analysis Steps

Data Preparation:
  Converted date columns to proper datetime format
  Created income bands (`Low`, `Mid`, `High`) using defined thresholds
  Checked for missing values and outliers

Exploratory Data Analysis (EDA):
  Visualized distributions of key numerical features (income, savings, loans, etc.)
  Explored categorical features such as occupation, loyalty classification, and risk weighting
  Generated descriptive statistics for all variables

Correlation Analysis:
Produced a heatmap of relationships among financial metrics
Identified patterns such as:
    - Strong correlation between Bank Deposits and Saving Accounts: suggesting overlapping or complementary saving behavior
    - Moderate correlations between Age/Income and various balances: reflecting typical financial lifecycle trends
    - Weak correlations involving Property Ownership: likely due to untracked external factors like location or inheritance
    - Business Lending showed moderate correlation with Bank Loans, but little connection to other metrics, suggesting it serves a distinct customer segment

Relationship Exploration:
  Used regression plots to examine interactions such as:
  Checking vs. Savings Accounts
  Business Lending vs. Bank Loans
  Estimated Income vs. Account Balances

---

Technologies

  Python, 
  Pandas, NumPy for Data manipulation
  Seaborn, Matplotlib for Visualization
  Jupyter Notebook for Development environment
