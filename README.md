# Diameter Prediction of Asteroids

This project focuses on predicting the diameter of asteroids using various machine learning models. The dataset contains detailed information about asteroids, including their physical and orbital characteristics. The goal is to preprocess the data, train multiple regression models, and evaluate their performance.

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Preprocessing](#preprocessing)
- [Models Used](#models-used)
- [Evaluation Metrics](#evaluation-metrics)

---

## Project Overview

Asteroids are celestial objects that orbit the Sun. Predicting their diameters is crucial for understanding their physical properties and assessing potential risks. This project uses machine learning techniques to predict asteroid diameters based on their features.

---

## Dataset

The dataset used in this project contains the following key columns:

- **Physical Properties**: Diameter, Albedo, Absolute Magnitude, etc.
- **Orbital Elements**: Eccentricity, Semi-Major Axis, Inclination, etc.
- **Flags**: Near-Earth Object (NEO), Potentially Hazardous Asteroid (PHA), etc.

The dataset is preprocessed to handle missing values, outliers, and irrelevant columns.

---

## Preprocessing

The following preprocessing steps were applied:
1. **Column Renaming**: Renamed columns for better readability.
2. **Missing Value Handling**: Imputed missing values using median for numerical columns and mode for categorical columns.
3. **Outlier Handling**: Used the IQR method to cap outliers.
4. **Feature Scaling**: Standardized numerical features using `StandardScaler`.
5. **Encoding**: Encoded categorical features using `LabelEncoder`.

---

## Models Used

The following regression models were trained and evaluated:
1. **Linear Regression**
2. **Decision Tree Regressor**
3. **K-Nearest Neighbors (KNN) Regressor**
4. **Random Forest Regressor**
5. **XGBoost Regressor**
6. **Lasso Regression**
7. **Ridge Regression**
8. **Polynomial Regression**

---

## Evaluation Metrics

The models were evaluated using the following metrics:
- **Mean Squared Error (MSE)**
- **R² Score**
- **Mean Absolute Error (MAE)** (for some models)

---
