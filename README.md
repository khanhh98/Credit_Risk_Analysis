# Credit_Risk_Analysis
Supervised Machine Leanring and Credit Risk

## Overview of the analysis
The analysis focus on using various types of machine learning algorithms and models to predict credit risk of applicants. We will run provided dataset and its features through each model in order to find the most appropriate method and model.
The models used: 
  - Oversampling
  - Under sampling
  - SMOTE Oversampling
  - Combination of Oversampling % Under sampling
  - Balanced Random Forest Classifier
  - Easy Ensemble AdaBoost Classifier

## Results
### Naive Radom Oversampling
- Model accuracy score: ~66%
- Predicted High Risk Applicants: 1% precision with 69% recall
- Predicted Low Risk Applicants: 100% precision with 61% recall

<img width="1141" alt="Naive random oversampling" src="https://user-images.githubusercontent.com/63434761/169206114-6802b0a6-6726-4535-8f87-23c0a8ee3791.png">

### SMOTE oversampling model
- Model accuracy score: ~66%
- Predicted High Risk Applicants: 1% precision with 63% recall
- Predicted Low Risk Applicants: 100% precision with 69% recall

<img width="1143" alt="SMOTE Oversampling" src="https://user-images.githubusercontent.com/63434761/169208137-b99843e7-9ace-49f1-ba11-350eca0d8f13.png">

### Undersampling
- Model accuracy score: ~66%
- Predicted High Risk Applicants: 1% precision with 69% recall
- Predicted Low Risk Applicants: 100% precision with 40% recall

<img width="1176" alt="Undersampling" src="https://user-images.githubusercontent.com/63434761/169209780-306406a2-6959-4694-b3f0-a1791953b1e3.png">

### Combination
- Model accuracy score: ~54%
- Predicted High Risk Applicants: 1% precision with 72% recall
- Predicted Low Risk Applicants: 100% precision with 57% recall

<img width="1142" alt="combine" src="https://user-images.githubusercontent.com/63434761/169210598-63265ca8-97be-4a9b-a72f-6ce4c7ae78e5.png">

### Balanced Random Forest Classifier
- Model accuracy score: ~77%
- Predicted High Risk Applicants: 3% precision with 66% recall
- Predicted Low Risk Applicants: 100% precision with 88% recall

![Balanced random forest](https://user-images.githubusercontent.com/63434761/169210983-3e69a2fe-cc16-4a0f-a75a-0fc9430c3863.png)

### Easy Ensemble AdaBoost Classifier
- Model accuracy score: ~91%
- Predicted High Risk Applicants: 9% precision with 89% recall
- Predicted Low Risk Applicants: 100% precision with 94% recall

![Screen Shot 2022-05-18 at 9 57 11 PM](https://user-images.githubusercontent.com/63434761/169211164-791af82d-0776-4812-beef-501d034dd73a.png)

## Summary
- For all these models, I would recommend the easy ensemble classifiers since it has the highest accuracy score with acceptable balance of precision and recall scores
