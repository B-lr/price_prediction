# House Price Prediction – Ames Housing Dataset

##  Overview

This project focuses on building a machine learning model to predict the final sale prices of residential homes in Ames, Iowa. The dataset consists of 79 explanatory variables describing various aspects of each property, including structural features, quality, and location.

The objective is to leverage feature engineering and ensemble learning techniques to develop an accurate predictive model and uncover key factors influencing housing prices.

---

##  Objectives

* Predict house sale prices using structured tabular data
* Perform data preprocessing and feature engineering
* Train and evaluate ensemble-based regression models
* Analyze factors affecting property valuation

---

##  Dataset

* Source: Kaggle – House Prices: Advanced Regression Techniques
* https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/data
* Features: 79 explanatory variables
* Target Variable: `SalePrice`

---

##  Methods & Approach

###  Data Quality Checks

* Handled missing values using appropriate imputation techniques
* Encoded categorical variables for model compatibility
* Ensured dataset consistency and readiness for modeling

###  Feature Engineering

* Created new features to capture additional information
* Transformed and refined existing variables
* Improved predictive power through meaningful feature extraction

###  Model Selection

* Random Forest Regressor chosen for its robustness and ability to handle complex feature interactions

###  Model Training & Tuning

* Split dataset into training and validation sets
* Trained model on processed dataset
* Applied a sliding window technique for prediction (if applicable to workflow)

---

##  Results
* Model Evaluation Metric: RMSE (Root Mean Squared Error)
* Achieved RMSE: **0.0045268817600401775**

The model demonstrates strong predictive performance, indicating effective feature engineering and model selection.

---

