# Predicting Default Risk

## Introduction
You are a loan officer at a bank that needs to come up with an efficient solution to classify new customers on whether they can be approved for a loan or not.

## Business and Data Understanding
A decision must be made on whether or not each of the 500 new loan applications can be approved. As a result, two main datasets must be gathered. The first must contain attributes that influence creditworthiness on all past applicants and the second must contain those same attributes for the new applicants. To determine the creditworthiness of each applicant from this data, binary classification models should be used, specifically logit regression, decision tree, random forest, and boosted models.

## Conclusions
The relative importance of accurately predicting creditworthy and non-creditworthy applicants should be inquired from the bank to determine whether the model should be weighted toward creditworthy or non-creditworthy applicants. Assuming these predictions are of equal importance, the Random Forest Model was used because it is the most accurate model with an accuracy of 83%. The ROC Curve further cements this choice, because the area under the Random Forest Model Curve is the largest at 0.9998. Though the Random Forest Model is the most accurate, the model is biased toward non-creditworthy applicants with an accuracy of 85% (412 applicants not approved) and away from creditworthy applicants with an accuracy of 72% (88 applicants approved).