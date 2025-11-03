# Machine Learning Portfolio

Welcome to my Machine Learning Portfolio! This repository showcases projects that apply **Exploratory Data Analysis (EDA)**, **data visualization**, and **machine learning techniques** to solve real-world problems.

---

## Introduction
This portfolio demonstrates my ability to:
- Perform **data cleaning** and **statistical summarization**.
- Apply **EDA techniques** to uncover insights.
- Build and evaluate **machine learning models**.
- Create **visualizations** using libraries like Matplotlib, Seaborn, and Plotly.

---

## Projects
Here are some featured projects in this repository:

### 1. Titanic Survival Prediction
- **Description**: Analyze Titanic dataset, perform EDA, and build a classification model.
- **Techniques**: Data cleaning, visualization, logistic regression.
- **Notebook**: [Titanic_EDA_ML.ipynb](Titanic_EDA_ML.ipynb)

### 2. House Price Prediction
- **Description**: Predict house prices using regression models.
- **Techniques**: Feature engineering, correlation analysis, Random Forest.
- **Notebook**: [HousePrices_EDA_ML.ipynb](HousePrices_EDA_ML.ipynb)

---

## Installation
To run these projects locally:
```bash
git clone https://github.com/<your-username>/machine-learning-EDA-projects.git
cd machine-learning-EDA-projects
pip install -r requirements.txt
``

Practical_Application_1/
  ├── README.md
  ├── Practical_Application_1.ipynb
  ├── coupon_data.csv

import pandas as pd
import seaborn as sns
import matplotlib.pyplot as plt
df.info()
df.describe()
df.groupby('coupon')['Y'].mean()
sns.barplot(x='coupon', y='Y', data=df)
Visualizations:
plt.title('Acceptance Rate by Coupon Type')
plt.xlabel('Coupon Type')
plt.ylabel('Acceptance Rate')
fig, axes = plt.subplots(1, 2, figsize=(12, 5))
sns.histplot(df[df['Y']==1]['age'], ax=axes[0])
sns.histplot(df[df['Y']==0]['age'], ax=axes[1])




