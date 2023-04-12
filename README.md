# Credit_Risk_Analysis

## Overview

Using an understanding of Python and machine learning, Jill wants to be able to apply machine learning to credit card risk. Jill wants to use inbalanced-learn and scikit-learn libraries to build and evaluate models based on a credit card dataset from LendingClub, a peer-to-peer lending services company. Six different models were used to resample the data. The methods used were:

- RandomOverSampler: over-samples the data
- SMOTE: over-samples the data
- ClusterCentroids: under-samples the data
- SMOTEEN: uses a combinatorial approach of over and under sampling
- BalancedRandomForestClassifier: Compares two machine learning models to reduce bias
- EasyEnsembleClassifier: Compares two machine learning models to reduce bias

Each model is then evaluated for performance and a recommendation is made whether or not a particular model should be used to effectively predict credit card risk. 