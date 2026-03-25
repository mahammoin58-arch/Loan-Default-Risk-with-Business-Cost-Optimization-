# Loan-Default-Risk-with-Business-Cost-Optimization-
Predict the likelihood of a loan default and optimize the decision threshold based on  cost-benefit analysis.  

# Task Objective

The main objective of this project is to predict the likelihood of a loan default and optimize decision-making using cost-benefit analysis.
The goal is to help financial institutions minimize losses by selecting an optimal probability threshold for approving or rejecting loan applications.

# My Approach
I followed a structured data science workflow:

1. Data Loading & Understanding

- Loaded dataset using pandas
- Explored features, structure, and data types

2. Data Preprocessing

- Handled missing values
- Encoded categorical variables
- Removed irrelevant features

3. Exploratory Data Analysis (EDA)

- Analyzed default vs non-default distribution
- Identified key risk factors
- Visualized relationships using Matplotlib & Seaborn

4. Feature Engineering

- Selected important features influencing default risk
- Prepared dataset for modeling

5. Model Building

- Logistic Regression
- Random Forest

6. Model Evaluation

- Accuracy
- Confusion Matrix
- Precision, Recall, F1-score
- ROC-AUC Score

7. Business Cost Optimization

- Defined cost of false positives and false negatives
- Adjusted probability threshold
- Selected optimal threshold to minimize total business cost
  
# Results and Findings
- Random Forest provided better predictive performance
- Key factors influencing default risk included income, credit history, and loan-related attributes
- Class imbalance was observed in the dataset
- Optimizing the decision threshold significantly reduced potential financial loss

# Conclusion

This project shows how machine learning combined with business logic can:

- Improve risk assessment
- Reduce financial losses
- Support smarter loan approval decisions
