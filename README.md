# On-Time-Delivery-Prediction-for-E-Commerce-Shipments-Using-Machine-Learning
Project Overview
This project aims to predict whether a product shipment will reach the customer on time using machine learning techniques. The dataset contains logistics-related information such as shipment method, product weight, discounts, and customer feedback. The goal is to build a classification model that can accurately predict delivery punctuality, helping businesses streamline operations and improve customer satisfaction.

Problem Statement
In e-commerce logistics, late deliveries can lead to customer dissatisfaction and increased operational costs. Predicting on-time delivery allows businesses to proactively manage delays and optimize resource allocation. This project uses historical shipment data to build a predictive model for delivery outcomes.

Objective
Perform data preprocessing including handling of missing values and negative values due to normalization.

Conduct exploratory data analysis (EDA) to understand feature distributions and relationships.

Encode categorical variables and normalize/scale numerical features.

Train multiple machine learning models for binary classification of delivery status.

Evaluate and tune the models to maximize prediction performance.

Compare models and select the most suitable one for deployment or insights.

Dataset Description
The dataset consists of 10,999 records and 12 features (excluding encoded dummies). The key features include:

Customer_care_calls: Number of calls made to customer service

Customer_rating: Customer rating of service (1–5)

Cost_of_the_Product: Product price

Prior_purchases: Number of previous purchases by the customer

Product_importance: Product importance (low, medium, high)

Gender: Customer gender

Discount_offered: Discount applied to the product

Weight_in_gms: Product weight in grams

Mode_of_Shipment: Shipping method used (Ship, Flight, Road)

Warehouse_block: Warehouse origin block (A–F)

Reached.on.Time_Y.N: Target variable (0 = Not on time, 1 = On time)

Techniques Used
Data Cleaning and Preprocessing

Handling of normalization issues and negative values

Label and One-Hot Encoding for categorical variables

Data Visualization (histograms, box plots, bar charts, heatmaps, pair plots)

Machine Learning Models:

Logistic Regression

Decision Tree

Random Forest

Support Vector Machine (SVM)

XGBoost

Hyperparameter Tuning (GridSearchCV)

Model Evaluation using:

Accuracy

Precision

Recall

F1-score

Confusion Matrix

ROC Curve and AUC Score

Results
Random Forest and XGBoost delivered strong results with high accuracy and generalization.

Logistic Regression provided a good baseline and interpretable coefficients.

Hyperparameter tuning improved model performance across all models.

Final model selected based on trade-off between performance metrics and interpretability.

Conclusion
This project demonstrates a complete machine learning pipeline for binary classification using real-world logistics data. The analysis highlights the importance of discount offered, mode of shipment, and product weight in predicting delivery outcomes. The chosen model can help e-commerce companies proactively manage shipments and enhance logistics planning.
