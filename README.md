# Telecom-Customer-Churn-Prediction

This project aims to predict customer churn for a telecom company using machine learning techniques. By analyzing customer data and building predictive models, the project seeks to identify customers who are likely to leave the service, enabling the company to take proactive measures to retain them.

## Table of Contents
- [Project Overview](#project-overview)
- [Data Collection](#data-collection )
- [Data Preprocessing](#data-preprocessing)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Machine Learning Model](#machine-learning-model)
- [Business Recommendations](#business-recommendations)
- [Conclusion](#conclusion)

## Project Overview
Introduction - 
   -  Customer churn is a significant issue in the telecom industry, where customers often switch providers due to better offers, dissatisfaction, or other factors. 
   -  This project uses historical customer data to build a machine learning model that predicts whether a customer will churn. 
   -  The insights from this model can help telecom companies improve customer retention strategies.

Objective - 
  - The primary objective is to understand the factors influencing customer churn and build machine learning models to predict churn. 
  - By doing so, the telecom company can proactively implement retention strategies, thereby reducing customer attrition and improving overall business performance.


## Data Collection 
Data collection in data science is the process of gathering data from various sources. It involves identifying sources, gathering data, and storing it in a structured format. 
  - Dataset: Customer Churn Prediction Dataset.
  - Content: Contains customer data for churn prediction.
  - Source: Sourced from a telecommunications company.
  - Purpose: Used for real-world customer churn analysis.

Dataset - Telecom Customer Churn Dataset

![image](https://github.com/user-attachments/assets/6e24beeb-247d-4e74-b1c6-8c340020de51)

## Data Preprocessing 
1) Handling Missing Values
    - Discuss strategies for addressing missing data, such as imputation or removal.
2) Dealing with Outliers
    - Identify and address outliers that can impact model performance.
3) Encoding Categorical Variables
    - Explain techniques to convert categorical data into a format suitable for machine learning models.
4) Splitting Data into Training and Testing Sets
    - Emphasize the importance of dividing data for model training and evaluation.

* Explored demographic information, contract details, and services used by customers.
* Investigated the distribution of gender, seniority, partner, and dependent status among customers.
* Analyzed customer tenure, contract types, and the distribution of services used.

Key Insights:

     1) The dataset includes a diverse customer base, with almost equal distribution between male and female customers.
     2) Senior citizens constitute around 16% of the customer base.
     3) Approximately 50% of customers have a partner, while only 30% have dependents.
     4) Most customers opt for month-to-month contracts, indicating flexibility in service usage.
     5) Customers with longer tenure tend to have two-year contracts.

## Exploratory Data Analysis (EDA) 
  - Investigated the relationship between churn and various variables such as tenure, contract type, and monthly charges.
  - Explored the impact of seniority on churn rates.
  - Analyzed the distribution of monthly and total charges concerning churn.

Key Findings:

    1) Customers with shorter tenure, month-to-month contracts, and higher monthly charges are more likely to churn.
    2) Senior citizens exhibit a higher churn rate compared to younger customers.
    3) Churn is inversely related to the total charges, indicating lower churn when total charges are higher.


## Machine Learning Model
1) Logistic Regression:   
  -  Type: Supervised learning algorithm used for classification tasks.
  -  Concept: It models the relationship between the dependent binary variable (target) and one or more independent variables by estimating probabilities using a logistic function. It's suitable for binary classification.
![image](https://github.com/user-attachments/assets/41408e9d-2fd8-4196-ab19-75066133c443)

2) Random Forest:
  - Type: Ensemble learning method, specifically a bagging algorithm.
  - Concept: It builds multiple decision trees and combines their predictions to produce a more accurate and robust result. Each tree in the forest is trained on a random subset of the data.
![image](https://github.com/user-attachments/assets/6283a02c-03de-4a90-ac24-47f71c4ce456)

3) Support Vector Machine (SVM):
  - Type: Supervised learning algorithm used for classification and regression tasks.
  - Concept: SVM finds a hyperplane that best separates data points of different classes. It aims to maximize the margin between the classes while allowing for a small number of misclassifications.
![image](https://github.com/user-attachments/assets/ab67fd0b-b9c7-4df2-938c-8c4e93bd888a)

4) Adaboost:
  - Type: Ensemble learning method, specifically a boosting algorithm.
  - Concept: Adaboost combines multiple weak classifiers to create a strong classifier. It assigns weights to data points, giving more importance to misclassified points, and iteratively improves the model.
![image](https://github.com/user-attachments/assets/cbd45e3b-c542-4f72-87ac-ee8e00b0ae98)

5) XG Boost (Extreme Gradient Boosting):
  - Type: Ensemble learning method, specifically a boosting algorithm.
  - Concept: XG Boost is an advanced gradient boosting algorithm known for its efficiency and performance. It builds decision trees sequentially, focusing on minimizing the loss function. It uses gradient descent for optimization.
![image](https://github.com/user-attachments/assets/8c70f0f2-87c4-4757-957c-e533391668db)

## Model Performance:
  - Logistic Regression: Accuracy - 80.76%
  - Random Forest: Accuracy - 80.88%
  - Support Vector Machine (SVM): Accuracy - 82.02%
  - ADA Boost: Accuracy - 81.59%
  - XG Boost: Accuracy - 80.60%

Interpretation - 
1) SVM achieved the highest accuracy, indicating its effectiveness in predicting customer churn.
2) Monthly contract, tenure, and total charges are identified as significant predictors of churn across multiple models.
3) The business should focus on retaining customers with shorter tenures, offering attractive contract terms, and managing monthly charges effectively.

## Business Recommendations
  - Implement targeted retention strategies for customers with shorter tenures, such as promotional offers or discounts on long-term contracts.
  - Enhance customer communication and satisfaction, especially for senior citizens who exhibit a higher churn rate.
  - Optimize pricing strategies to maintain competitive monthly charges while emphasizing the value of services.
  - Consider personalized promotions for loyal customers with longer tenures to encourage them to continue with the service.
  - Continuously monitor and analyze customer feedback to identify areas for improvement and address customer concerns proactively.

## Conclusion 

  - By leveraging data science and predictive modeling, the telecom company can gain valuable insights into customer churn patterns and implement strategies to enhance customer retention.
  - The combination of exploratory data analysis and machine learning provides a comprehensive understanding of customer behavior, empowering the business to make informed decisions and foster long-term customer relationships.





                                                                       Thank You For Visiting














