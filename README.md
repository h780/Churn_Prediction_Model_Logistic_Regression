# Churn_Prediction_Model_Logistic_Regression

In this project I perform Logistic Regression to develop a Churn Prediction Model on streaming data.

Business Objective: Predicting a qualitative response for observation can be referred to as classifying that observation since it involves assigning the observation to a category or class. Logistic Regression is built on the foundation of classification. It is a supervised learning algorithm used to predict categorical or discrete dependent variables. The sigmoid function is used in logistic regression to model the data.

Customers that have decided to quit their engagement with their current company are known as churned customers. I decided to work with a churn dataset for this case study.

XYZ is a service provider that offers a one-year subscription plan for their product to customers. The corporation is curious as to whether or not customers would renew their subscriptions for the next year.

Data Description: This data provides information about a video streaming service company, where they want to predict if the customer will churn or not. The CSV consists of around 2000 rows and 16 columns.

Tech Stack: 
Language - Python
Libraries - numpy, pandas, matplotlib, seaborn, sklearn, pickle, imblearn, statsmodel

Approach:

1. Importing the required libraries and reading the dataset.
2. Inspecting and cleaning up the data
3. Perform data encoding on categorical variables
4. Exploratory Data Analysis (EDA)
   -> Data Visualization
5. Feature Engineering
   -> Dropping of unwanted columns
6. Model Building
   -> Using the statsmodel library
7. Model Building
   -> Performing train test split
   -> Logistic Regression Model
8. Model Validation (predictions)
   -> Accuracy score
   -> Confusion matrix
   -> ROC and AUC
   -> Recall score
   -> Precision score
   -> F1-score
9. Handling the unbalanced data
   -> With balanced weights
   -> Random weights
   -> Adjusting imbalanced data
   -> Using SMOTE
10. Feature Selection
   -> Barrier threshold selection
   -> RFE method
11. Save the model in the form of a pickle file.



 
