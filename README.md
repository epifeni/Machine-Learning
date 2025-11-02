# Machine Learning/Deep Learning Model Notes
## Classification Error Performance Evaluation
* **Accuracy** in classification porblems is the **number of correct predictions** made by the model divided by the **total number of predictions**. How many prediction did you get right as a percentage?
  * Accuracy is a good indicator of model performance on balanced data only
* **Recall** is the ability of a model to find all the relevant cases within a dataset
  * Expresses the ability of finding all the relevant instances in a dataset
  * = Number of true positives / (number of true positives {correct positive predictions} + number of false negatives {incorrect positive predictions})
* **Precision** of a classification model is to identify only the relevant data points
  * Expresses the propotion of the datasets our model says was relevant that actually were relevant
  * = Number of true positives / (number of true positives + number of false positives {incorrectly classifed as positive})
* F1 Score finds the optimal blend of precision and recall
* * The harmonic mean of precision and recall
  * = 2 X [(precision * recall) / (precision + recall)]
   * Harmonic mean punishes extreme differences between precision and recall

# Confusion Matrix - Compares the predicted values to the true values
<img width="851" height="400" alt="image" src="https://github.com/user-attachments/assets/4176ae46-8a37-45d7-ab33-c6eeb49f5f27" />  

## Correct Predictions
* *True positive* - the person having the disease and the model correctly predicting that they have the disease
* *True negative* - the person not having the disease and the model correctly predicting that they do not have the disease
## Incorrent Predictions
* *False positive* (Type 1 Error) - the person does not have the disease by the model inaccurately predicts taht they do have the disease. The model is falsely saying the person is positive for the disease
* *False negative* (Type 2 Error) - the person does have the disease but the model inaccuraetly predicts that they do not have the disease.

## Calculations
<img width="815" height="432" alt="image" src="https://github.com/user-attachments/assets/4d6b1f79-2a40-4da2-a2fa-dcd2e461e457" />  

## Regression Error Performance Evaluation  







