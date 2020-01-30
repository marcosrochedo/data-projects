# Heart Disease: Predict heart disease with medical data

## Objective

- The purpose of this case study is predict whether the patient will have heart disease using medical data

## Dataset information
 
This database contains 76 attributes, but all published experiments refer to using a subset of 14 of them. In particular, the Cleveland database is the only one that has been used by ML researchers to
this date. The "goal" field refers to the presence of heart disease in the patient. It is integer valued from 0 (no presence) to 4. Experiments with the Cleveland database have concentrated on simply attempting to distinguish presence (values 1,2,3,4) from absence (value 0). The names and social security numbers of the patients were recently removed from the database, replaced with dummy values.


## About the Dataset

Predict variables
- 1 - Age
- 2 - Sex
- 3 - Cp 
- 4 - Trestbps 
- 5 - Fbs 
- 6 - Restecg
- 7 - Thalach 
- 8 - Exang 
- 9 - Oldpeak
- 10 - Slope 
- 11 - Ca 
- 12 - Thal 

Output variable): 
- 13 - Target (0 and 1)

## A little about this analysis...

- Data preprocessing and visualizing missing values

- Exploratory data analysis

![Alt Text](https://raw.githubusercontent.com/mp-rocha/data-projects/master/heart-disease-predict/heart-disease-predict/images/menxwomen.png)

- Compare the results between differents types of models

![Alt Text](https://raw.githubusercontent.com/mp-rocha/data-projects/master/heart-disease-predict/heart-disease-predict/images/results.PNG)

- Neural Network accuracy: 85%

![Alt Text](https://raw.githubusercontent.com/mp-rocha/data-projects/master/heart-disease-predict/heart-disease-predict/images/nnetwork.PNG)

- Machine Learning Explainability

![Alt Text](https://raw.githubusercontent.com/mp-rocha/data-projects/master/heart-disease-predict/heart-disease-predict/images/shapvalues.PNG)

## References:

1. Hungarian Institute of Cardiology. Budapest: Andras Janosi, M.D.
2. University Hospital, Zurich, Switzerland: William Steinbrunn, M.D.
3. University Hospital, Basel, Switzerland: Matthias Pfisterer, M.D.
4. V.A. Medical Center, Long Beach and Cleveland Clinic Foundation: Robert Detrano, M.D., Ph.D.
