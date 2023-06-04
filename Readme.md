# Title
Lead Scoring using Logistic Regression

# Description
A company called X Education, which sells online courses, generates a large number of leads for its sales team with a significant marketing investment.

The goals of the analytics project are to
- build a model to assign a lead score to each of the leads (where a higher lead score indicates a more promising lead),
- identify the most promising leads, called 'Hot Leads', for the sales team, and
- develop solutions to some problems presented by the company.

The model will be used to provide more qualified leads to the sales team and improve the lead conversion rate.

# Approach to Analysis
Analysis is done as per the following steps:
- Data Understanding, Cleaning & Visualisation
- Data Preparation
- Model Building
- Model Evaluation
- Model Interpretation

# Results
The best logistic regression model resulting from the modelling process has 17 predictor variables and the following performance metrics

**Training Dataset**
- Accuracy = 0.82
- Sensitivity = 0.78
- Specificity = 0.84
- Precision = 0.76
- Recall = 0.78

**Test Dataset**
- Accuracy = 0.82
- Sensitivity = 0.77
- Specificity = 0.85
- Precision = 0.77
- Recall = 0.77

Assigning lead scores to all of the 9240 leads (data points) results in 3603 hot leads.