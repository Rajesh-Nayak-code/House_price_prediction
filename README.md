# House Price Prediction - Data Cleaning & Preprocessing Pipeline

## Overview

This project demonstrates a complete machine learning data preparation workflow on a house price dataset. The primary focus of this project is data understanding, cleaning, visualization, preprocessing, and preparing the dataset for machine learning models.

---

## Objectives

* Understand the dataset structure
* Perform Exploratory Data Analysis (EDA)
* Identify missing values and duplicates
* Analyze categorical and numerical features
* Detect potential outliers
* Handle missing values
* Encode categorical variables
* Scale numerical features
* Split data into training and testing sets
* Train a baseline Linear Regression model
* Evaluate model performance using R² Score

---

## Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-Learn

---

## Project Workflow

### 1. Data Loading

* Load dataset using Pandas
* Inspect dataset dimensions

### 2. Exploratory Data Analysis (EDA)

* Dataset shape
* Top and bottom records
* Data types
* Missing value analysis
* Statistical summary
* Duplicate value detection
* Unique categorical value analysis

### 3. Data Visualization

#### Price Distribution

* Histogram
* Kernel Density Estimation (KDE)

#### Correlation Analysis

* Correlation heatmap with target variable (Price)

#### Outlier Detection

* Boxplot visualization

### 4. Data Cleaning

#### Missing Numerical Values

* Replaced using column mean

#### Missing Categorical Values

* Replaced with "Unknown"

#### Duplicate Detection

* Dataset checked for duplicate records

### 5. Data Preprocessing

#### Feature Encoding

* One-Hot Encoding using `pd.get_dummies()`

#### Train-Test Split

* 80% Training Data
* 20% Testing Data

#### Feature Scaling

* MinMaxScaler

### 6. Model Training

* Linear Regression

### 7. Model Evaluation

* R² Score

---

## Key Learning Outcomes

* Data cleaning techniques
* Exploratory data analysis
* Visualization using Seaborn and Matplotlib
* Handling categorical variables
* Feature scaling
* Train-test splitting
* Building a basic regression model
* Evaluating machine learning models

---

## Future Improvements

* Feature Engineering
* Feature Selection
* Multiple Regression Models
* Cross Validation
* Hyperparameter Tuning
* Model Comparison
* Pipeline Automation


