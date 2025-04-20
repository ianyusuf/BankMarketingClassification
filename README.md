# Bank Marketing Classification - Hadyan Yusuf Imran

This repository contains a classification project using the Bank Marketing dataset from the UCI Machine Learning Repository. The objective is to predict whether a customer will subscribe to a term deposit product based on their attributes and campaign data.

## Dataset

The dataset used is publicly available and contains 11 attributes:

- **age**: age of the customer
- **job**: type of job
- **balance**: average yearly balance in euros
- **housing**: whether the customer has a housing loan
- **loan**: whether the customer has a personal loan
- **contact**: contact communication type
- **month**: last contact month of year
- **campaign**: number of contacts performed during this campaign
- **pdays**: number of days passed since the client was last contacted (if -1, client was not previously contacted)
- **poutcome**: outcome of the previous marketing campaign
- **deposit**: target variable, whether the client subscribed to a term deposit

## Objective

The project aims to build a classification model that can help marketing teams target potential customers more effectively by predicting the likelihood of a customer subscribing to a deposit product.

## Steps

1. **Data Cleaning**  
   Handle missing values, drop or replace unknowns, convert categorical variables, etc.

2. **Exploratory Data Analysis (EDA)**  
   Analyze distribution of key features, correlation between variables, and class imbalance.

3. **Feature Engineering**  
   - One-hot encoding for categorical variables
   - Binning continuous features (if applicable)

4. **Model Building**  
   Models used include:
   - Logistic Regression
   - Decision Tree
   - Random Forest
   - Support Vector Machine
   - K-Nearest Neighbors
   - XGBoost
   - AdaBoost
   - CatBoost
   - Naive Bayes
   - Gradient Boosting

5. **Model Evaluation**  
   Metrics evaluated:
   - Accuracy
   - Recall
   - Precision
   - F1 Score
   - ROC AUC
   - PR AUC

6. **Model Inference**  
   Final model saved and inference shown in separate notebook.

## Results

The best-performing models are selected based on F1 Score and ROC AUC. Insights from feature importance are also used to support business decision-making.

## Deployment

The model can be further deployed using:
- Flask or FastAPI for API endpoints
- Streamlit for interactive web app
- Integration with CRM tools for targeting

## Author

**Hadyan Yusuf Imran**  
📧 [LinkedIn](https://www.linkedin.com/in/ianyusuf/)  
📌 Final Project - Data Science Bootcamp  

