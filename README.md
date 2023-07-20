# HEALTH_INSURANCE_CROSS_SELL_PREDICTION-CLASSIFICATION-PROJECT
Our client is an Insurance company that has provided Health Insurance to its customers now they need your help in building a model to predict whether the policyholders (customers) from past year will also be interested in Vehicle Insurance provided by the company.
# **Summary**
The health insurance cross sell prediction dataset is a dataset that contains information about customers of an insurance company and whether they have purchased a particular insurance product. The goal is to build a predictive model that can accurately identify which customers are likely to purchase the product.
**In this project, we analyzed the dataset and performed exploratory data analysis to understand the patterns and relationships in the data. We then preprocessed the data and trained four different classification models:**
 **Logistic Regression, KNN, Random Forest, and XGBoost.**

Conclusion
1.Starting from loading our dataset, we initially checked for null values and duplicates. There were no null values and duplicates so treatment of such was not required.

Through Exploratory Data Analysis,

2.we observed that customers belonging to youngAge are more interested in vehicle response.while Young people below 30 are not interested in vehicle insurance.

3.We observed that customers having vehicles older than 2 years are more likely to be interested in vehicle insurance. Similarly, customers having damaged vehicles are more likely to be interested in vehicle insurance.

4.The variable such as Age, Previously_insured,Annual_premium are more afecting the target variable.

5.For Feature Selection, we applied the Mutual Information technique. Here we observed that Previously_Insured is the most important feature and has the highest impact on the dependent feature and there is no correlation between the two.

6.We observed that the target variable was highly imbalanced.So this issue was solved by using Random Over Sample resampling technique.

7.we applied feature scaling techniques to normalize our data to bring all features on the same scale and make it easier to process by ML algorithms.

8.Further, we applied Machine Learning Algorithms to determine whether a customer would be interested in Vehicle Insurance.

For the logistic regression we got an accuracy of 78% for the

KNN classifier we got an accuracy of 85% for

XGBClassifier we got the aacuracy of 81%.
