# Redwine: Using chemical analysis to determine the quality

## Objective

- The purpose of this case study is to learn the different techniques of machine learning through the dataset redwinequality
attribute Information

## The wine quality
 
Only life is too short to drink bad wine. I bring as a motto (and serves for coffee too). But how to evaluate the quality of a wine? Like or dislike is a personal matter, but quality is another story. Nowadays the quality of wine is determined by arbitrary notes from evaluators through the human senses. Based on the data and the chemical analyzes, how about we try this note any other way now?

## About the Dataset

Predict variables
- 1 - fixed acidity 
- 2 - volatile acidity 
- 3 - citric acid 
- 4 - residual sugar 
- 5 - chlorides 
- 6 - free sulfur dioxide 
- 7 - total sulfur dioxide 
- 8 - density 
- 9 - pH 
- 10 - sulphates 
- 11 - alcohol 

Output variable (based on sensory data): 
- 12 - quality (score between 0 and 10)

## Analysis and Prediction

- Data preprocessing and visualizing missing values

- Distribution check of the wine quality

![Alt Text](https://raw.githubusercontent.com/mp-rocha/data-projects/master/redwine-quality-predict/images/distribution.png)

- Correlation between predictors and between the predictors and target variables

![Alt Text](https://raw.githubusercontent.com/mp-rocha/data-projects/master/redwine-quality-predict/images/winequality.png)

- Building and training Classifier models

- Compare the results between differents types of models

![Alt Text](https://raw.githubusercontent.com/mp-rocha/data-projects/master/redwine-quality-predict/images/results.PNG)

## References:

P. Cortez, A. Cerdeira, F. Almeida, T. Matos and J. Reis. /n 
Modeling wine preferences by data mining from physicochemical properties. In Decision Support Systems, Elsevier, 47(4):547-553, 2009.
