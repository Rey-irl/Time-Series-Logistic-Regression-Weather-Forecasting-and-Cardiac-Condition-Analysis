
# 📊 Time Series & Logistic Regression Project

This project combines two data-driven approaches to explore and predict real-world patterns using **Time Series Forecasting** and **Logistic Regression Classification**. It is divided into two main sections:

- Forecasting **Grass Minimum Temperature** using historical weather data
- Evaluating the impact of physiological variables on **Cardiac Conditions**

---

## 🔹 Part 1: Time Series Forecasting — Grass Minimum Temperature 🌡️

### 🧠 Objective:
Predict the daily *Grass Minimum Temperature (°C)* using historical weather data from **January 1942 to October 2023**.

### 🧰 Methods Applied:
- 📉 Simple Moving Average (SMA)
- 🔄 Naïve Forecast (Random Walk)
- 📈 Exponential Smoothing
- 🔁 ARIMA / SARIMA Modeling

### 🔍 Key Steps:
- Seasonal decomposition and trend analysis
- Train/test split (Train: 2019–2022, Test: Jan–Oct 2023)
- ACF & PACF analysis for model tuning
- Residual diagnostics and model validation

### ✅ Best Performing Model:
**ARIMA(4,1,1)**  
- RMSE: 3.7  
- Mean prediction error: 2.981  
- Recommended for short-term seasonal forecasting

---

## 🔹 Part 2: Logistic Regression — Cardiac Condition Analysis ❤️

### 🧠 Objective:
Analyze whether **age**, **weight**, **gender**, and **fitness score** affect the presence or absence of **cardiac conditions** using a dataset of 100 participants.

### 🧰 Process:
- Exploratory data analysis and visualization
- Outlier detection via Interquartile Range (IQR)
- Transformation of categorical variables to binary (dummy encoding)
- Model tuning using significance (p-values)
- Performance evaluation using:
  - Confusion matrix
  - Accuracy: **72.22%**
  - Sensitivity (Recall): **54.55%**
  - ROC Curve: **67.27% AUC**

### 🎯 Final Insight:
- **Age** and **Weight** were significant predictors.
- **Fitness score** and **gender** showed weaker predictive power.
- Logistic regression proved suitable for binary health classification.

---

## 🧭 Methodology

This project follows the **Knowledge Discovery in Databases (KDD)** process:

1. **Data Selection**
2. **Data Preprocessing**
3. **Data Transformation**
4. **Data Mining**
5. **Pattern Evaluation**
6. **Knowledge Representation**

---

## 📚 References

- Hosmer, D. W., Lemeshow, S., & Sturdivant, R. X. (2013). *Applied Logistic Regression*. Wiley.
- Delen, D. (2020). *Predictive Analytics*. Pearson FT Press.
- Gharehbaghi, A. (2023). *Deep Learning in Time Series Analysis*. CRC Press.
- Joseph, M. (2022). *Modern Time Series Forecasting with Python*. Packt Publishing.

---

## 💻 Tools Used
- R programming language
- `forecast`, `tseries`, `ggplot2`, and related R packages

---

## 🧠 Author
**Reyna Vargas Antonio**  
National College of Ireland  
Email: x23127635@student.ncirl.ie

---

