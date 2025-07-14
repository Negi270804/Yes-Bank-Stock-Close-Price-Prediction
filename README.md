Here is a professional and structured `README.md` file for your GitHub repository based on your project **"YES BANK STOCK CLOSING PRICE PREDICTION"**:

---

```markdown
# 📈 YES BANK STOCK CLOSING PRICE PREDICTION

### 👤 Contributor: Nikhil Negi  
### 📁 Project Type: Regression (Machine Learning)  
### 🔗 [Project Notebook (Google Colab)](https://colab.research.google.com/drive/13zWLsfqAZ3vYDJKVThAYvp0dugCzkozF?usp=sharing)  
### 🌐 [GitHub Repository](https://github.com/Negi270804/Yes-Bank-Stock-Close-Price-Prediction.git)

---

## 🧠 Project Objective

This project aims to predict the future closing prices of YES Bank stock listed on the National Stock Exchange using regression-based machine learning models such as:

- Linear Regression
- Lasso Regression
- Ridge Regression

Understanding and forecasting stock trends could yield significant financial advantages for investors and analysts.

---

## 🧩 Dataset Description

- **Source**: YES Bank monthly stock prices (CSV)
- **Rows**: 185
- **Columns**:  
  - `Date` (Monthly format, e.g., Jul-05)  
  - `Open`, `High`, `Low`, `Close` prices

---

## 🔍 Problem Statement

YES Bank has been under scrutiny since 2018 due to financial scandals. This project explores the bank's stock price behavior and evaluates the feasibility of using machine learning to predict its monthly **closing prices**.

---

## 📊 Exploratory Data Analysis (EDA)

A total of **15+ charts** were generated using the **UBM (Univariate, Bivariate, Multivariate)** approach to explore relationships and patterns, such as:

- Trends in closing prices over time
- Distribution of Open, High, Low, and Close prices
- Correlation heatmaps and pairplots
- Log transformations to normalize skewed features

---

## ✅ Data Preprocessing

- Converted `Date` to datetime format
- Checked for and found **no missing or duplicate values**
- Log-transformed target variable (`Close`) and normalized features
- Outlier analysis using boxplots
- Feature selection using **VIF** to reduce multicollinearity

---

## 🧪 Hypothesis Testing

Three statistical tests were conducted:
1. Paired t-test on `Open` vs `Close`
2. Welch's t-test on `Close` prices before and after 2018
3. Pearson correlation between `Open` and `Close`

---

## 📦 Machine Learning Models

### 1. Linear Regression
- **R² Score**: 0.9978
- **MAE**: 3.05
- **RMSE**: 4.47  
Baseline model with strong predictive accuracy.

### 2. Lasso Regression
- **Tuned using GridSearchCV**
- **R² Score**: 0.9978
- Performs regularization and automatic feature selection.

### 3. Ridge Regression
- **R² Score**: 0.9921
- Useful for handling multicollinearity without dropping features.

---

## ⚙️ Hyperparameter Tuning

- Used `GridSearchCV` on Lasso Regression to optimize the `alpha` parameter.
- Best `alpha`: `0.0001`

---

## 📈 Evaluation Metrics & Business Impact

| Metric  | Description                             | Business Impact                            |
|---------|-----------------------------------------|--------------------------------------------|
| R²      | Model's explained variance              | Measures model accuracy                    |
| MSE     | Mean squared error                      | Penalizes large errors                     |
| RMSE    | Root of MSE (original units)            | Easy interpretability                      |
| MAE     | Mean of absolute errors                 | Average prediction deviation               |
| MAPE    | % error                                 | Useful for scale-independent evaluation    |

✅ These metrics indicate **high model reliability** which supports **risk mitigation**, **investment planning**, and **strategic financial decisions**.

---

## 📌 Conclusion

- The model effectively captures patterns in YES Bank's stock data.
- Linear and Lasso regressions perform exceptionally well.
- This approach can be extended to other time-series financial assets for similar forecasting.

---

## 📎 License

This project is for educational purposes. No financial advice is provided.

---

## 🙌 Acknowledgements

- Dataset sourced from internal coursework
- Libraries used: `pandas`, `matplotlib`, `seaborn`, `scikit-learn`, `statsmodels`

---

```
