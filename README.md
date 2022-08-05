# Credit_Risk_Analysis
## Project Overview
Using various libraries and algoriths as well as variety different techniques to train and evaluate models with unbalanaced classes. Techniques include imbalanced-learn, scikit-learn, RandomOversampler, SMOTE algorithms, ClusterCentroids algorithm, SMOTEEN algorithm, BalancedRandomForestClassifier and EasyEnsembleClassifier.
Goal of this project was to explain how a machine learning algorithm is using in data analytics by creating training and testing groups from a given dataset, implementing logistic regression, decision tree, random forest and support vector machine algorithms. Comparing the advantages & disadvantages of each technique, we can determing which approach is best for given dataset or situation.
## Results
Balanced Accuracy scores and Precision/recall scores for each model are listed below:
### Naive Random Oversampling
* Balanced Accuracy: 0.6361855437510828
* Precision: The precision is low for High-risk loans and is high for Low-risk loans.
* Recall: High/Low risk = .66/.67

### SMOTE Oversampling
* Balanced Accuracy: 0.6289276059481651
* Precision: The precision is low for High-risk loans and is high for Low-risk loans.
* Recall: High/Low risk = .62/.64

### Undersampling
* Balanced Accuracy:0.6289276059481651
* Precision: The precision is low for High-risk loans and is high for Low-risk loans.
* Recall: High/Low risk = .59/.43

### Combination Under-Over Sampling
* Balanced Accuracy: 0.5104477642006195
* Precision: The precision is low for High-risk loans and is high for Low-risk loans.
* Recall: High/Low risk = .70/.57

### Balanced Random Foret Classifier
* Balanced Accuracy: 0.7877672625306695
* Precision: The precision is low for High-risk loans and is high for Low-risk loans.
* Recall: High/Low risk = .67/.91

### Easy Ensemble Ada Boost Classifier
* Balanced Accuracy: 0.925427358175101
* Precision: The precision is low for High-risk loans and is high for Low-risk loans.
* Recall: High/Low risk = .91/.94

## Summary
To determine the best machine learning model, we must identify which  model has the highest compared accuracy between 0 and 1. For this data set, the Easy Ensemble AdaBoost Classifier producuced the highest accuracy score of .93 balanced accuracy. This score was nearly 15 points higher than every other model. The precision scores for all models were similar and within an appropriate range. Finally, the recall score needs to fall between 0 and 1 with the highest score being most optimal. To conclude, the Easy Ensemble AdaBoost Classifier is the overall best machine learning model to chose from as both the balanced accuracy and recall scores were the highest among all models.
