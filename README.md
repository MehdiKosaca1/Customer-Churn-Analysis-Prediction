# Customer Churn Analysis & Prediction
## Project Overview
This project focuses on predicting customer churn with an accuracy of 96%. The goal is to build a predictive model using various machine learning techniques, including logistic regression, decision trees, and random forests. The project leverages exploratory data analysis (EDA) for understanding the dataset, feature engineering for enhancing model performance, and simulation for validating results.

## About the Dataset
The bank customer churn dataset is a widely used dataset for predicting customer churn in the banking sector. It contains information about customers who have either left the bank or continue to be active members. The dataset includes the following attributes:

Customer ID: A unique identifier for each customer.

Surname: The customer's last name.

Credit Score: A numerical value representing the customer's credit score.

Geography: The country where the customer resides (France, Spain, or Germany).

Gender: The customer's gender (Male or Female).

Age: The customer's age.

Tenure: The number of years the customer has been with the bank.

Balance: The customer's account balance.

NumOfProducts: The number of bank products the customer uses (e.g., savings account, credit card).

HasCrCard: Whether the customer has a credit card (1 = yes, 0 = no).

IsActiveMember: Whether the customer is an active member (1 = yes, 0 = no).

EstimatedSalary: The estimated salary of the customer.

Exited: Whether the customer has churned (1 = yes, 0 = no).

This dataset is commonly used for classification tasks, where the goal is to predict whether a customer will churn based on the given attributes.

## 🚀 Project Workflow
### 1. Exploratory Data Analysis (EDA)
The first step in the project involved performing an in-depth exploratory data analysis (EDA) to understand the characteristics of the dataset. This phase helped in identifying important patterns, missing values, and the distribution of key variables. Visualizations such as histograms, box plots, and heatmaps were used to examine correlations and the spread of features.

### 2. Data Preprocessing
While no specific data cleaning was done, the EDA helped identify any outliers and potential issues with the dataset, allowing for better preparation of the data for modeling. Key steps in this phase include:

Handling missing values and duplicates

Scaling and normalizing numeric features

Encoding categorical variables

### 3. Feature Engineering
Feature engineering was a key aspect of the project. New features were created, and existing ones were transformed to improve model performance. Techniques such as one-hot encoding for categorical variables and scaling for continuous features were used.

### 4. Model Building
The project utilized multiple machine learning models for customer churn prediction:

Logistic Regression: A baseline model to understand the relationship between features and churn.

Decision Trees: A tree-based method to capture non-linear relationships.

Random Forests: An ensemble method that combines multiple decision trees to increase model accuracy.

Different models were compared based on performance metrics, such as accuracy, precision, recall, and F1 score.

### 5. Handling Overfitting with Correlation Analysis
Overfitting was addressed by performing correlation analysis to identify and remove highly correlated features. Features with high correlation were either selected or merged, reducing model complexity and improving generalization. This helped the model avoid overfitting and perform better on unseen data.

### 6. Simulation
Simulations were conducted to validate the model’s robustness and ensure that the results were consistent across various scenarios. This also helped in understanding how the model would perform under different conditions.

### 7. Model Evaluation
After training the models, the results were evaluated using several metrics to determine the best performing model. The random forest model achieved an impressive 96% accuracy, demonstrating its effectiveness in predicting customer churn.

### 8. Insights and Results
The final model provided valuable insights into the factors that most influence customer churn. Key insights included:

High correlation between customer service interactions and churn likelihood.

Significant impact of customer tenure on the likelihood of leaving.

Usage patterns in relation to churn risk.
## 💡 Conclusion
This project provides a solid foundation for customer churn prediction, with a well-performing model that can help businesses identify at-risk customers and take proactive measures. The use of machine learning models, EDA, feature engineering, and simulation ensures that the solution is both accurate and robust.
