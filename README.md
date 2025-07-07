# 🚢 Task 2: Titanic Dataset – Data Cleaning and EDA

This project is part of the **Prodigy InfoTech Data Analyst Internship**.

---

## ✅ Objective

Perform data cleaning and exploratory data analysis (EDA) on the Titanic dataset to explore relationships between variables and identify meaningful patterns and trends.

---

## 📁 Dataset

- Source: [Kaggle Titanic Dataset](https://www.kaggle.com/c/titanic/data)
- Raw file included: [`Data/train.csv`](Data/train.csv) ✅


---

## 🧹 Data Cleaning Summary

- Filled missing `Age` values using the median
- Filled missing `Embarked` values using the mode
- Dropped the `Cabin` column (too many nulls)
- Dropped irrelevant columns: `Name`, `Ticket`, `PassengerId`
- Ensured no missing values remained

---

## 📊 Exploratory Data Analysis (EDA)

Performed visual analysis on:

- Survival by gender
- Passenger class
- Age distribution
- Correlation heatmap

📸 **Check the screenshots above in the repository for selected EDA visualizations.**

---

## 🧠 Key Insights

- Females had a significantly higher survival rate than males
- 1st class passengers survived more than 2nd or 3rd class
- Most passengers were between 20–40 years old
- Fare and Pclass showed moderate correlation with survival

---

## 💻 Tools Used

- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

---
