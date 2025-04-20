# 🏦 Bank Marketing Classification
This project aims to analyze marketing campaign data from a bank to predict whether a customer will subscribe to a term deposit. The classification model helps identify high-potential customers and optimize campaign strategies.

## 📂 Dataset Source
[Bank Marketing Dataset - UCI Repository](https://archive.ics.uci.edu/ml/datasets/Bank+Marketing)

# 📚 Business Understanding

## 📌 Background
The bank has been running marketing campaigns to promote term deposit subscriptions. However, the success rate is relatively low. By utilizing machine learning, we aim to identify which customers are more likely to make a deposit and adjust marketing strategies accordingly. This approach helps reduce campaign costs and increase overall effectiveness.

## 🌟 SMART Analysis
**Specific:** Improve the success rate of term deposit subscriptions by targeting the right customers using predictive modeling.

**Measurable:** Increase the deposit subscription rate from the current baseline to a higher percentage determined through model evaluation.

**Achievable:**
- Analyze key customer attributes such as age, job, balance, and contact history to find patterns.
- Use classification models to predict the likelihood of a customer subscribing.
- Focus campaigns on high-potential customer segments.

**Relevant:**
Identifying high-conversion customers helps reduce campaign inefficiencies and improve ROI. Better customer targeting will also improve customer experience and response rates.

**Time-bound:** Implement and evaluate the model's impact within a 3-month campaign cycle.

## ✅ Problem Breakdown
- What customer features influence the likelihood of subscribing to a term deposit?
- Which customer segments have the highest conversion rates?
- How do marketing channels and contact timing affect deposit subscription?
- Which classification models yield the best performance for this task?

## 👥 Target Users
Bank Marketing Team and Decision-Makers

## 🧰 Tools & Technologies Used
Python: Used for data preprocessing, modeling, and evaluation. Key libraries include:
  - pandas for data manipulation
  - matplotlib and seaborn for visualization
  - scikit-learn for machine learning models
  - xgboost, catboost, and lightgbm for advanced classification algorithms

## 📊 Model Comparison
Various models were tested including:
- Logistic Regression
- Decision Tree
- Random Forest
- KNN
- Support Vector Machine
- Naive Bayes
- XGBoost, AdaBoost, GradientBoosting, CatBoost

Each model was evaluated based on:
- Accuracy
- Recall
- Precision
- F1 Score
- ROC AUC
- PR AUC

## 🚀 Inference
📁 [Bank-Marketing-Classification-Inference.ipynb](https://github.com/ianyusuf/BankMarketingClassification/blob/main/Bank-Marketing-Classification-Inference.ipynb)

Model inference is available in a separate notebook to show how the final model can be used in production for predicting new customer data.

## 🧠 Insights
- Customers with higher balances and those contacted via cellular are more likely to subscribe.
- The outcome of previous campaigns significantly affects future success.
- Some job categories have much higher conversion rates than others.

## 📌 Author
**Hadyan Yusuf Imran**  
📧 [LinkedIn](https://www.linkedin.com/in/ianyusuf/)  
🎓 Final Project - Data Science Bootcamp
