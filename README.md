# 🏠 House Price Prediction

## 📌 Project Overview

This project aims to predict house sale prices using Machine Learning techniques.

The workflow includes:

- Data Understanding
- Data Cleaning
- Exploratory Data Analysis (EDA)
- Missing Value Handling
- Outlier Detection & Removal
- Feature Engineering
- Encoding Categorical Features
- Model Training & Evaluation
- Cross Validation

---

## 📊 Dataset

Dataset: House Prices - Advanced Regression Techniques

The dataset contains residential home information such as:

- Living Area
- Garage Size
- Basement Area
- Construction Year
- House Quality
- Neighborhood Information

Target Variable:

```text
SalePrice
```

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-Learn
- Joblib

---

## 🤖 Models Trained

### Linear Regression

R² Score:

```text
0.9005
```

### Random Forest Regressor

R² Score:

```text
0.8760
```

### Gradient Boosting Regressor

R² Score:

```text
0.9074
```

---

## 📈 Cross Validation

5-Fold Cross Validation:

```text
Average R² = 0.9029
```

This confirms that the model generalizes well and produces stable results across different data splits.

---

## 🏆 Best Model

Gradient Boosting Regressor

Performance:

```text
MAE  = 0.0883
RMSE = 0.1249
R²   = 0.9074
```

---

## 📂 Repository Structure

```text
house-price-prediction/
│
├── House_Price_Prediction.ipynb
├── house_price_model.pkl
├── requirements.txt
└── README.md
```

---

## 🚀 Future Improvements

- Hyperparameter Tuning
- XGBoost Implementation
- Streamlit Deployment
- Feature Selection Optimization

---

## 👩‍💻 Author

Aya Kamal

AI Student | Machine Learning Enthusiast
