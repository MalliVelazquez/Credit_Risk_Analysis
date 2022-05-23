# Credit_Risk_Analysis
 
## Analysis Overview

The purpose of this analysis is to create a machine learning model to predict and evaluate credit risk of the potencial clients.

## Results

### Naive Random Oversampling

* Accuracy Score: 67.5%
* Precision High Risk: 1%
* Precision Low Risk: 100%
* Recall High Risk: 69%
* Recall Low Risk: 66%

![Oversampling_Analysis](https://user-images.githubusercontent.com/96633294/169722881-99c42f48-06cc-4923-ac66-a118896c2cea.png)


### SMOTE 

* Accuracy Score: 67.7%
* Precision High Risk: 1%
* Precision Low Risk: 100%
* Recall High Risk: 70%
* Recall Low Risk: 65%

![SMOTE_Analysis](https://user-images.githubusercontent.com/96633294/169723113-ec2a2af3-ffe7-456f-88b5-ebf02f348553.png)


### Cluster Centroid Undersampling

* Accuracy Score: 51.9%
* Precision High Risk: 0%
* Precision Low Risk: 100%
* Recall High Risk: 64%
* Recall Low Risk: 40%

![Undersampling_Analysis](https://user-images.githubusercontent.com/96633294/169723333-a8a3584a-9a71-4418-85b7-7a33a16f53f9.png)


### SMOTEENN

* Accuracy Score: 68%
* Precision High Risk: 1%
* Precision Low Risk: 100%
* Recall High Risk: 76%
* Recall Low Risk: 60%

![SMOTENN_Analysis](https://user-images.githubusercontent.com/96633294/169723558-31e36b91-cad2-4042-98bb-e3ee4396b389.png)

### Easy Ensemble Classifying

* Accuracy Score: 92.3%
* Precision High Risk: 6%
* Precision Low Risk: 100%
* Recall High Risk: 91%
* Recall Low Risk: 94%

![Easy_Ensemble_Analysis](https://user-images.githubusercontent.com/96633294/169732049-60de8888-f6cb-40fa-a944-28eb0da1f71c.png)

## Summary

As we can see in the previous analysis, 5 options for risk determination can be viable and would give us a fairly accurate prediction, however the most accurate turns out to be the Easy Ensemble Classifying model.

I do not recomend the model Cluster Centroid Undersampling since this just have an Accuracy Score of 51.9% wich can not be very helpful. 
