# Credit_Risk_Analysis

### Overview of the Analysis
The purpose of this analysis was to test a series of 6 machine learning models to determine which is most effective at assessing credit card risk for consumers. Given the binary nature of assessing risk in this way - either consumers are "high" risk or "low" risk - we tested classification models to make predictions. 

### Results
Below is a list of the balanced accuracy and recall scores for all six of the models.

(1) Naive Random Oversampling: 
Balanced Accuracy Score - .65
Recall - .63

(2) SMOTE Oversampling:
Balanced Accuracy Score - .63
Recall - .68

(3) Undersampling:
Balanced Accuracy Score - .63
Recall - .55

(4) Combination (Over and Under):
Balanced Accuracy Score - .57
Recall - .57

(5) Random Forest Classifier:
Balanced Accuracy Score - .5
Recall - .99

(6) Easy Ensemble AdaBoost Classifier:
Balanced Accuracy Score - 1
Recall - 1

### Summary
The ensemble classification models had the highest overall accuracy and recall scores. The final model - an Easy Ensemble AdaBoost - was assessed to be the strongest overall model. This model's classification report scores were consistently as high or higher than  those of the other models.