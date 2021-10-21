# Credit Risk Analysis
# Overview of the Loan Prediction Risk Analysis

## Purpose:
The purpose of this project was to analyze a dataset from LendingClub to predict credit risk using six supervised machine learning models.
## Results:
1.	Random Overampling:<br>
•	Balance accuracy score rounded to the nearest percent is 67%.<br>
•	The high-risk precision is at 1% and recall score is 69%.<br>
•	The low-risk precision is at 99% and recall score is 61%.<br>
![Random over Sampler](https://user-images.githubusercontent.com/86321353/138346165-e551104f-74bb-4532-b44b-68c3874a0eb4.png)
2.	SMOTE Oversampling:<br>
•	Balance accuracy score rounded to the nearest percent is close to the previous model at 66%.<br>
•	The high-risk precision is at 1% and recall score is 63%.<br>
•	The low-risk precision is at 100% and recall score is 69%.<br>
![SMOTE](https://user-images.githubusercontent.com/86321353/138346197-18995ab5-028f-4c4a-b1a4-2a74cf4916c7.png)
3.	Cluster Centroids:<br>
•	Balance accuracy score rounded to the nearest percent is 54%.<br>
•	The high-risk precision is at 1% and recall score is 69%.<br>
•	The low-risk precision is at 100% and recall score is 40%.<br>
![Cluster Centroids](https://user-images.githubusercontent.com/86321353/138346222-76349d73-2f68-4247-943a-9ceb40a17bce.png)
4.	SMOTEEN:<br>
•	Balance accuracy score rounded to the nearest percent is 66%.<br>
•	The high-risk precision is at 1% and recall score is 73%.<br>
•	The low-risk precision is at 100% and recall score is 59%.<br>
![SMOTEEN](https://user-images.githubusercontent.com/86321353/138346245-988eb4c7-7588-4469-b824-4ccb3229b72b.png)
5.	Balanced Random Forest Classifier:<br>
•	Balance accuracy score rounded to the nearest percent is 79%.<br>
•	The high-risk precision is at 3% and recall score is 70%.<br>
•	The low-risk precision is at 100% and recall score is 87%.<br>
![Balanced Random forest](https://user-images.githubusercontent.com/86321353/138346276-1adf0d8d-2a66-41ef-8b93-22109fafa84b.png)
6.	Easy Ensemble Classifier:<br>
•	Balance accuracy score rounded to the nearest percent is 93%.<br>
•	The high-risk precision is at 9% and recall score is 92%.<br>
•	The low-risk precision is at 100% and recall score is 94%.<br>
![Easy Ensemble](https://user-images.githubusercontent.com/86321353/138346292-d7c0275f-bc0e-4a3b-995d-afcfec574b3d.png)


## Summary of the results:
After our review, we have determined that most of the models we analyzed are not good at predicting high risk loans as they classified most of the applications as low risk. Out of the 6, we can say that the Easy Ensemble Classifier had the highest sensitivity at 92% to predict a high risk

## Recommendations:
I would not recommend using any of the models, since they were not good at predicting high risk loans. If we had no other option, I would recommend using the Easy Ensemble Classifier as it was closer to our target point; However, it is still risky to use it.
