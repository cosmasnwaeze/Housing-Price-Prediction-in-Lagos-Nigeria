# Housing-Price-Prediction-in-Lagos-Nigeria
To develop an accurate predictive model that can forecast housing prices in Lagos, Nigeria, and identify the most influential factors affecting housing prices

![Housing Market](https://i.postimg.cc/43tF36JH/LAGOS.jpg)

## Introduction
The real estate market in Lagos is dynamic, with property prices influenced by various factors such as location, number of bedrooms, and amenities. Accurately predicting housing prices can help buyers, sellers, and investors make informed decisions. In this notebook, we will analyze a dataset containing property listings and develop a machine learning model to predict housing prices in Lagos.

### Objective
To develop a predictive model using machine learning algorithms to forecast housing prices in Lagos, Nigeria.

### Summary Objective
- Analyzing the real estate market in Lagos to create a predictive model that can help stakeholders make informed decisions.
- To analyze the relationship between various factors and housing prices in Lagos, Nigeria.
- To develop an accurate predictive model that can forecast housing prices in Lagos, Nigeria, and identify the most influential factors affecting housing prices.

### Methodology
The project will utilize a dataset from **Open Africa** (https://open.africa/dataset/cost-of-housing-in-lagos) containing information on housing prices in Lagos. The dataset will be preprocessed, and four machine learning models will be implemented:

1. **Linear Regression Model**
2. **Random Forest Regressor**
3. **Gradient Boosting Regressor**
4. **Support Vector Regressor (SVR)**

The project aims to:
1. Develop a predictive model that can accurately forecast housing prices in Lagos, Nigeria.
2. Evaluate the performance of the four machine learning models.
3. Identify the most influential factors affecting housing prices in Lagos.

### Conclusion
This project will contribute to the understanding of the real estate market in Lagos, Nigeria, and provide a valuable tool for stakeholders to make informed decisions.

### Recommendations
Future research can focus on incorporating additional data sources, exploring other machine learning algorithms, and developing a web-based application for easy access to the predictive model.

## Table of Contents

- [Importing Libraries](#importing-libraries)
- [Loading Data](#loading-data)
- [Data Overview to Understand Its Structure](#data-overview-to-understand-its-structure)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Data Preprocessing](#data-preprocessing)
- [Modeling](#modeling)
- [Results](#results)


The best-performing model is Gradient Boosting Regressor with an R2 score of 0.5787.
Future improvements can include incorporating additional features,
further hyperparameter tuning, and utilizing deep learning models for better accuracy.

### Communicating Feature Importance
10 most important features affecting housing prices.

| Feature          | Importance   |
|-------------------|-----------------|
| Furnished        | 0.000237        |
| Newly Built      | 0.001586        |
| Bathrooms        | 0.004039        |
| Serviced         | 0.021215        |
| Toilets          | 0.036799        |
| City             | 0.370092        |
| Bedrooms         | 0.566033        |
