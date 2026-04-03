# PRODIGY_ML_01
# 🏠 House Price Prediction using Machine Learning

## 📌 Project Overview

This project builds a **Machine Learning model** to predict house prices based on key features such as living area, number of bedrooms, and bathrooms.

The goal is to demonstrate a complete **end-to-end ML pipeline**, including data preprocessing, model training, evaluation, and prediction.

---

## 🎯 Problem Statement

Accurately predicting house prices is important for:

* Real estate businesses
* Buyers and sellers
* Investment decision-making

This project uses **Linear Regression** to estimate house prices from structured data.

---

## 📊 Dataset

* Source: Kaggle House Prices Dataset
* Total Features: ~155 columns
* Used Features:

  * `GrLivArea` → Living Area
  * `BedroomAbvGr` → Number of Bedrooms
  * `FullBath` → Number of Bathrooms
* Target Variable:

  * `SalePrice`

---

## ⚙️ Tech Stack

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib

---

## 🚀 ML Pipeline

1. **Data Loading**
2. **Feature Selection**
3. **Handling Missing Values**
4. **Train-Test Split**
5. **Feature Scaling (StandardScaler)**
6. **Model Training (Linear Regression)**
7. **Model Evaluation (MSE, R² Score)**
8. **Prediction on New Data**

---

## 📈 Model Performance

| Metric                   | Value        |
| ------------------------ | ------------ |
| Mean Squared Error (MSE) | ~2.8 Billion |
| R² Score                 | **0.63**     |

### 🧠 Interpretation

* The model explains **63% of variance** in house prices
* Performance is good for a baseline model with limited features
* Can be improved with advanced feature engineering and models

---

## 🔍 Key Insights

* Living area (`GrLivArea`) has strong impact on price
* Number of rooms and bathrooms influence pricing trends
* Simple models can still provide meaningful predictions

---

## 🏡 Example Prediction

**Input:**

* Area: 2000 sqft
* Bedrooms: 3
* Bathrooms: 2

**Predicted Price:**

```
~71,000 (approx)
```

---

## 📁 Project Structure

```
house-price-prediction/
│── data/
│    └── train.csv
│
│── notebook/
│    └── house_price.ipynb
│
│── src/
│    └── model.py
│
│── README.md
│── requirements.txt
```

---

## ▶️ How to Run

```bash
pip install -r requirements.txt
python src/model.py
```

---

## 💡 Future Improvements

* Use more features (e.g., `OverallQual`, `GarageCars`)
* Apply advanced models (Random Forest, XGBoost)
* Hyperparameter tuning
* Deploy using Streamlit or Flask

---

## 🧠 Learning Outcomes

* Built a complete ML pipeline
* Understood regression modeling
* Learned feature selection and preprocessing
* Gained hands-on experience with real-world dataset

---

## 👨‍💻 Author

**Shashank Sharma**

---

## ⭐ Final Note

This project demonstrates how a simple Linear Regression model can be used to solve real-world problems and serves as a strong foundation for advanced machine learning techniques.
