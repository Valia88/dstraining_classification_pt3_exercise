# dstraining_classification_pt3_exercise
To predict a given Test dataset for the target classes as part of the Classification Part 3 module(competition). 


Exercise Project Description
The goal of this challenge is to recognize one user amongst all others. Keep in mind that data is highly inbalanced.

Evaluation metrics of this challenge is ROC AUC.


This dataset contains user transitions between pages. The goal of this challenge is to recognize one user amongst all others. The dataset consists of user sessions, each session is a sequence of transitions between pages. A sequence can be one to ten pages long.

train.csv - contains webpages, timestamps, and targets for each train session.
test.csv - contains webpages, timestamps for each test session.
id_map.parquet - webpages id to url map
