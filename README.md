# Credit_Risk_Analysis

Overview of the analysis:
The purpose of the assignment is to apply our knowledge of the imbalanced-learn and scikit-learn libraries to evaluate three different machine learning models by using resampling to determine which of the model would be better at predicting credit risk. First, we are instructed to use oversampling RandomOverSampler and SMOTE algorithms and CLusterCentroids algorithm to resample the dataset. Then, to predict credit risk, we were instructed to use the two additional models, BalancedRandomForestClassifier and EasyEnsembleClassifier. Finally, the data were evaluated to classify the credit risk for individuals as "high risk" or "low risk."

Results:
Below are the results of six different machine learning models used to analyze the data.  The balanced accuracy score, the accuracy scores the recall score of each sample is well evaluated to support the result.

 1.                  pre       rec       spe        f1       geo       iba       sup

  high_risk       0.01      0.53      0.54      0.01      0.53      0.28       104
   low_risk       0.99      0.54      0.53      0.70      0.53      0.28     17101

avg / total       0.99      0.54      0.53      0.69      0.53      0.28     17205

 2.                 pre       rec       spe        f1       geo       iba       sup

  high_risk       0.01      0.54      0.74      0.02      0.63      0.39       104
   low_risk       1.00      0.74      0.54      0.85      0.63      0.41     17101

avg / total       0.99      0.74      0.54      0.84      0.63      0.41     17205

  3.                pre       rec       spe        f1       geo       iba       sup

  high_risk       0.01      0.44      0.70      0.02      0.56      0.30       104
   low_risk       1.00      0.70      0.44      0.83      0.56      0.32     17101

avg / total       0.99      0.70      0.44      0.82      0.56      0.32     17205


4.
                  pre       rec       spe        f1       geo       iba       sup

  high_risk       0.01      0.70      0.60      0.02      0.65      0.42       104
   low_risk       1.00      0.60      0.70      0.75      0.65      0.41     17101

avg / total       0.99      0.60      0.70      0.74      0.65      0.41     17205


5.
                   pre       rec       spe        f1       geo       iba       sup

  high_risk       0.03      0.70      0.87      0.06      0.78      0.60       101
   low_risk       1.00      0.87      0.70      0.93      0.78      0.62     17104

avg / total       0.99      0.87      0.70      0.93      0.78      0.62     17205

 

  6.               pre       rec       spe        f1       geo       iba       sup

  high_risk       0.09      0.92      0.94      0.16      0.93      0.87       101
   low_risk       1.00      0.94      0.92      0.97      0.93      0.87     17104

avg / total       0.99      0.94      0.92      0.97      0.93      0.87     17205
                
Summary:
Among the six machine learning models evaluated, the Easy Ensemble AdaBoost Classifier appear to the most accurate model. The Easy Ensemble AdaBoost classifier proved: balanced accuracy score = 0.93, the mean accuracy score = 0.99, the mean recall score = 0.94.  The Easy Ensemble AdaBoost Classified seems accurate more the other models. The disadvantage of using these models is that the accuracy scores of the high_risk prediction are significantly lower than the accuracy scores of the low_risk prediction which could potentially cause errors in the overall accuracy of the credit card risk assessment.

