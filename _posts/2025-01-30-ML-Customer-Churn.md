---
title: "Customer Churn Prediction"
date: 2025-01-29 00:00:00 -0700
image: assets/images/Customer-Churn.png
categories: [Machine Learning]
tags: [machine learning, python, jupyter, pandas, sklearn, flask, deployment]     # TAG names should always be lowercase
---

# Customer Churn Prediction

## Project Overview:
This project focuses on predicting customer churn using machine learning models. The objective was to analyze customer data, identify key factors influencing churn, and deploy a predictive model to classify customers as likely to churn or not.

### Key questions explored:
- **What are the primary factors contributing to customer churn?**
- **How accurately can we predict churn using machine learning models?**
- **Which features are most important in determining churn probability?**
- **How can businesses use this model to retain customers?**

## Dataset
### Source
The dataset used in this analysis was obtained from Kaggle and contains detailed customer information, including demographics, usage patterns, and account details.

### Contents
The dataset includes the following key columns:

Customer ID: Unique identifier for each customer.
- **Subscription Length**: Number of months the customer has been with the company.
- **Monthly Charges**: Monthly subscription fees.
- **Total Charges**: Total amount billed.
- **Contract Type**: Type of customer contract (monthly, yearly, etc.).
- **Payment Method**: The method used by the customer for payments.
- **Customer Support Calls**: Number of times the customer contacted support.
- **Churn**: Whether the customer left (1) or stayed (0).

## Objective
The primary objectives of this analysis are:
- To build a machine learning model that accurately predicts customer churn.
- To identify key features influencing customer retention.
- To provide actionable insights to reduce churn rates.
- To deploy a web-based application for real-time predictions.

## Analysis

### Tools and Libraries Used

- **Python**: Core programming language for data analysis and modeling.

- **Jupyter Notebook**: For data exploration and model development.

- **pandas & NumPy**: For data manipulation and preprocessing.

- m**atplotlib & seaborn**: For data visualization.

- **scikit-learn**: For building machine learning models.

- **Flask**: For deploying the model as a web application.

### Steps Undertaken

**Data Preprocessing**:
- Handling missing values.
- Converting categorical variables into numerical representations.
- Standardizing and normalizing features.

**Exploratory Data Analysis**:
- Analyzing churn distribution across different features.
- Identifying correlations between churn and key attributes.
- Visualizing feature importance using bar plots and heatmaps.

**Feature Engineering**:
- Creating new features such as tenure categories.
- Encoding categorical variables.
- Selecting the most relevant features based on statistical tests.

**Model Building & Evaluation**:
- Training different models (Logistic Regression, Decision Trees, Random Forest, XGBoost).
- Comparing models using metrics like accuracy, precision, recall, and F1-score.
- Fine-tuning hyperparameters for the best performance.

**Model Deployment**:
- Saving the trained model using pickle.
- Creating a Flask web application for real-time predictions.
- Deploying the application on a cloud server for accessibility.

## Key Insights:
- **High-Risk Customers**: Customers with month-to-month contracts and high monthly charges were most likely to churn.
- **Payment Methods**: Those using electronic check payments showed a higher churn rate.
- **Customer Support Impact**: A high number of support calls correlated with a higher likelihood of churn.
- **Retention Strategies**: Offering loyalty incentives to high-risk customers can help reduce churn.

## Real-World Applications:

- **Customer Retention Strategies**: Businesses can use churn prediction models to identify and target high-risk customers with retention campaigns.

- **Personalized Marketing**: Companies can provide special offers to customers likely to churn based on model predictions.

- **Optimized Customer Support**: Customer support teams can proactively engage with at-risk customers to resolve issues and improve satisfaction.

- **Revenue Growth**: Reducing churn directly impacts revenue by maintaining a stable customer base.

## Project Notebook

<div style="display: flex; justify-content: flex-start;">
    <iframe title="Universities Analysis" width="900" height="541.25" 
            src="https://nbviewer.org/github/sikmat/ML-Churn-Prediction/blob/main/churn_prediction.ipynb"
            frameborder="0" allowFullScreen="true">
    </iframe>
</div>
<video src="assets/churn.webm"></video>

#### [GitHub Project Link](<https://github.com/sikmat/ML-Churn-Prediction>)