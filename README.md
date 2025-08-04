# TASK_1_Elevate_Labs

# 🧹 Titanic Data Cleaning & Preprocessing

This project focuses on cleaning and preparing the Titanic dataset for machine learning applications. It covers the essential preprocessing steps needed before feeding the data into a model.

## 📁 Dataset
- **Source**: Titanic dataset (`Titanic-Dataset.csv`)
- **Records**: 891 passengers
- **Features**: 12 columns including categorical and numerical data

## 🎯 Objectives
1. Import and explore the dataset (data types, nulls)
2. Handle missing values using mean/median/imputation
3. Convert categorical features into numerical using encoding
4. Normalize/standardize numerical features
5. Visualize and remove outliers using boxplots

## 🛠️ Tools & Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## 🧪 Preprocessing Steps

### 1. Load & Explore Data
- Checked data types, missing values, and basic statistics using `info()`, `describe()`, and `isnull().sum()`.

### 2. Handle Missing Values
- Imputed `Age` with median value.
- Filled `Embarked` with the mode.
- Dropped `Cabin` due to excessive missing values.

### 3. Encode Categorical Variables
- One-hot encoding applied to:
  - `Sex`
  - `Embarked`

### 4. Normalize Numerical Features
- Used `StandardScaler` on:
  - `Age`
  - `Fare`
  - `SibSp`
  - `Parch`

### 5. Outlier Detection & Removal
- Used boxplots to visualize outliers.
- Removed outliers using the IQR method.

## 📊 Outcome
- Final cleaned dataset is free from nulls, encoded, normalized, and stripped of outliers — ready for training ML models.

---

> **Author**: _A Paritosh_

