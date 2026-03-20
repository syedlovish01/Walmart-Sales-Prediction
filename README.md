# 📊 Walmart Weekly Sales Prediction

## 📌 Overview

This project focuses on predicting weekly sales for Walmart stores using machine learning techniques.
It explores how historical sales, calendar patterns, and external factors influence demand.

The project demonstrates a complete **data science workflow**, including:

* Data preprocessing
* Exploratory data analysis (EDA)
* Feature engineering
* Model training & comparison
* Performance evaluation

---

## 🎯 Problem Statement

The goal is to predict **weekly sales** using historical data.

This project is designed as a **short-term forecasting problem**, where recent past data (e.g., previous weeks' sales) is available at prediction time.

---

## 📂 Dataset

The dataset contains weekly sales data for 45 Walmart stores with the following features:

* `Store` – Store ID
* `Date` – Week of sales
* `Weekly_Sales` – Target variable
* `Holiday_Flag` – Whether the week includes a holiday
* `Temperature` – Average temperature
* `Fuel_Price` – Fuel cost
* `CPI` – Consumer Price Index
* `Unemployment` – Unemployment rate

---

## 🔍 Exploratory Data Analysis (EDA)

Key insights:

* Sales vary significantly across stores
* Strong seasonal patterns exist (holidays, yearly cycles)
* External factors like temperature show weak linear correlation
* Holiday weeks often show spikes in sales

---

## ⚙️ Feature Engineering

The following features were created:

### 📅 Time-based Features

* Year
* Month
* Week

### 🔁 Lag Features

* `Lag_1` – Sales from previous week
* `Lag_2` – Sales from two weeks ago

These features help capture:

* Seasonality
* Temporal trends
* Short-term dependencies

---

## 🧠 Models Used

The following models were trained and evaluated:

* Linear Regression
* Ridge Regression
* Decision Tree
* Random Forest
* K-Nearest Neighbors (KNN)

---

## 📊 Model Performance

| Model             | R² Score | MAE  |
| ----------------- | -------- | ---- |
| Random Forest     | ~0.97    | ~57k |
| Linear Regression | ~0.96    | ~74k |

👉 **Random Forest performed best**, capturing nonlinear relationships in the data.

---

## 🧠 Key Insights

* Lag features are highly influential for prediction
* Calendar features capture strong seasonal patterns
* Store-level differences significantly affect sales
* Multiple models performed well due to structured data patterns

---

## ⚠️ Limitations

* The dataset is highly structured and exhibits stable patterns, making the problem easier than real-world scenarios
* The model relies heavily on lag features (recent sales)
* Assumes availability of recent historical data at prediction time
* May not generalize well to sudden changes (e.g., promotions, economic shocks)

---

## 🚀 Future Improvements

* Multi-step forecasting (predict multiple weeks ahead)
* Incorporating external data (promotions, events)
* Hyperparameter tuning
* Model deployment (API or dashboard)

---

## 🛠️ Tech Stack

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib / Seaborn

---

## 📈 Conclusion

This project demonstrates how combining:

* **time-based features**
* **lag features**
* and **machine learning models**

can effectively predict sales in structured datasets.

It also highlights the importance of **model validation and understanding data patterns**, not just achieving high performance.

---

## 👨‍💻 Author

Lovish Haider
BSc International Business Information Systems
Aspiring Data Scientist
