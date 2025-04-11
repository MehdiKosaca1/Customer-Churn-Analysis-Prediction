# Customer Churn Analysis & Prediction
## Project Overview
This project focuses on predicting customer churn with an accuracy of 96%. The goal is to build a predictive model using various machine learning techniques, including logistic regression, decision trees, and random forests. The project leverages exploratory data analysis (EDA) for understanding the dataset, feature engineering for enhancing model performance, and simulation for validating results.
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

### 5. Handling Overfitting
To address overfitting, several strategies were implemented:

Cross-Validation: K-fold cross-validation was used to assess the model’s performance on multiple splits of the dataset.

Regularization: Techniques like L1 and L2 regularization were applied to reduce the complexity of the model and improve generalization.

### 6. Simulation
Simulations were conducted to validate the model’s robustness and ensure that the results were consistent across various scenarios. This also helped in understanding how the model would perform under different conditions.

### 7. Model Evaluation
After training the models, the results were evaluated using several metrics to determine the best performing model. The random forest model achieved an impressive 96% accuracy, demonstrating its effectiveness in predicting customer churn.

### 8. Insights and Results
The final model provided valuable insights into the factors that most influence customer churn. Key insights included:

High correlation between customer service interactions and churn likelihood.

Significant impact of customer tenure on the likelihood of leaving.

Usage patterns in relation to churn risk.
