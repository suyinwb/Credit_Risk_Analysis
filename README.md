# Credit Risk Analysis

## Background

Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, you’ll need to employ different techniques to train and evaluate models with unbalanced classes. Jill asks you to use imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling.

## Overview of Project

### Purpose

Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, you’ll oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. Then, you’ll use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Next, you’ll compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. Once you’re done, you’ll evaluate the performance of these models and make a written recommendation on whether they should be used to predict credit risk.

## Analysis And Challenges

## Methodology: Analytics Paradigm

#### 1. Decomposing the Ask

* Deliverable 1: Use Resampling Models to Predict Credit Risk
* Deliverable 2: Use the SMOTEENN Algorithm to Predict Credit Risk
* Deliverable 3: Use Ensemble Classifiers to Predict Credit Risk

#### 2. Identify the Datasource
* LoanStats_2019Q1.csv for 68817 records. Dataset is imbalanced with 68470 low risk and 347 high risk.

### 3. Define Strategy & Metrics
**Resource:** Python, numpy, pandas, pathlib, collections, sklearn, imblearn

#### 4. Data Retrieval Plan
NA

#### 5. Assemble & Clean the Data
Null values dropped and columns name changed so Data Scientist can understand the values better. 

#### 6. Analyse for Trends

The analysis is indicated below in [Analysis](#analysis)

#### 7. Acknowledging Limitations
Need more knowledge on statistics.

#### 8. Making the Call:
The "Proper" Conclusion is indicated below in [Summary](#summary)

## Analysis



>Paid  Total Reviews

![paid](resources/paid_total.png)

There is a total of _**1207 of paid reviews**_ that have received 20 or more helpful votes and those helpful votes are 50% or more than total votes.

## Summary

## Appendix

### References
