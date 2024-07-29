# InsureWise: Risk and Premium Management

## Introduction

InsureWise leverages machine learning to improve premium assessment and minimize claim losses in car insurance. This project focuses on developing a predictive model to assess the probability of car insurance claims, allowing for more accurate premium settings and better risk management.

## Objectives

### Primary Goals
- **Develop a Predictive Model:** Create a robust model to assess the probability of car insurance claims.
- **Risk Assessment:** Estimate the likelihood of a claim within a specified period, enabling accurate premium settings and risk management.

### Secondary Goals
- **Identify Key Factors:** Analyze critical factors influencing claim probability.
- **Data Exploration:** Uncover insights into vehicle, policyholder, and policy characteristics contributing to higher claim risks.
- **Improve Risk Management:** Provide actionable insights to refine risk assessment and mitigation strategies.
- **Enhance Customer Satisfaction:** Offer personalized premiums and preventive measures to improve customer satisfaction and retention.

## Business Problem

Predicting car insurance claims accurately is a significant challenge due to the financial impact and complex risk factors. This project aims to address this challenge using advanced data analytics and machine learning techniques to:
- **Assess Claim Probability:** Provide accurate predictions of claim likelihood.
- **Optimize Premiums:** Enable precise and fair premium settings based on individual risk profiles.
- **Enhance Risk Management:** Offer insights into key risk factors for better strategies.
- **Improve Customer Experience:** Increase customer satisfaction through personalized and transparent insurance policies.

## Assumptions

- **Representative Dataset:** The dataset accurately represents the population of car insurance policyholders.
- **Sufficient Variables:** Provided variables are sufficient for accurate predictions.
- **Data Integrity:** Data is free from significant errors or biases.
- **Stable Relationships:** The relationship between variables and claim probability remains stable over time.

## Data Description

The dataset includes comprehensive details on factors influencing insurance claim probability, covering demographic, vehicle, and policy attributes. The target variable is "is_claim," indicating whether a claim has been made.

## Model Building and Evaluation

### Baseline Modeling
- **Logistic Regression:** Chosen for its transparency, efficiency, and interpretability.
- **Handling Outliers:** Mitigated through preprocessing and regularization techniques.

### Advanced Modeling
- **Classifiers Used:** Various classifiers including Decision Tree, Random Forest, Adaboost, Gradient Boosting, XGBoost, LightGBM, and CatBoost were explored.
- **Handling Imbalanced Data:** SMOTE was applied to balance class distribution.
- **Selected Model:** CatBoost showed the best performance in capturing minority class instances effectively.

## Recommendations

- **Insurance Interventions:** Targeted interventions for high-risk customers, including personalized premium rates and proactive support.
- **Key Insights:** Identified risk factors and predictive modeling to accurately predict claims and improve risk management.
- **Customer Segmentation:** Offer customized policies and interventions based on risk levels.

## Conclusion

The insights from this project provide a robust foundation for developing targeted interventions and policy adjustments. These strategies aim to reduce claim risks, enhance customer satisfaction, and improve overall efficiency in claim management for insurance companies. Together, we can make a difference in the insurance industry.
