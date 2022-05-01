# Credit_Risk_Analysis

## Analysis Overview
The purpose of this project was to predict creadit risk using the following machine learning models: RandomOverSampler, SMOTE, ClusterCentroids, SMOTEENN, BalancedRandomForestClassifier, and EasyEnsembleClassifier

## Results

### RandomOverSampler
- The balanced accuracy score is 66.1%
- High risk precision is about 1% with 72% recall
- Low risk precision is 100% with 60% recall

### SMOTE
- The balanced accuracy score is 65.8%
- High risk precision is about 1% with 62% recall
- Low risk precision is 100% with 69% recall

### ClusterCentroids
- The balanced accuracy score is 54.4%
- High risk precision is about 1% with 69% recall
- Low risk precision is 100% with 40% recall

### SMOTEENN
- The balanced accuracy score is 62.5%
- High risk precision is about 1% with 65% recall
- Low risk precision is 100% with 60% recall

### BalancedRandomForestClassifier
- The balanced accuracy score is 78.7%
- High risk precision is about 4% with 67% recall
- Low risk precision is 100% with 91% recall

### EasyEnsembleClassifier
- The balanced accuracy score is 92.5%
- High risk precision is about 7% with 91% recall
- Low risk precision is 100% with 94% recall

## Summary
All of the models had nearly perfect precision for low risk but very low precision for high risk, though the ensemble models did improve that. However, even the esemble models would classify many low risk applicants as high risk, causing them to not receive loans. Because of this, I would not recommend any of the models in their current form.