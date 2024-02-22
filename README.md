# MachineLearning_Project
Predictive modelling of both binary and multiclass classification, using the "Sklearn" library, can predict if a patient will be readmitted to the hospital within 30 days of being discharged and the timeframe of a patient’s
readmission, with the classes being “No”, “<30 days”, “>30 days”.

# Authors 
**Diogo Reis**

**João Machado**

**David Guarin**

**Diogo Almeida**

**Flávio Ivo**

# Abstract 
If hospitals and healthcare centres, could predict correctly the readmissions of patients it would change 
drastically the healthcare system as we know it, as this could give enough time to the hospital to 
prevent many kinds of emergencies before they happen. In other words, the impact of good 
predictions could lead the healthcare system to be well-prepared in different domains such as: 
professional scalings, resources quantity, appointment planning and others. To address this problem, 
and facing the issue of an imbalanced dataset we performed various data preprocessing and feature 
selection techniques to have the best dataset possible to develop Machine-Learning models to 
evaluate two different classification problems: binary and multiclass. In binary, the goal is to predict if 
a patient will be readmitted within 30 days before being discharged, this is the same in multiclass, 
though in this case we also check if the individual will be readmitted after 30 days, capturing the 
timeframe of patient’s readmissions. Finally, our results reveal that our best model is Stacking, which 
uses Naive Bayes and Gradient Boosting with a meta-model of Gradient Boosting, with an F1 score of 
0.287 for our binary target, and for our multiclass target the best model is Gradient Boosting with a 
0.552 F1 score. In conclusion, to get a better outcome would be necessary a dataset with more 
consistent information and a more balanced target variable. Using oversampling could improve the 
score, but it needs a high computational cost

# Introduction
In the healthcare sector, it’s crucial that we know of the patient's readmissions done within a certain period of time after 
their discharge. Machine Learning is a great tool to address this problem because it can help to identify potential problems 
and holes in the industry and provide the best solutions based on the different metrics and outputs given by the many 
models applied to the data. This is done mainly by predicting the patient readmissions so that patient care and substantial 
cost savings can be improved.
To achieve this task, we did multiple steps so that we could get to the best possible conclusion, given the data, of trying 
to predict the readmissions, both on a binary problem, between the patients being readmitted or not and even a 
multiclass scenario where we have more data regarding the exact timeframe where that same patient was readmitted. 
With that in mind, we developed this work from the beginning by checking the data and correcting its inconsistencies, to 
transforming variables, dealing with outliers, scaling, encoding and applying multiple steps of feature engineering, to 
finally developing multiple different models, both individual and ensembles, such as Logistic Regression, Naive Bayes, 
KNN, MLP’s, Decision Trees, Random Forests, Bagging Classifiers, Boosting’s, Stacking´s and even a Voting Classifier.
This project aims to address these points in detail, backed up by the outputs of the code done, while explaining the full 
thought process that we had during the development of this work, describing and referencing all this using the main 
documentations from sklearn libraries, while at the end concluding a solution for both future studies and possible improvements to the work done here
