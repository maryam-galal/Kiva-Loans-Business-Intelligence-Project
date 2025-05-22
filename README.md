# 🌍 Kiva Loans Business Intelligence Project (2025)

This project analyzes a real-world dataset from [Kiva.org](https://drive.google.com/file/d/1IOWPH9qyEhqfPrNlBEVe2Swcko-ULzwO/view?usp=sharing), a nonprofit organization that connects lenders with borrowers in underserved communities. The goal is to extract insights and make data-driven recommendations using business intelligence tools, data analysis, and machine learning.

## 📁 Project Structure

- `Kiva_Loans_Analysis.ipynb` — Main analysis notebook with data cleaning, EDA, modeling, and time series.
- `PowerBI_Report.pbix` — Interactive Power BI dashboard visualizing key findings.
- `Kiva_Loans_Presentation.pptx` — 30-slide presentation summarizing the project.
- `data/` — Contains the raw and cleaned datasets.
- `README.md` — Project overview.

## 🎯 Project Objective

Use data analysis, visualization, and machine learning to help the Kiva organization answer key business questions:

- 📊 Which sectors receive the highest amount of funding, and how does this change over time?
- 🤝 Is there a correlation between the number of lenders and the funded loan amount?
- 🔮 Can we predict future funded amounts based on historical data?
- 📈 What are the trends in loan funding over time?

## 🧰 Tools & Technologies

- **Python** (`pandas`, `matplotlib`, `seaborn`, `scikit-learn`)
- **Power BI** (for interactive visualizations)
- **Jupyter Notebook**
- **Machine Learning**: Linear Regression, Random Forest, Decision Tree
- **Time Series**: ARIMA, Trend analysis, resampling over time

## 🔍 Data Overview

The dataset includes:
- Loan ID, Amounts (`loan_amount`, `funded_amount`)
- Sector & Country
- Partner ID, Loan Term, Lender Count
- Borrower Genders, Repayment Interval
- Loan Initiation Date

## 🔄 Data Preprocessing

- Missing value handling (especially in `borrower_genders`, `term_in_months`)
- Type conversion (`date` to datetime)
- Outlier detection and removal
- Feature encoding (for modeling)

## 📊 Exploratory Data Analysis

- Sector-wise and country-wise funding distribution
- Gender-based loan analysis
- Time trends of funded loans
- Correlation heatmaps

## 🔎 Predictive Modeling

Built a machine learning model to **predict funded amount** using features like:
- Loan amount
- Term in months
- Sector (encoded)
- Lender count
- Repayment interval

## 📆 Time Series Analysis

Analyzed monthly trends of total funded amount using:
- Time aggregation (monthly/yearly)
- Line plots and moving averages

## 📌 Key Insights

- 📈 Most funding goes to sectors like **Agriculture**, **Food** and **Retail**
- 🌍 Countries like **Philippines**, **Kenya** and **El salvador** are top recipients
- 📊 Funded amount is positively correlated with lender count
- 🧠 Machine learning models can reasonably estimate funded amounts based on loan features

