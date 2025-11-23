# Amazon_EDA

This project focuses on predicting customer churn for Amazon Prime using machine learning techniques. The goal is to identify patterns that lead users to unsubscribe and help the business make data-driven retention decisions.

Project Objective

Analyze user behavior and subscription patterns

Identify factors contributing to churn

Build ML models to predict churn probability

Recommend actionable business insights to improve customer retention

Dataset Overview
Feature Type	Examples
Numerical	Age, Watch Time, Monthly Spend, Review Score
Categorical	Gender, Subscription Plan, Device Type, Region
Target Variable	Churn (0 = No, 1 = Yes)

Data Preprocessing Steps

Handled missing values

Encoded categorical features

Scaled numerical columns

Checked imbalance & applied SMOTE

Feature correlation & multicollinearity check

Exploratory Data Analysis (EDA)

Key insights discovered:

Users with lower watch time show a higher churn rate

Single-month and trial users churn more than annual members

Lower satisfaction scores correlate with higher churn

Multiple visualizations were used including heatmaps, bar charts, histograms, boxplots, and churn distribution charts.

Feature Importance & Explainability

Tools used:

SHAP values

Feature importance plot

Partial Dependence Plots

Top predictive features include:

Subscription tenure

Watch frequency

Review score

Payment failure occurrences

Business Recommendations

Improve engagement for low-watch-time users

Send reminders before payment lapses

Personalized offers based on viewing habits

Incentives for long-term subscription plans

Conclusion

The project successfully identifies churn drivers and predicts customer churn with high reliability. The insights and model can help Amazon Prime reduce churn, improve customer satisfaction, and optimize retention strategy.
