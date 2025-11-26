# Urgency Prediction for Cases

This project aims to predict whether a case is urgent or not based on the features provided in the dataset. The system uses machine learning models to analyze the data and make predictions with high accuracy.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Data Preprocessing](#data-preprocessing)
- [Models used](#models-used)
- [Performance](#performance)
- [Future Work](#future-work)

---

## Overview

The project is designed to classify cases as **urgent** or **not urgent** using the features in the dataset. It involves preprocessing the data, analyzing it through exploratory data analysis (EDA), and training machine learning models to achieve accurate predictions.

---

## Features

- Predicts urgency of cases using machine learning.
- Handles missing values and duplicates effectively.
- Implements multiple classification models for comparison.
- Achieves an accuracy of **~81%**.

---

## Technologies Used

- **Python 3.12**
- **Libraries:**
  - pandas
  - numpy
  - scikit-learn
  - matplotlib
  - seaborn

---

## Data Preprocessing

The dataset underwent the following preprocessing steps:
1. **Exploratory Data Analysis (EDA):** 
   - Visualized feature distributions and relationships.
   - Identified patterns and anomalies.
2. **Data Cleaning:**
   - Handled missing values by either filling them with appropriate values or dropping records where necessary.
   - Removed duplicate entries.
3. **Feature Engineering:**
   - Applied label encoding to transform categorical variables into numeric representations.

---

## Models used

Three machine learning models were implemented:
1. **Logistic Regression**
2. **K-Nearest Neighbors (KNN)**
3. **Random Forest Classifier**

The models were trained and evaluated using common metrics like accuracy, recall, F1 score and Precission.

---


## Performance

The models achieved the following accuracy:
- **Logistic Regression:** ~78%
- **KNN:** ~81%
- **Random Forest:** ~80%

The Random Forest and KNN performed slightly better and are recommended for deployment.


