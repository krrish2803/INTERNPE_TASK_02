# 🚗 Car Price Prediction using Machine Learning

This project aims to predict the selling price of a used car based on key features like brand, manufacturing year, kilometers driven, and fuel type using a **Linear Regression** model built with **Python** and **scikit-learn**.

---

## 📌 Problem Statement

Used car buyers and sellers often struggle to estimate a fair price. This model helps predict the **resale value** of a car based on historical data, improving decision-making for dealers and consumers.

---

## 📂 Dataset

- **Filename**: `quikr_car.csv`
- **Features:**
  - `name`: Car model name
  - `year`: Year of manufacture
  - `selling_price`: Price listed by seller
  - `km_driven`: Total kilometers driven
  - `fuel_type`: Petrol/Diesel/CNG
  - `owner`: Ownership type
  - `location`: Selling city

---

## 🔧 Tech Stack & Tools

- 🐍 Python
- 📊 Pandas, NumPy
- 📈 Matplotlib, Seaborn
- 🤖 scikit-learn (Linear Regression, Pipeline)
- 💾 Pickle (Model Saving)

---

## 🧠 Model Details

- **Algorithm Used**: Linear Regression
- **Preprocessing**:
  - Cleaned and transformed `name`, `fuel_type`, `km_driven`
  - Extracted car brand from name
  - Used `ColumnTransformer` and `OneHotEncoder` for categorical variables
- **Model Evaluation**:
  - **Metric**: R² Score
  - **Best Score Achieved**: ~0.84 (84% variance explained)
  - Trained and evaluated across 1000 random train-test splits

---

## 🚀 How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/krrish2803/car-price-prediction.git
   cd car-price-prediction
   ```
