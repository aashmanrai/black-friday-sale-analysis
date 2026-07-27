# 🛍️ Black Friday Sales Analysis and Purchase Prediction using Python

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-F7931E?logo=scikitlearn)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-blue)
![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Visualization-4C72B0)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?logo=jupyter)

---

## 📌 Project Overview

This project analyzes the **Black Friday Sales Dataset** using Python to understand customer purchasing behavior and identify the factors that influence purchase amounts. The notebook covers the complete workflow from data cleaning and exploratory data analysis (EDA) to feature engineering and machine learning model development for purchase prediction.

---

## 🎯 Objectives

- Clean and preprocess the dataset.
- Perform Exploratory Data Analysis (EDA).
- Analyze customer purchasing behavior.
- Engineer useful features for machine learning.
- Train and compare multiple regression models.
- Evaluate model performance using regression metrics.
- Identify important features influencing purchase amount.

---

## 📂 Dataset

The dataset contains information about customer demographics, product categories, and purchase amounts during Black Friday sales.

It includes features such as:

- User ID
- Product ID
- Gender
- Age
- Occupation
- City Category
- Stay in Current City Years
- Marital Status
- Product Category 1
- Product Category 2
- Product Category 3
- Purchase Amount

---

# 🧹 Data Preprocessing

The following preprocessing steps were performed:

- Loaded the dataset using Pandas.
- Inspected dataset dimensions and data types.
- Checked for missing values.
- Filled missing values in Product_Category_2 and Product_Category_3.
- Checked for duplicate records.
- Converted `Stay_In_Current_City_Years` into numeric format.
- Saved and reloaded the cleaned dataset.

---

# 📊 Exploratory Data Analysis (EDA)

The notebook includes visual analysis of:

- Purchase amount distribution
- Gender-wise purchase analysis
- Age-wise purchase analysis
- City category analysis
- Purchase outlier detection using boxplots
- Correlation heatmap

These visualizations help understand purchasing patterns across different customer segments.

---

# ⚙️ Feature Engineering

The project includes feature engineering to improve model performance.

Performed tasks include:

- Creating additional numerical features.
- Preparing data for machine learning.
- Selecting relevant features.
- Encoding categorical variables.

---

# 🤖 Machine Learning Models

The following regression algorithms were implemented and compared:

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- Gradient Boosting Regressor

---

# 📈 Model Evaluation

The models were evaluated using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- R² Score

The notebook also includes a comparison of model performance and discusses the trade-offs between Random Forest and Gradient Boosting.

---

# ⭐ Feature Importance

Feature importance analysis was performed using the selected machine learning model to identify which variables contributed the most to predicting purchase amounts.

---

# 🛠️ Technologies Used

- Python
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

# 📁 Project Structure

```
Black-Friday-Sales-Analysis/
│
├── Black-Friday.ipynb
├── Black_Friday_sales.csv
├── cleaned_black_friday.csv
└── README.md
```

---

# 🚀 Key Learning Outcomes

- Data Cleaning and Preprocessing
- Exploratory Data Analysis
- Feature Engineering
- Feature Selection
- Regression Modeling
- Model Comparison
- Performance Evaluation
- Feature Importance Analysis
- Data Visualization using Matplotlib and Seaborn

---

# 📬 Author

**Aashman Rai**

BCA (Artificial Intelligence & Machine Learning)

Galgotias University

---
