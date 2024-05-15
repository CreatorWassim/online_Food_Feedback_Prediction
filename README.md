# **Predicting Customer Feedback on Online Food Orders**

### Introduction
This repository presents a machine learning project aimed at predicting customer feedback on their online food orders. The project utilizes demographic information, location data, and order details to construct a predictive model capable of classifying feedback as positive or negative.

original code on Kaggle: https://www.kaggle.com/code/wassimouledmohamed/online-food-feedback-prediction

### Objective
The primary objective of this project is to develop a machine learning model that accurately predicts customer feedback based on various factors such as age, gender, marital status, occupation, monthly income, educational qualifications, family size, location coordinates, pin code, and order status.

### Dataset
The dataset contains 388 entries with 13 columns, comprising both numerical and categorical data. It includes features such as age, gender, marital status, occupation, monthly income, educational qualifications, family size, latitude, longitude, pin code, order status, and customer feedback.
Dataset on Kaggle : https://www.kaggle.com/datasets/sudarshan24byte/online-food-dataset

### Data Processing
The data preprocessing phase involves handling missing values, encoding categorical variables, and normalizing numerical features. Missing values were not found in the dataset, and categorical encoding was performed using ordinal encoding and one-hot encoding techniques. Numerical features were standardized using a standard scaler.

### Prediction Model
The dataset was split into training and testing sets, with 60% of the data used for training and 40% for testing. A random forest classifier was chosen as the predictive model due to its ability to handle both numerical and categorical data effectively. Cross-validation was used to assess the model's performance, achieving an accuracy of 84.48%.

### Model Evaluation
The trained model was evaluated using precision, recall, and F1 score metrics. The precision, recall, and F1 score for predicting positive feedback were found to be 90.91%, 94.49%, and 92.66%, respectively. Confusion matrix visualization was used to further analyze the model's performance.

### Conclusion
By leveraging demographic information, location data, and order details, the developed model can assist online food platforms in predicting customer feedback accurately. This predictive capability enables businesses to identify areas for improvement, enhance customer satisfaction, and optimize service delivery.

### Note
The dataset exhibits class imbalance, with a larger proportion of instances representing positive feedback compared to negative feedback. When interpreting the model's performance, it's essential to consider this class imbalance and its potential impact on predictive accuracy.
