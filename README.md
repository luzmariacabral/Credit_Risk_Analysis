# Credit_Risk_Analysis
In this challenge we are being tasked with analyzing six different machine learning models and choose the best for risk assessment of a loan application. The six are Oversampling and SMOTE, Clcuster Centroids or Undersampling algorigthms, a combination approach of over and undersampling using the SMOTEEN algorithm, Balanced Randomg Forest Classifier and Easy Ensemble Classifier. We will review each models balanced accuracy scores along with their precisioin and recall scores to determine which model would help us best assess risk in the loan application. At the end a recommendation will be made for the best model for the task. 

To quickly review Balanced Accuracy Scores are how tests stand up to targeting the problem, a program may address the question but may not always provide the correct answer. Precision scores or positive predictive values, measures the likelihood that the tests are correct. Recall is is much more sensitive to detecting outcomes or a target problem, most commonly used in the medical field to check for illnesses. These 3 factors will assist us in determining a good model to use. 

## Results of Testing the Six Models
To assess these models we will be reviewing a dataset from the LendingClub for each model, after reviewing it and cleaning it up we split the data into training and testing batches to put through each model

### Oversampling
- Balanced Accuracy Score: 0.6473
- Precision: 0.99
- Recall: 0.57

### Undersampling or Cluster Centroid
- Balanced Accuracy Score: 0.5447
- Precision: 0.99
- Recall: 0.57

### SMOTE Algorithm
- Balanced Accuracy Score: 0.6447
- Precision: 0.99
- Recall: 0.57

### SMOTEEN Algorithm
- Balanced Accuracy Score: 0.6621
- Precision: 0.99
- Recall: 0.57

### Balanced Random Forest Classifier
- Balanced Accuracy Score: 0.7885
- Precision: 0.99
- Recall: 0.87

### Easy Ensemble Classifier
- Balanced Accuracy Score: 0.9316
- Precision: 0.99
- Recall: 0.94


## Summary: Which did it best?
The results that were produced by each model were very similar to each other. In the firs 4 models, over and undersampling, SMOTE and SMOTEEN, the Balanced Accruacy Score ranged between 54% and 64%, which means that these tests are completing their functions but the results they are producing are correct half the time, at best approximately 65% of the time. All 4 of these models produced a Precision score of 99%, wich means those that those application that were approved or were categorized as 'low_risk" were 99% accurately chosen. All 4 models chose with high precision rates, however the sensitivity of the algorithms are low, at 57%, so it's difficult to know if these test were correct. 

With the ensemble learners the outcomes were different and what feels would produce the better outcomes. They both carried higher Balanced Accuracy Scores; the Balanced Random Classifier was 78% and Easy Ensemble is 93%. Both scoring high in Precission and in Sensitivity, making these probably higher to detect bad applications or applicants with a higher risk. Now it's hard to make a decision for the best model to use because it's understood that this sample is controled with a set outcome to expect. Reviewing the performance of these models in the real world may also provide different outcomes, each would probably excel in different industrry in comparison to the others. Based on this information and the way these tests were done my recommendation would be for the Ease Ensemble Classifier model, with the higher scored to detect high riks applicants.  
