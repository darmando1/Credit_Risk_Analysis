# Credit_Risk_Analysis

## Project Overview
Staff has been approached to help credit risks when providing loans to clients. Utilizing credit card data from LEndingClub, a peer-to-peer lending services company, staff will utlizing sampling tools and machine learning to predict potential credit risk.

## Results
  1. RandomOverSampler
    : ![Random Oversample](https://github.com/darmando1/Credit_Risk_Analysis/blob/main/Screenshots/RandomOverSampling.JPG)

  2. SMOTE Oversampling
    : ![SMOTE Oversampling](https://github.com/darmando1/Credit_Risk_Analysis/blob/main/Screenshots/SmoteOversampling.JPG)

  3. ClusterCentroids
    : ![ClusterCentroids](https://github.com/darmando1/Credit_Risk_Analysis/blob/main/Screenshots/ClusterCentroidsUndersample.JPG)

  4. SMOTEENN
    : ![SMOTEENN](https://github.com/darmando1/Credit_Risk_Analysis/blob/main/Screenshots/SMOTEENN.JPG)

  5. Balanced Random Forest Classifier
    : ![BRFC](https://github.com/darmando1/Credit_Risk_Analysis/blob/main/Screenshots/BRFC.JPG)

  6. Easy Ensemble AdaBoost Classifier
    : ![EEC](https://github.com/darmando1/Credit_Risk_Analysis/blob/main/Screenshots/EEC.JPG)

## Analysis of Results
All of the machine learning techniques captured above identify a low_risk precision score of 1. This means that if a loan was low-risk the machine accurrately predicted it. High risk precision is best for the Easy Ensemble AdaBoost Classifier. Finally, the balanced accuracy score is .9316 for the Easy Ensemble AdaBoost Classifier which also justifies utilizing this model as a good method for detecting risky loans.
