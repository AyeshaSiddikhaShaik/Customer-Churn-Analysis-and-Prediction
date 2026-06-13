# Customer Churn Analysis and Prediction using Machine Learning

## Project Overview

Customer churn is one of the most critical challenges faced by subscription-based businesses. This project analyzes customer subscription behavior and develops a machine learning model to predict customer churn.

The objective is to identify key behavioral patterns that influence churn and provide actionable business recommendations for customer retention.

---

## Dataset Information

* Total Records: 2,800 Customers
* Features: Subscription Plan, Monthly Fee, Weekly Usage Hours, Support Tickets, Payment Failures, Tenure, Login Activity
* Target Variable: Churn

---

## Project Workflow

### Data Preprocessing

* Data Quality Assessment
* Missing Value Analysis
* Feature Encoding
* Feature Selection

### Exploratory Data Analysis

* Churn Distribution Analysis
* Subscription Plan Analysis
* Customer Engagement Analysis
* Payment Failure Analysis
* Support Ticket Analysis
* Login Activity Analysis

### Machine Learning

* Logistic Regression Model
* Train-Test Split
* Model Evaluation
* Confusion Matrix
* Classification Report
* Feature Importance Analysis

---

## Key Findings

* Payment failures emerged as the strongest predictor of customer churn.
* Customers with higher support ticket volumes showed increased churn probability.
* Lower engagement and inactivity were strongly associated with churn.
* Subscription plan type alone had limited influence on churn behavior.

---

## Model Performance

| Metric   | Value  |
| -------- | ------ |
| Accuracy | 65.36% |

The model demonstrated moderate predictive performance and successfully identified major churn patterns within the dataset.

---
## Model Evaluation

The Logistic Regression model was evaluated using:

- Accuracy Score
- Confusion Matrix
- Classification Report
- Precision, Recall, and F1-score

The model achieved an accuracy of 65.36% and demonstrated better identification of churn customers, achieving higher recall for churn prediction.

## Project Visualizations

### Customer Churn Distribution

Visual analysis of churned and retained customers to understand overall churn patterns.

![Churn Distribution](churn_distribution.png)


### Confusion Matrix

Evaluation of model predictions showing correctly and incorrectly classified customers.

![Confusion Matrix](confusion_matrix.png)



## Business Recommendations

* Implement proactive payment failure alerts.
* Monitor high support-ticket customers for retention campaigns.
* Re-engage inactive users through personalized offers.
* Develop churn risk monitoring systems for early intervention.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Google Colab

---

## Future Enhancements

Future improvements include:

* Implementing advanced models such as Random Forest and XGBoost.
* Applying hyperparameter optimization techniques.
* Developing a real-time customer churn prediction dashboard.
* Deploying the model as an interactive ML application.
  
---
 ## Project Impact

This project demonstrates how machine learning can transform customer behavior data into actionable retention strategies. By identifying early churn signals, businesses can move from reactive customer management to proactive retention.

## Author

Ayesha Siddikha 

B.Tech Artificial Intelligence & Data Science

