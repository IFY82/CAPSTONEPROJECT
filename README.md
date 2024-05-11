# CAPSTONEPROJECT
This shows the churn prediction analysis carried out for ConnectTel Telecomm Company in order to help them with the reduce customer attrition, enhance customer loyalty, and maintain a competitive edge in the highly dynamic and competitive telecommunications industry.


# Title: Analysis of Churn Prediction for ConnectTel Telecom Company

## Introduction:

### Problem Overview
The business problem outlined in the overview for ConnectTel Telecom Company is customer churn. Customer churn, or the rate at which customers stop doing business with a company, is identified as a significant threat to the company's sustainability and growth. The current customer retention strategies are deemed ineffective, leading to the loss of valuable customers to competitors.

### Brief overview of the analysis objective.
To address this challenge, ConnectTel aims to develop a robust customer churn prediction system. As a Data Scientist, you've been contacted to assist in this endeavor. The company intends to leverage advanced analytics and machine learning techniques on available customer data to accurately forecast customer churn. The goal is to implement targeted retention initiatives based on these predictions.

### Description of the dataset used for analysis.
The dataset used for this project was provided by 10Alytics. The dataset contains a collection of features extracted from ConnectTel Telecomms about their customers, including gender of customer, how many lines the customer has, if the customer has dependents or not, whether the customer is a senior citizen or not, and other relevant information.

## Exploratory Data Analysis (EDA):
A properly conducted EDA empowers ConnectTel Telecom Company with actionable insights and strategic advantages that can significantly improve customer retention efforts and business performance.

### Summary of key findings from EDA, including:

#### Distribution of target variable ('Churn').
This involved analyzing churn rates over time, identifying seasonal variations, and detecting any underlying patterns in customer behavior leading to churn.

#### Visualizations of relationships between 'Churn' and key features.
This involved examining the distribution of various variables such as gender, partner, dependents, and service subscriptions among churners and non-churners

#### Correlation analysis between 'Churn' and numerical/categorical features.
This was used to visualize relationships between the churn label and key features, explore correlations between variables, and conduct univariate, bivariate, and multivariate analysis.

## Feature Engineering:

### Description of any feature engineering techniques applied to the dataset.
To perform feature engineering on the ConnectTel Telecom Company dataset, we encoded categorical variables and created new features where necessary based on insights from our EDA.

### Explanation of new features created or transformations performed.
A new feature 'HasPhoneAndInternet' was created to indicate if a customer has both phone and internet service
A new feature 'HasStreamingServices' was created to indicate if a customer has either streaming TV or streaming movies service
A new feature 'FamilySize' was created to indicate the size of the customer's family (including themselves)
A new feature TotalServices was created to indicate total count of all additional services subscribed to by the customer
A new feature 'SeniorCitizenStatus' was created to indicate if a customer is a senior citizen or not

## Modeling:
The dataset was split into features (X) and the target variable (y).
The data was split into training and testing sets using the train_test_split function.
3 supervised learning models were used: Logistic Regression, Random Forest, and Support Vector Machine (SVM).
Finally, he results were compared to select the best-performing model(s) for further analysis or deployment.


## Model Evaluation:

### Analysis of model performance using appropriate metrics.
Accuracy: This metric was used indicate the overall correctness of the predictions. 
Precision: Precision measured the proportion of true positive predictions among all positive predictions made by the model. 
Recall: Recall, also known as sensitivity or true positive rate, was used measured the proportion of true positives that are correctly identified by the model. 
F1-score: F1-score is the harmonic mean of precision and recall. It provided a balance between precision and recall. 
Classification Report: The classification report provided a summary of precision, recall, F1-score, and support (the number of actual occurrences of each class). 

### Discussion on the importance of specific metrics for the business problem.
- Logistic Regression seemed to be the most balanced model in terms of accuracy, precision, recall, and F1-score. It provided a reasonable trade-off between correctly predicting both churn and non-churn cases.

## Conclusion:

### Summary of key insights gained from the analysis.
- The purpose of this project is to predict churn in ConnectTel.
- Logistic Regression seems to be the most balanced model in terms of accuracy, precision, recall, and F1-score

### Recommendations for improving churn prediction and customer retention strategies.

- Based on the churn prediction analysis, here are some recommendations for improving churn prediction and customer retention strategies
* Enhance Customer Engagement. Implement proactive communication strategies to engage with customers regularly. 
* Improve Service Quality: Identify areas for improvement in service quality based on customer feedback and complaints.
* Optimize Pricing Strategies: Evaluate pricing plans and packages to ensure competitiveness in the market while maintaining profitability.
* Strengthen Customer Support: Invest in robust customer support systems to provide timely assistance and resolution to customer queries and issues.
* Promote Long-Term Contracts: Encourage customers to sign up for long-term contracts by offering incentives or discounts for committing to extended service agreements.
* Upsell and Cross-Sell Opportunities: Identify upsell and cross-sell opportunities based on customer usage patterns and preferences.
* Foster Customer Loyalty Programs: Develop customer loyalty programs that reward long-term customers for their continued patronage.


















