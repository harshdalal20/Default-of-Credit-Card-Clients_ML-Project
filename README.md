Project Overview
Credit card defaults are a significant concern for both financial institutions and consumers. This analysis uses customer payment data to build predictive models that classify the likelihood of default. By leveraging Machine Learning without any Libraries like Sckit learn or Sklear used, we aim to provide actionable insights to mitigate credit risks.

Dataset Details
Number of Instances: 30,000
Number of Attributes: 24
Characteristics: Multivariate, containing both integer and real-valued features
Key Features:
Demographics: Gender, education, marital status, and age
Credit History: Past payment status (April–September 2005)
Financial Data: Bill amounts and payments made (April–September 2005)
Target Variable: Default payment (1 = Default, 0 = No Default)


Project Objectives
Preprocessing:
Clean and transform the dataset
Perform univariate and multivariate analysis to explore feature relationships

Modeling:
Split data into training (70%) and testing (30%) sets
Experiment with machine learning models:
Naïve Bayes Classification
Decision Trees (e.g., Random Forest)

Evaluation:
Assess model performance using metrics such as accuracy, precision, recall, and F1-score
Adjust models for optimal performance

Probabilistic Insights:
Estimate the likelihood of a customer's default payment

Results:
Logistic Regression gives the best result with accuracy of 0.74

