# Heart Disease Detection: Capstone Project

This capstone project aims to develop a machine learning model to predict heart disease using a dataset containing various cardiovascular health metrics. The project will involve data preprocessing, exploratory data analysis, feature engineering, model training, evaluation, and visualization.

Dataset link: https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction

## Attribute information
- Age: age of the patient [years]
- Sex: sex of the patient [M: Male, F: Female]
- ChestPainType: chest pain type [TA: Typical Angina, ATA: Atypical Angina, NAP: Non-Anginal Pain, ASY: Asymptomatic]
- RestingBP: resting blood pressure [mm Hg]
- Cholesterol: serum cholesterol [mm/dl]
- FastingBS: fasting blood sugar [1: if FastingBS > 120 mg/dl, 0: otherwise]
- RestingECG: resting electrocardiogram results [Normal: Normal, ST: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV), LVH: showing probable or definite left ventricular hypertrophy by Estes' criteria]
- MaxHR: maximum heart rate achieved [Numeric value between 60 and 202]
- ExerciseAngina: exercise-induced angina [Y: Yes, N: No]
- Oldpeak: oldpeak = ST [Numeric value measured in depression]
- ST_Slope: the slope of the peak exercise ST segment [Up: upsloping, Flat: flat, Down: downsloping]
- HeartDisease: output class [1: heart disease, 0: Normal]

## Sections

### Data preparation
The data is preliminary split to training and test datasets to perform evaluations only on training dataset to not make subjective conclusions.

### EDA
The exploratory data analysis includes:
- Per column analysis
- Heart diseases column analysis
- Cross-column analysis

The per column analysis also includes data relation to gender and age with conclusions and suggestions done during analysis.

### Model selection, evaluations and training
The models selected for dataset processing:
- Logistic Regression
- Gradient Boosting
- KNeighbors Classifier
- Decision Tree Classifier
- AdaBoost Classifier
- Random Forest
- XGBoost Classifier
- Support Vector Machine
- Naive Bayes Classifier
- Extra Trees Classifier
- LightGBM Classifier
- CatBoost Classifier
- Bagging Classifier
- Neural Network (MLP)
- SGD Classifier
- Voting Classifier that consists of
  - Logistic Regression
  - Random Forest
  - Support Vector Machine

The model analysis includes hyperparameters grid search, training datasets with different preprocessing, extensive hyperparameters grid search for promising candidates and final candidate evaluation and testing.  