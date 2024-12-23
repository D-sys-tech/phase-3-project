Customer Churn Prediction for SyriaTel: A Machine Learning Approach to Enhance Retention Strategies.

## Business understanding
Customer churn is a major challenge for companies in the telecommunications industry, including SyriaTel. The objective is to develop a predictive model that can determine whether a customer is likely to terminate their services. This binary classification task focuses on identifying patterns in customer behavior and demographic data that may signal a risk of churn. The ultimate goal is to help SyriaTel mitigate the financial impact of churn by enabling proactive retention strategies.

## Problem statement
SyriaTel is confronted with the challenge of retaining customers in a highly competitive telecommunications market. Customer churn results in revenue loss and negatively impacts the company’s reputation and market position. The goal is to create a predictive model that can accurately identify customers at risk of churning, allowing SyriaTel to take proactive steps with targeted retention strategies.
## Objectives
The goal is to develop the most effective model for predicting customer churn at SyriaTel, with the aim of minimizing the financial impact of churn through the implementation of targeted retention strategies.
## Data source
The data is sourced from https://www.kaggle.com/datasets/becksddf/churn-in-telecoms-dataset
## Data understanding
Obtain a dataset from Kaggle consisting of 21 columns and 3333 rows, containing relevant information for predicting customer churn. Each row represents a customer, and each column represents features related to customer behavior, demographics, and interactions with SyriaTel's services.
The columns are as follows: 
- **state:** the state the user lives in
- **account length:** the number of days the user has this account
- **area code:** the code of the area the user lives in
- **phone number:** the phone number of the user
- **international plan:** true if the user has the international plan, otherwise false
- **voice mail plan:** true if the user has the voice mail plan, otherwise false
- **number vmail messages:** the number of voice mail messages the user has sent
- **total day minutes:** total number of minutes the user has been in calls during the day
- **total day calls:** total number of calls the user has done during the day
- **total day charge:** total amount of money the user was charged by the Telecom company for calls during the day
- **total eve minutes:** total number of minutes the user has been in calls during the evening
- **total eve calls:** total number of calls the user has done during the evening
- **total eve charge:** total amount of money the user was charged by the Telecom company for calls during the evening
- **total night minutes:** total number of minutes the user has been in calls during the night
- **total night calls:** total number of calls the user has done during the night
- **total night charge:** total amount of money the user was charged by the Telecom company for calls during the night
- **total intl minutes:** total number of minutes the user has been in international calls
- **total intl calls:** total number of international calls the user has done
- **total intl charge:** total amount of money the user was charged by the Telecom company for international calls
- **customer service calls:** number of customer service calls the user has done
- **churn:** true if the user terminated the contract, otherwise false

## Data Preparation:
Clean the dataset by handling missing values, encoding categorical variables, and scaling numerical features. Perform exploratory data analysis to understand the distribution of features and identify potential correlations with customer churn.
## Logistic regression model
The performance metrics for your Logistic Regression model indicate excellent predictive performance:
Accuracy (96.67%): This high accuracy suggests the model correctly predicts churn and non-churn cases most of the time.
Precision (97.00%): A precision score of 97% indicates that when the model predicts a customer will churn, it is correct 97% of the time.
Recall (96.67%): This score implies that the model correctly identifies 96.67% of the actual churn cases, showing it is effective in minimizing false negatives.
F1-score (96.68%): The F1-score balances precision and recall, confirming that the model achieves a strong trade-off between these metrics.AUC (1.0): The perfect Area Under the Curve (AUC) score suggests the model is excellent at distinguishing between churn and non-churn customers.
## Decision tree
Precision (97.00%):The model is highly precise, meaning it correctly identifies 97% of the customers it predicts will churn. 
Recall (96.67%):The model successfully captures 96.67% of the actual churn cases, ensuring most at-risk customers are flagged for retention efforts. High recall is critical for minimizing the number of customers who churn undetected.
Accuracy (96.67%):The model's overall performance is strong, with nearly 97% of predictions being correct. This reflects a well-balanced model that performs effectively.
##Accuracy (100%):The model correctly predicted all instances, achieving perfect accuracy.
Precision (100%):Every customer flagged as likely to churn was indeed a churner, with no false positives.
Recall (100%):The model captured all actual churners, leaving no false negatives.
F1-score (100%):A perfect balance between precision and recall, indicating exceptional predictive performance.
ROC AUC Score (100%):The model perfectly distinguishes between churners and non-churners, showcasing outstanding reparability.
## Random forest
Accuracy (100%):The model correctly predicted all instances, achieving perfect accuracy.
Precision (100%):Every customer flagged as likely to churn was indeed a churner, with no false positives.
Recall (100%):The model captured all actual churners, leaving no false negatives.
F1-score (100%):A perfect balance between precision and recall, indicating exceptional predictive performance.
ROC AUC Score (100%):The model perfectly distinguishes between churners and non-churners, showcasing outstanding reparability.
## Conclusion
From the above models, random forest model is performing better than the logistics and decision tree model.

## recommendations
1.Introduce loyalty programs that reward long-term customers with benefits such as free upgrades, exclusive services, or special discounts.

2.Customers with frequent customer service calls may indicate unresolved issues. Streamline complaint resolution processes to address their concerns promptly.

3.Design personalized offers such as discounts, loyalty rewards, or improved service plans to retain these customers