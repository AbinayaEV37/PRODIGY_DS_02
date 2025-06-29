# PRODIGY_DS_02

## 📌 Internship Task 02 – Data Cleaning & Exploratory Data Analysis (EDA)

This project focuses on performing **data cleaning** and **exploratory data analysis (EDA)** on the famous **Titanic dataset** from [Kaggle](https://www.kaggle.com/c/titanic/data).

The goal was to uncover patterns in survival based on different passenger features like **gender**, **class**, **age**, and **embarkation point**.

## Dataset

- Dataset used: [`train.csv`](https://www.kaggle.com/c/titanic/data)
- Source: Kaggle Titanic: Machine Learning from Disaster

## 🛠️ Tools & Libraries Used

- **Google Colab**
- **Python 3**
  - pandas
  - matplotlib
  - seaborn

## Data Cleaning

- Handled missing values in:
  - Age: filled with median
  - Embarked: filled with mode
  - Cabin: dropped due to too many missing values
- Converted categorical data for better visualization


## 📊 Exploratory Data Analysis (EDA)

### 1️⃣ Survival Count

- Counted total survivors vs. non-survivors

### 2️⃣ Survival by Gender

- Women had a significantly higher survival rate than men

### 3️⃣ Survival by Passenger Class

- Passengers in **1st class** had a higher survival rate than those in **3rd class**

### 4️⃣ Age Distribution

- Most passengers were between **20–40 years old**
- Some young children and elderly passengers were present
- Used histograms and KDE curves to study age distribution


## 📈 Key Insights

- **Gender** and **class** played a major role in survival likelihood
- **Children** and **1st class passengers** had better survival odds
- **Most 3rd class male passengers did not survive**


## 🗂️ Files in This Repo

| File Name              | Description                                 |
|------------------------|---------------------------------------------|
| `titanic_eda.ipynb`    | The main Colab notebook with all code, plots, and markdown |
| `README.md`            | Project documentation (this file)          |

