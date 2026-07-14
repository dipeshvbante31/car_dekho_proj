# 🚗 CarDekho Used Car Price Prediction

## 📌 Project Overview

This project predicts the selling price of used cars using Machine Learning regression algorithms. The dataset is preprocessed by handling categorical features through encoding, scaling numerical features, and training multiple regression models to identify the best-performing algorithm.

The project demonstrates a complete Machine Learning workflow, including data preprocessing, feature engineering, model training, evaluation, and comparison.

---

## 📂 Dataset

- Dataset: CarDekho Used Car Dataset
- File Used: `cardekho_imputated.csv`

### Target Variable

- `selling_price`

---

## 📊 Features Used

Some important features include:

- Model
- Vehicle Age
- Kilometers Driven
- Seller Type
- Fuel Type
- Transmission Type
- Mileage
- Engine
- Max Power
- Seats

Columns removed before training:

- `car_name`
- `brand`

---

## 🛠 Libraries Used

- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Statsmodels

---

## ⚙ Data Preprocessing

The following preprocessing steps were performed:

- Removed unnecessary columns
- Label Encoding for `model`
- One-Hot Encoding for categorical columns
- Standard Scaling of numerical features
- Train-Test Split (80:20)

---

## 🤖 Machine Learning Models

The following regression models were trained:

- Linear Regression
- Lasso Regression
- Ridge Regression
- K-Nearest Neighbors Regressor
- Decision Tree Regressor
- Random Forest Regressor

---

## 📈 Evaluation Metrics

Each model is evaluated using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

---

## 🔍 Model Comparison

All models are trained and evaluated on both training and testing datasets.

The performance comparison helps determine the best model for predicting used car prices.

---

## 📁 Project Structure

```
CarDekho-Price-Prediction/
│
├── cardekho.ipynb
├── cardekho_imputated.csv
├── README.md
└── requirements.txt
```

---

## ▶ How to Run

1. Clone the repository

```bash
git clone https://github.com/yourusername/car-price-prediction.git
```

2. Install dependencies

```bash
pip install -r requirements.txt
```

3. Open the notebook

```bash
jupyter notebook
```

4. Run all cells.

---

## 📚 Skills Demonstrated

- Data Cleaning
- Feature Engineering
- Label Encoding
- One-Hot Encoding
- Feature Scaling
- Regression Algorithms
- Model Evaluation
- Performance Comparison
- Machine Learning Pipeline

---

## 🚀 Future Improvements

- Hyperparameter Tuning using GridSearchCV
- Cross Validation
- Feature Selection
- Model Saving using Pickle
- Flask/Streamlit Deployment
- XGBoost and CatBoost Implementation

---

## 👨‍💻 Author

Dipesh Bante
