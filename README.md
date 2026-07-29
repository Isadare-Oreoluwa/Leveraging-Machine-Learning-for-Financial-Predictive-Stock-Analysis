# 📈 Leveraging Machine Learning for Financial & Predictive Stock Analysis

## 📌 Overview

This project applies statistical analysis and machine learning to evaluate corporate financial performance and predict stock price movements. Using exploratory data analysis, feature engineering, and predictive modeling, it identifies key financial drivers of stock returns and generates insights to support data-driven investment decisions.

The project demonstrates an end-to-end machine learning workflow, from data preparation and model development to evaluation and interpretation, making it a practical resource for anyone interested in financial analytics and predictive modelling.

---

## 📂 Dataset

The analysis uses a financial dataset obtained from **Kaggle**, containing financial statements and market information for multiple listed companies.

**Dataset:** https://www.kaggle.com/datasets/pacificrm/financial-sheets

### Dataset Includes

- Annual and quarterly financial statements
- Stock prices and market capitalization
- Financial ratios covering profitability, leverage, efficiency, and growth
- Financial data at **T₀** with stock performance measured at **T₁**

### Dataset Summary

- **Observations:** ~3,000 company-quarter records
- **Features:** 9 financial indicators
- **Target Variable:** `price_change_%`
- **Additional Fields:** Company name and reporting period

### Key Features

- Return on Capital Employed (ROCE)
- Operating Profit Margin (OPM)
- Asset Turnover (ATO)
- Return on Assets (ROA)
- Debt-to-Equity Ratio
- EPS Growth (3 Years)
- PEG Ratio
- Market Capitalization
- Composite Efficiency Score

---

## 🤖 Machine Learning Models

The following regression models were developed and compared:

- Linear Regression
- Ridge Regression
- Lasso Regression
- Elastic Net Regression
- Random Forest Regressor
- Gradient Boosting Regressor
- XGBoost
- Multi-Layer Perceptron (MLP)

### Model Evaluation

Performance was evaluated using:

- R² (Coefficient of Determination)
- Root Mean Squared Error (RMSE)
- Mean Absolute Error (MAE)

Hyperparameter optimisation was performed using **GridSearchCV** with cross-validation.

---

## 📊 Key Results

### Best Performing Model

**Random Forest Regressor**

- **R²:** ~0.23
- **RMSE:** ~6.05

### Most Important Predictors

- Market Capitalization
- Return on Capital Employed (ROCE)
- Return on Assets (ROA)
- Debt-to-Equity Ratio

### Key Insights

- Linear regression models showed relatively weak predictive performance.
- Tree-based algorithms captured complex non-linear relationships more effectively.
- Profitability metrics contributed more to predictive performance than liquidity indicators.
- The final model ranked companies according to their predicted quarterly stock price appreciation.

---

## 📁 Repository Structure

```text
Leveraging Machine Learning for Financial & Predictive Stock Analysis/
│
├── Data/
│   ├── Dataset
│   └── Processed Data
│
├── Code/
│   ├── Data Preparation
│   ├── Exploratory Data Analysis
│   ├── Machine Learning Models
│   └── Model Evaluation
│
├── Report/
│   └── Comprehensive Financial Analysis Report.pdf
│
└── README.md
```

---

## 🚀 Getting Started

### Clone the Repository

```bash
git clone https://github.com/Isadare-Oreoluwa/Leveraging-Machine-Learning-for-Financial-Predictive-Stock-Analysis.git
```

### Install Required Libraries

```bash
pip install pandas numpy scikit-learn matplotlib seaborn xgboost
```

### Run the Project

1. Download the dataset.
2. Update the dataset path in the Python scripts.
3. Execute the notebooks or Python scripts to:
   - Clean and prepare the data
   - Perform exploratory data analysis
   - Train and evaluate machine learning models
   - Generate stock price predictions

---

## 📄 Report

The project report covers:

- Exploratory Data Analysis
- Feature Engineering
- Statistical Analysis
- Machine Learning Model Development
- Model Evaluation
- Feature Importance
- Investment Insights and Recommendations

📄 **View Report**

https://github.com/Isadare-Oreoluwa/Leveraging-Machine-Learning-for-Financial-Predictive-Stock-Analysis/blob/main/Comprehensive%20Financial%20Analysis%20Report.pdf

---

## 💻 Code & Data

The complete source code, datasets, and supporting files are available in this repository.

📂 **Browse Repository**

https://github.com/Isadare-Oreoluwa/Leveraging-Machine-Learning-for-Financial-Predictive-Stock-Analysis

---

## ⚠️ Disclaimer

This project is intended for educational and research purposes. The predictive models provide analytical insights and should not be interpreted as financial or investment advice.

---

## 📫 Contact

If you have any questions, feedback, or collaboration opportunities, feel free to get in touch.

- **Email:** isadare.ore@gmail.com
- **LinkedIn:** https://www.linkedin.com/in/oreoluwa-isadare
