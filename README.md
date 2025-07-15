# 📊 YES BANK Stock Closing Price Prediction

This project presents a comprehensive machine learning solution to predict the **monthly closing stock price** of YES BANK based on historical Open, High, and Low prices. The model includes data cleaning, exploratory data analysis (EDA), hypothesis testing, regression modeling, and performance evaluation.

---

## 📁 Repository Overview

- **Project Type:** Machine Learning - Regression  
- **Contributor:** Nikhil Negi  
- **GitHub Repo:** [Yes-Bank-Stock-Close-Price-Prediction](https://github.com/Negi270804/Yes-Bank-Stock-Close-Price-Prediction)  
- **Dataset:** YES BANK monthly stock prices (Jul-2005 to Nov-2020)

---

## 🎯 Business Objective

To predict the monthly **closing stock price** using ML models, supporting:
- Informed trading decisions  
- Market risk analysis  
- Long-term investment strategy  

---

## 🔍 Problem Statement

YES BANK has faced volatility post-2018 due to financial controversies. This project analyzes how that impacted stock behavior and builds predictive models for its monthly closing price.

---

## 🔬 Key Steps

### 🧹 Data Cleaning
- No missing or duplicate values
- Converted 'Date' to datetime
- Applied transformations (log, z-score)

### 📊 EDA & Visualization
- 15+ charts (line plot, scatter, heatmap, pairplot)
- UBM pattern: Univariate, Bivariate, Multivariate
- Statistical testing: t-tests, Pearson correlation

### 📈 Feature Engineering
- Dropped multicollinear features using VIF
- Final model used ['High', 'Low'] to predict 'Close'

---

## 🧠 Hypothesis Testing

1. **Open vs Close Mean** → No significant difference  
2. **Close Before vs After 2018** → Significant drop  
3. **Open vs Close Correlation** → Strong correlation (0.97+)

---

## 🤖 Models Used

| Model             | R² Score | RMSE   | MAE   | MAPE   |
|------------------|----------|--------|-------|--------|
| Linear Regression| 0.9978   | 4.47   | 3.05  | 5.4%   |
| Lasso Regression | 0.9978   | 4.51   | 3.09  | 5.4%   |
| Ridge Regression | 0.9921   | Higher | -     | -      |

- ✅ Best Model: **Lasso Regression (with GridSearchCV)**  
- 🧪 Feature scaling: **MinMaxScaler**  
- 🎯 Target transformation: **Logarithmic**

---

## ⚙️ Tools & Tech Stack

- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn, Statsmodels  

---

## 📌 Insights

- YES BANK price shows high volatility post-2018.  
- Strong linear relationships across Open, High, Low, and Close.  
- Regularized models like Lasso slightly outperform plain Linear Regression.

---

## 📦 Project Structure

Yes-Bank-Stock-Close-Price-Prediction/


├── data/

│ └── data_YesBank_StockPrices.csv

├── notebook/

│ └── YES_BANK_STOCK_CLOSING_PRICE_PREDICTION.ipynb

├── README.md

---

## 🙏 Acknowledgements

Thanks to:
- **Winnovation** for mentorship  
- **Abhisek Mishra** for insights on LinkedIn  

---

## 📬 Contact

🔗 [LinkedIn - Nikhil Negi](https://www.linkedin.com/in/nikhil-negi-0bb166328)  
📁 [GitHub - Negi270804](https://github.com/Negi270804)

---
