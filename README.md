# Telecom Customer Churn Prediction

## Objective
The goal of this project is to predict whether a customer will churn from a telecommunications company. Churn refers to customers discontinuing their services with the company. This project analyzes customer demographics, services, tenure, and other factors to understand the reasons behind customer churn and develop a predictive model to forecast churn.

## Data Overview
The dataset used in this project contains information about customers' demographics, services they subscribed to, and whether they churned. The data is used to build a machine learning model that predicts the likelihood of customer churn.

### Columns in the dataset:
- **CustomerID**: Unique identifier for each customer.
- **Demographics**: Customer age, gender, and other demographic details.
- **Services**: Information on the services used by the customer (e.g., phone service, internet service).
- **Tenure**: Duration for which the customer has been with the company.
- **Churn**: Whether the customer has churned or not.

## Data Preprocessing
Data preprocessing includes:
- Handling missing values.
- Encoding categorical variables.
- Normalizing numerical features.
- Splitting the data into training and testing sets.

## Exploratory Data Analysis (EDA)
In the exploratory data analysis phase, we visualize the dataset to uncover trends and patterns that can guide our predictions.

### Service Usage:
- **Phone Service**: Around 6,000 customers have opted for phone service, with a significant portion (around 50%) using multiple lines.
- **Internet Service**: Approximately 5,500 customers have subscribed to internet services. Among them, 3,000 customers have opted for fibre optics, while the rest prefer DSL.
- **Other Services**: 
  - **Online Backup** and **Device Protection**: Approximately 2,500 customers opted for these services, indicating concern for data and device protection.

## Models Built
This project uses various machine learning models to predict customer churn. Models include:
- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- Gradient Boosting Classifier
- XGBoost Classifier

### Model Evaluation
Each model is evaluated using the following metrics:
- **Accuracy**: The percentage of correct predictions.
- **Precision**: The proportion of positive predictions that are actually correct.
- **Recall**: The proportion of actual positive instances correctly predicted.
- **F1-Score**: A balance between precision and recall.

## Conclusion
The project aims to provide valuable insights into customer churn, helping the telecom company to take preventive actions. The final model can predict with high accuracy whether a customer is likely to churn, enabling the company to target these customers with retention strategies.

## Requirements
- Python 3.x
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- XGBoost

## Installation
1. Clone the repository.
2. Install the necessary dependencies using pip:
 ```bash
python churn_prediction.py
