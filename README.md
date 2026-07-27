# 🌾 Leveraging Machine Learning for Predicting Agricultural Trade Flows

## 📌 Overview

This project applies machine learning techniques to predict agricultural trade flows between Nigeria and its trading partners. Using economic, demographic, and geographic indicators, it identifies the key drivers of trade and evaluates the performance of multiple predictive models to support data-driven trade analysis.

The project demonstrates an end-to-end machine learning workflow, from data preparation and exploratory analysis to model development, evaluation, and interpretation.

---

## 📂 Dataset

The analysis uses a comprehensive agricultural trade dataset containing economic, demographic, and geographic variables influencing bilateral trade between Nigeria and its trading partners.

### Dataset Includes

- Import and export values (USD)
- GDP of Nigeria and partner countries
- Exchange rates
- Population statistics
- Distance between trading partners
- Shared language indicators
- Landlocked status and other geographic variables

### Dataset Summary

- **Study Period:** 1996–2021
- **Country:** Nigeria and its agricultural trading partners
- **Target Variables:** Import and Export Trade Values
- **Features:** Economic, demographic, and geographic indicators

---

## 🤖 Machine Learning Models

The project compares the performance of several machine learning algorithms:

- Linear Regression
- Ridge Regression
- Lasso Regression
- Random Forest Regressor
- Gradient Boosting Regressor
- Multi-Layer Perceptron (MLP)

### Model Evaluation Metrics

- R² (Coefficient of Determination)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)

---

## 📊 Results & Insights

### Best Performing Model

**Random Forest Regressor**

- **R²:** 0.75
- **MSE:** 3.61 × 10¹⁵

### Key Drivers of Agricultural Trade

- GDP of trading partners
- Population size
- Exchange rates
- Geographic distance

### Key Findings

- Random Forest produced the strongest predictive performance among the models evaluated.
- Economic indicators, particularly GDP, were the strongest determinants of agricultural trade.
- Geographic distance remained a significant predictor of bilateral trade flows.
- Machine learning models effectively captured complex relationships between economic and geographic variables.

---

## 📁 Repository Structure

```text
Leveraging-Machine-Learning-for-Predicting-Agricultural-Trade-Flows/
│
├── Data and Code/
│   ├── Agricultural Trade Dataset.xlsx
│   ├── Agricultural Trade Flow Prediction.ipynb
│   └── Agricultural Trade Visualisation.ipynb
│
├── Agricultural Trade Flows Prediction Report.pdf
│
└── README.md
```



---

## 🚀 Getting Started

### Viewing the Project

Browse the repository to access the report, dataset, and Jupyter notebooks. Files can be viewed directly on GitHub or downloaded for offline use.

### Download the Repository

To download all project files:

1. Click the **Code** button.
2. Select **Download ZIP**.
3. Extract the ZIP file to your preferred location.

### Clone the Repository

```bash
git clone https://github.com/Isadare-Oreoluwa/Leveraging-Machine-Learning-for-Predicting-Agricultural-Trade-Flows.git
```

### Install Required Libraries

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

### Run the Notebooks

1. Open the Jupyter notebooks in the **Data and Code** folder.
2. Update the dataset file path in each notebook to match the location of the Excel file on your local machine.

For example, replace:

```python
df = pd.read_excel('/content/Agricultural Trade Dataset.xlsx')
```

with:

```python
df = pd.read_excel('Data and Code/Agricultural Trade Dataset.xlsx')
```

or use the appropriate file path for your system.

3. Run the notebook cells sequentially to reproduce the data preparation, exploratory analysis, visualisations, model training, and predictions.

---

## 📄 Report

The project report includes:

- Exploratory Data Analysis
- Feature Engineering
- Statistical Analysis
- Machine Learning Model Development
- Model Evaluation
- Feature Importance Analysis
- Trade Policy Insights and Recommendations

📄 **View the Report**

https://github.com/Isadare-Oreoluwa/Leveraging-Machine-Learning-for-Predicting-Agricultural-Trade-Flows/blob/main/Agricultural%20Trade%20Flows%20Prediction%20Report.pdf

---

## 💻 Code & Data

The repository contains all resources required to reproduce the analysis.

- **Agricultural Trade Dataset.xlsx** – Dataset used for model development and evaluation.
- **Jupyter Notebooks** – Data preparation, exploratory analysis, visualisation, machine learning modelling, and prediction workflow.

> **Note:** The notebooks were originally developed in a cloud environment. If running them locally, update the dataset file paths before executing the code.

📂 **Browse the Repository**

https://github.com/Isadare-Oreoluwa/Leveraging-Machine-Learning-for-Predicting-Agricultural-Trade-Flows

---

## ⚠️ Disclaimer

This project was developed for educational and portfolio purposes. The predictive models are intended to support trade analysis and should not be interpreted as definitive forecasts or policy recommendations.

---

## 📫 Contact

If you have any questions, feedback, or collaboration opportunities, feel free to get in touch.

- **Email:** isadare.ore@gmail.com
- **LinkedIn:** https://www.linkedin.com/in/oreoluwa-isadare
