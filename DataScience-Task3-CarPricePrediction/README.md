# 🚗 Car Price Prediction with Machine Learning

A regression-based machine learning project that predicts the selling price of used cars using the CarDekho dataset. The project covers data preprocessing, feature engineering, exploratory data analysis (EDA), model training, evaluation, and feature importance analysis.

---

## 📌 Objective

Develop and compare multiple regression models to predict the selling price of a used car based on its specifications and identify the best-performing model.

---

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 📂 Project Structure

```
Car-Price-Prediction/
│
├── graphs/
│   ├── selling_price_distribution.png
│   ├── fuel_type_boxplot.png
│   ├── car_age_scatter.png
│   ├── correlation_heatmap.png
│   └── feature_importance.png
│
├── car data.csv
├── Car_Price_Prediction.ipynb
└── README.md
```

---

## 📊 Dataset

- **Dataset:** CarDekho Used Car Dataset
- **Source:** Kaggle
- **Records:** 301
- **Target Variable:** `Selling_Price`

### Features

- Car Name
- Year
- Present Price
- Kms Driven
- Fuel Type
- Seller Type
- Transmission
- Owner

---

## 🧹 Data Preprocessing

The following preprocessing steps were performed:

- Checked for missing values
- Removed duplicate records
- Created **Car_Age** feature from the **Year** column
- Extracted **Brand** from the **Car_Name**
- One-Hot Encoded categorical variables

---

## 📈 Exploratory Data Analysis (EDA)

The notebook includes:

- Selling Price Distribution
- Selling Price vs Fuel Type
- Selling Price vs Car Age
- Correlation Heatmap

---

## 🤖 Machine Learning Models

The following regression models were trained:

- Linear Regression
- Random Forest Regressor

---

## 📏 Evaluation Metrics

Each model was evaluated using:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

| Model | MAE | RMSE | R² Score |
|------|------:|------:|------:|
| Linear Regression | 1.3606 | 2.5892 | 0.7399 |
| Random Forest Regressor | 1.4168 | 3.4825 | 0.5294 |

---

## 🏆 Best Performing Model

**Linear Regression**

### Justification

- Lowest Mean Absolute Error (MAE)
- Lowest Root Mean Squared Error (RMSE)
- Highest R² Score
- Best overall performance on the test dataset

---

## 📊 Feature Importance

The notebook includes a feature importance chart generated using the Random Forest model to identify the most influential features affecting car prices.

---

## ▶️ How to Run

### 1. Clone the repository

```bash
git clone https://github.com/your-username/Car-Price-Prediction.git
```

### 2. Navigate to the project

```bash
cd Car-Price-Prediction
```

### 3. Install dependencies

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

### 5. Open

```
Car_Price_Prediction.ipynb
```

Run all cells.

---

## 📚 Libraries Used

```python
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns

from sklearn.model_selection import train_test_split
from sklearn.preprocessing import OneHotEncoder
from sklearn.compose import ColumnTransformer
from sklearn.pipeline import Pipeline

from sklearn.linear_model import LinearRegression
from sklearn.ensemble import RandomForestRegressor

from sklearn.metrics import (
    mean_absolute_error,
    mean_squared_error,
    r2_score
)
```

---

## 🎯 Learning Outcomes

- Data Cleaning
- Feature Engineering
- Exploratory Data Analysis (EDA)
- Categorical Data Encoding
- Regression Modeling
- Model Evaluation
- Feature Importance Analysis

---

## 👨‍💻 Author

**Aadarsh Rao**

B.Tech CSE (Data Science)

GitHub: https://github.com/your-username