# Customer-Churn-Prediction-Retention-Strategy-for-a-Fitness-Chain
Predict gym customer churn, identify high-risk segments, and deliver data-driven retention recommendations using classification and clustering models.

## Overview
This project analyses customer data from Model Fitness, a gym chain, to understand and reduce customer churn. The work combines exploratory analysis, churn prediction models, and customer segmentation to support a practical retention strategy.

The goal is to identify which customers are at risk of leaving, understand the drivers of churn, and provide actionable recommendations to improve customer engagement and loyalty.

---

## Business Objective
- Predict the probability of customer churn for the next month
- Identify key behavioural and contractual factors influencing churn
- Segment customers into meaningful groups
- Recommend targeted retention actions for high-risk segments

---

## Data
Source file:
- gym_churn_us.csv

Target:
- `Churn` — whether the customer churned in the following month

Key features include:
- demographics (age, gender)
- location and partnership indicators
- contract type and remaining duration
- visit frequency (lifetime vs current month)
- spending on additional services

---

## Analytical Workflow

### 1) Exploratory Data Analysis (EDA)
- Review missing values and feature distributions
- Compare averages for churned vs retained customers
- Visualise feature distributions and correlations

### 2) Churn Prediction Models
- Split data into training and validation sets
- Train and evaluate:
  - Logistic Regression
  - Random Forest
- Compare accuracy, precision, and recall to select the best model

### 3) Customer Segmentation
- Standardise features
- Explore cluster structure with hierarchical clustering
- Apply K-means clustering (n = 5)
- Analyse cluster profiles and churn rates by segment

---

## Key Outputs
- Churn prediction model performance comparison
- Identification of features most associated with churn
- Customer segments with distinct behaviour and churn risk
- Cluster-level churn rates
- Retention recommendations based on segment profiles

## Objective
Analyse customer behaviour to predict churn risk, identify key drivers of cancellation, and design data-driven retention recommendations for a gym chain.

## 1) Data Overview & Preparation
Load the dataset, review feature types, check for missing values, and validate data quality.

## 2) Exploratory Data Analysis
- Summary statistics and distributions
- Comparison of churned vs retained customers
- Correlation analysis to identify influential features

## 3) Churn Prediction Modelling
- Split data into training and validation sets
- Train Logistic Regression and Random Forest models
- Evaluate accuracy, precision, and recall
- Select the model with the best overall performance

## 4) Customer Segmentation
- Standardise features
- Explore cluster structure using hierarchical clustering
- Build K-means model (n = 5)
- Analyse cluster profiles and churn rates

## 5) Conclusions & Retention Recommendations

Summarise key churn drivers, identify high-risk segments, and propose practical retention actions to reduce customer attrition.
The analysis highlights clear behavioural patterns linked to churn, particularly visit frequency, contract duration, and engagement with additional services.  
Based on these insights, targeted retention actions are proposed for high-risk segments, such as contract renewal incentives and engagement-focused interventions.
---

## Tools
Python, pandas, scikit-learn, matplotlib/seaborn, SciPy, Jupyter Notebook
---

## Author
**Erika González**  
MBA | Marketing & Data Analytics  
Focus areas: Customer Analytics, Predictive Modelling, Retention Strategy
