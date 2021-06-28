# Credit_Risk_Analysis

Supervised Machine Learning and Credit Risk

## Overview of the Project

The project aims to use different techniques to train and evaluate models with unbalanced classes. Also, it is going to be used by the imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling. 

I will oversample the credit card credit dataset from LendingClub, a peer-to-peer lending services company, using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. The SMOTEENN algorithm will then be used in a combinatorial approach of over- and undersampling.

Then, to predict credit risk, I will compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier. When I'm finished, I'll assess the performance of these models and make a written recommendation on whether they should be used to predict credit risk.

## Results

The following table compares how different classifiers predict credit risk.

    - Oversampling_Naive Random Oversampling 

<p align="center"><img src="https://github.com/zkirsan/Credit_Risk_Analysis/blob/main/Resources/Oversampling_Imbalanced_Classification_Report.PNG"></img></p>

    - SMOTE
<p align="center"><img src="https://github.com/zkirsan/Credit_Risk_Analysis/blob/main/Resources/SMOTE_Imbalanced_Classification_Report.PNG"></img></p>

    - Cluster Centroid Undersampling

<p align="center"><img src="https://github.com/zkirsan/Credit_Risk_Analysis/blob/main/Resources/Cluster_Centroid_UnSampl_Imbalanced_Classification_Report.PNG"></img></p>

    - Combination (Over and Under) Sampling

<p align="center"><img src="https://github.com/zkirsan/Credit_Risk_Analysis/blob/main/Resources/SMOTEEN_Imbalanced_Classification_Report.PNG"></img></p>

    - Balanced Random Forest Classifier

<p align="center"><img src="https://github.com/zkirsan/Credit_Risk_Analysis/blob/main/Resources/BalancedRandomForest_Imbalanced_Classification_Report.PNG"></img></p>

    - Easy Ensemble AdaBoost Classifier

<p align="center"><img src="https://github.com/zkirsan/Credit_Risk_Analysis/blob/main/Resources/EasyEnsemble_Adaboost_Imbalanced_Classification_Report.PNG"></img></p>

## Summary

Summary:

The Easy Ensemble Classifier is clearly the most efficient model, with the highest accuracy precision, recall, and f1-score Even so, we should be extremely cautious about the 9 percent precision that it provides for High Risk Loans in the Easy Ensemble Adaboost Classifier. In addition to that, as you see above on the tables after using SMOTEEN with two different classifiers, it is clear that some accuracy, recall and precision have improved. 
