# Unit 11—Risky Business

![Credit Risk](Images/credit-risk.jpg)

## Background

Auto loans, mortgages, student loans, debt consolidation ... these are just a few examples of credit and loans that people are seeking online. Peer-to-peer lending services such as LendingClub or Prosper allow investors to loan other people money without the use of a bank. However, investors always want to mitigate risk, so you have been asked by a client to help them use machine learning techniques to predict credit risk.

In this assignment, you will build and evaluate several machine-learning models to predict credit risk using free data from LendingClub. Credit risk is an inherently imbalanced classification problem (the number of good loans is much larger than the number of at-risk loans), so you will need to employ different techniques for training and evaluating models with imbalanced classes. You will use the imbalanced-learn and Scikit-learn libraries to build and evaluate models using the two following techniques:

1. [Resampling](#Resampling)
2. [Ensemble Learning](#Ensemble-Learning)

---

### Files

[Resampling Starter Notebook](Starter_Code/credit_risk_resampling.ipynb)

[Ensemble Starter Notebook](Starter_Code/credit_risk_ensemble.ipynb)

[Lending Club Loans Data](Instructions/Resources/LoanStats_2019Q1.csv.zip)

---

## Instructions


### 1. Resampling

Use the above referenced Resampling Stater Notebook to answer the following:

> Which model had the best balanced accuracy score?
* The RandomOverSampler model predicts the highest balanced accuracy score. This model gives us the highest probability of correct calls or correct predictions for credit risk.
> Which model had the best recall score?
* The RandomOverSampler model has the best Recall score. This model will give us the highest actual positive samples that are correct.
> Which model had the best geometric mean score?
* 

### 2. Ensemble Learning

Use the above referenced Ensemble Starter Notebook to answer the following:

> Which model had the best balanced accuracy score?
* This model gives us the highest probability of correct calls or correct predictions for credit risk.
> Which model had the best recall score?
* This model will give us the highest actual positive samples that are correct.
> Which model had the best geometric mean score?
*
> What are the top three features?
*

---

### Hints and Considerations

For the ensemble learners, use 100 estimators for both models.

---

