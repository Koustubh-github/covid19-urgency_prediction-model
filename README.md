# Urgency Prediction for Cases

This project focuses on predicting whether a case is **urgent** based on the features provided in the dataset. It leverages machine learning models to analyze the data and deliver accurate predictions.  

---

## Table of Contents
- [Overview](#overview)  
- [Features](#features)  
- [Technologies Used](#technologies-used)  
- [Data Preprocessing](#data-preprocessing)  
- [Models Used](#models-used)  
- [Performance](#performance)  
- [Future Work](#future-work)  

---

## Overview
The project classifies cases as **urgent** or **non-urgent** by analyzing dataset features. It includes data preprocessing, exploratory data analysis (EDA), and training of machine learning models to achieve reliable predictions.  

---

## Features
- **Predicts case urgency using machine learning.**  
- **Effectively handles missing values and duplicate records.**  
- **Implements multiple classification models for comparison.**  
- **Achieves up to ~81% prediction accuracy.**  

---

## Technologies Used
- **Python 3.12**  
- **Libraries:** `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`  

---

## Data Preprocessing
The dataset was prepared through several steps:  

**Exploratory Data Analysis (EDA):**  
- Visualized feature distributions and relationships.  
- Identified patterns and anomalies.  

**Data Cleaning:**  
- Handled missing values by imputing or removing records.  
- Removed duplicate entries.  

**Feature Engineering:**  
- Applied label encoding to convert categorical variables into numeric form.  

---

## Models Used
Three machine learning models were trained and evaluated:  

- **Logistic Regression**  
- **K-Nearest Neighbors (KNN)**  
- **Random Forest Classifier**  

Evaluation metrics included **accuracy**, **recall**, **precision**, and **F1 score**.  

---

## Performance
| Model                  | Accuracy |
|------------------------|---------|
| Logistic Regression     | ~78%    |
| KNN                     | ~81%    |
| Random Forest Classifier| ~80%    |

KNN and Random Forest slightly outperformed Logistic Regression and are recommended for deployment.  

---

## Future Work
- Explore additional machine learning models like **XGBoost** or **LightGBM** for improved performance.  
- Implement **hyperparameter tuning** to optimize model accuracy.  
- Deploy the model using a **web interface or API** for real-time predictions.  
- Expand the dataset to include more features for better generalization.  
