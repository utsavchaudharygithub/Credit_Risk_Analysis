# Credit_Risk_Analysis

* Use Resampling Models to Predict Credit Risk:  Evaluated three machine learning models by using resampling to determine which is better at predicting credit risk. We used the oversampling RandomOverSampler and SMOTE algorithms, and then used the undersampling ClusterCentroids algorithm. Using these algorithms, resampled the dataset, viewed the count of the target classes, trained a logistic regression classifier, calculated the balanced accuracy score, generated a confusion matrix, and generate a classification report.


<img width="818" alt="Screen Shot 2022-03-07 at 11 56 08 PM" src="https://user-images.githubusercontent.com/91306158/157191993-a4f6f803-e166-4e3a-807a-01c0af7db602.png">

Balanced accuracy score is ~65%. The low_risk percision is highter at 1% and sensitivity is 67%

* Use the SMOTEENN Algorithm to Predict Credit Risk: We used a combinatorial approach of over- and undersampling with the SMOTEENN algorithm to determine if the results from the combinatorial approach are better at predicting credit risk than the resampling algorithms. Using the SMOTEENN algorithm, we resampled the dataset, viewed the count of the target classes, trained a logistic regression classifier, calculated the balanced accuracy score, generated a confusion matrix, and generate a classification report.

<img width="977" alt="Screen Shot 2022-03-08 at 12 03 18 AM" src="https://user-images.githubusercontent.com/91306158/157193098-1b612ecd-1926-4d9c-bc84-930d78afeb9a.png">

Balanced accuracy score is ~65%. The low_risk percision is highter at 1% and sensitivity is 66%



Deliverable 3: Use Ensemble Classifiers to Predict Credit Risk
Deliverable 4: A Written Report on the Credit Risk Analysis (README.md)
