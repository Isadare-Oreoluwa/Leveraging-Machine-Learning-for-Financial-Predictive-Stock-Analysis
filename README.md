# 📈 Leveraging Machine Learning for Financial & Predictive Stock Analysis

## 📌 Overview

This project applies statistical analysis and machine learning to evaluate corporate financial performance and predict stock price movements. Using exploratory data analysis, feature engineering, and predictive modelling, it identifies key financial drivers of stock returns and generates insights to support data-driven investment decisions.

The project demonstrates an end-to-end machine learning workflow, from data preparation and model development to model evaluation and interpretation.

---

## 📂 Dataset

The analysis uses a financial dataset obtained from **Kaggle**, containing financial statements and market information for multiple listed companies.

**Dataset Source:**  
https://www.kaggle.com/datasets/pacificrm/financial-sheets

### Dataset Includes

- Annual and quarterly financial statements
- Stock prices and market capitalisation
- Financial ratios covering profitability, leverage, efficiency, and growth
- Financial data at **T₀** with stock performance measured at **T₁**

### Dataset Summary

- **Observations:** ~3,000 company-quarter records
- **Features:** 9 financial indicators
- **Target Variable:** `price_change_%`
- **Additional Variables:** Company name and reporting period

### Key Features

- Return on Capital Employed (ROCE)
- Operating Profit Margin (OPM)
- Asset Turnover (ATO)
- Return on Assets (ROA)
- Debt-to-Equity Ratio
- EPS Growth (3 Years)
- PEG Ratio
- Market Capitalisation
- Composite Efficiency Score

---

## 🤖 Machine Learning Models

The project compares the performance of several regression algorithms:

- Linear Regression
- Ridge Regression
- Lasso Regression
- Elastic Net Regression
- Random Forest Regressor
- Gradient Boosting Regressor
- XGBoost
- Multi-Layer Perceptron (MLP)

### Model Evaluation Metrics

- R² (Coefficient of Determination)
- Root Mean Squared Error (RMSE)
- Mean Absolute Error (MAE)

Hyperparameter optimisation was performed using **GridSearchCV** with cross-validation.

---

## 📊 Results & Insights

### Best Performing Model

**Random Forest Regressor**

- **R²:** ~0.23
- **RMSE:** ~6.05

### Key Drivers of Stock Price Changes

- Market Capitalisation
- Return on Capital Employed (ROCE)
- Return on Assets (ROA)
- Debt-to-Equity Ratio

### Key Findings

- Linear models showed limited predictive performance, suggesting weak linear relationships between financial metrics and stock price movements.
- Tree-based models captured non-linear relationships more effectively and produced stronger predictions.
- Profitability indicators were among the strongest predictors of future stock performance.
- The final model generated a ranked list of companies with the highest predicted quarterly stock price appreciation.

---

## 📁 Repository Structure

```text
Leveraging-Machine-Learning-for-Financial-Predictive-Stock-Analysis/
│
├── Data and Code/
│   ├── Dataset/
│   │   ├── Financial Dataset.xlsx
│   │   └── ...
│   │
│   └── Financial analysis.ipynb
│
├── Comprehensive Financial Analysis Report.pdf
│
└── README.md
```

---

## 🚀 Getting Started

### View the Project

Browse the repository to access the report, dataset, and Jupyter Notebook.

### Download the Repository

To download all project files:

1. Click the **Code** button.
2. Select **Download ZIP**.
3. Extract the ZIP file to your preferred location.

### Clone the Repository

```bash
git clone https://github.com/Isadare-Oreoluwa/Leveraging-Machine-Learning-for-Financial-Predictive-Stock-Analysis.git
```

### Install Required Libraries

```bash
pip install pandas numpy scikit-learn matplotlib seaborn xgboost
```

### Run the Notebook

1. Open **Financial analysis.ipynb** in Jupyter Notebook or JupyterLab.
2. Ensure the dataset folder remains inside the **Data and Code** directory.
3. Run the notebook cells sequentially to reproduce the analysis and machine learning models.

---

## 📄 Report

The accompanying report covers:

- Exploratory Data Analysis
- Feature Engineering
- Statistical Analysis
- Machine Learning Model Development
- Model Evaluation
- Feature Importance Analysis
- Investment Insights and Recommendations

📄 **View the Report**

https://github.com/Isadare-Oreoluwa/Leveraging-Machine-Learning-for-Financial-Predictive-Stock-Analysis/blob/main/Comprehensive%20Financial%20Analysis%20Report.pdf

---

## 💻 Code & Data

The repository includes all resources required to reproduce the analysis.

- **Dataset/** – Financial datasets used in the project.
- **Financial analysis.ipynb** – Data preparation, exploratory analysis, machine learning modelling, evaluation, and prediction workflow.

📂 **Browse the Repository**

https://github.com/Isadare-Oreoluwa/Leveraging-Machine-Learning-for-Financial-Predictive-Stock-Analysis

---

## ⚠️ Disclaimer

This project was developed for educational and portfolio purposes. The predictive models are intended to support financial analysis and should not be interpreted as investment or financial advice.

---

## 📫 Contact

If you have any questions, feedback, or collaboration opportunities, feel free to get in touch.

- **Email:** isadare.ore@gmail.com
- **LinkedIn:** https://www.linkedin.com/in/oreoluwa-isadare
