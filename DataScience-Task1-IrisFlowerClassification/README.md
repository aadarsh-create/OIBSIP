# 🌸 Iris Flower Classification

A Machine Learning project that classifies Iris flowers into three species—**Setosa**, **Versicolor**, and **Virginica**—using their physical measurements.

---

## 📌 Objective

Build and evaluate multiple machine learning classification models to predict the species of an Iris flower based on its features.

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
DataScience-Task1/
│
├── graphs/
│   ├── image.png
│   ├── image1.png
│   ├── image2.png
│   └── image3.png
│
├── iris_flower_classification.ipynb
└── README.md
```

---

## 📊 Dataset

- **Dataset:** Iris Dataset
- **Source:** `sklearn.datasets.load_iris()`
- **Samples:** 150
- **Features:** 4
  - Sepal Length
  - Sepal Width
  - Petal Length
  - Petal Width
- **Classes:** 3

---

## 📈 Exploratory Data Analysis (EDA)

The notebook includes:

- Dataset overview
- Shape and data types
- Missing value check
- Descriptive statistics
- Species distribution
- Pairplot visualization
- Boxplots
- Correlation heatmap

---

## 🤖 Machine Learning Models

The following classification algorithms were implemented:

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Decision Tree
- Random Forest

---

## 📏 Model Evaluation

Each model is evaluated using:

- Accuracy Score
- Confusion Matrix
- Precision
- Recall
- F1-Score

The best-performing model is selected based on overall accuracy and evaluation metrics.

---

## 📸 Output Visualizations

The `graphs/` folder contains generated visualizations, including:

- Pairplot
- Boxplots
- Correlation Heatmap
- Model Evaluation Graphs

---

## ▶️ How to Run

1. Clone the repository

```bash
git clone https://github.com/your-username/DataScience-Task1.git
```

2. Navigate to the project folder

```bash
cd DataScience-Task1
```

3. Install the required libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

4. Open the notebook

```bash
jupyter notebook
```

5. Run all cells.

---

## 📚 Libraries Used

```python
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns

from sklearn.datasets import load_iris
from sklearn.model_selection import train_test_split

from sklearn.linear_model import LogisticRegression
from sklearn.neighbors import KNeighborsClassifier
from sklearn.tree import DecisionTreeClassifier
from sklearn.ensemble import RandomForestClassifier
```

---

## 🎯 Learning Outcomes

- Data preprocessing using Pandas
- Exploratory Data Analysis (EDA)
- Data visualization with Seaborn and Matplotlib
- Training multiple classification models
- Model comparison and evaluation
- Selecting the best-performing classifier

---

## 👨‍💻 Author

**Aadarsh Rao**

B.Tech CSE (Data Science)