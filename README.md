# Credit_Risk_Analysis
Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, we needed to employ different techniques to train and evaluate models with unbalanced classes. Jill asks us to use imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling.

# The purpose:
-Use Resampling Models to Predict Credit Risk
- Use the SMOTEENN algorithm to Predict Credit Risk
- Use Ensemble Classifiers to Predict Credit Risk
- A Written Report on the Credit Risk Analysis (README.md)

# Resources used: 
LoanStats_2019Q1.csv
credit_risk_resampling_starter_code.ipynb and credit_risk_ensemble_starter_code.ipynb.

# Applications used:
Jupyter Notebook 


----------------------------
# Use Resampling Models to Predict Credit Risk: 
Evaluated three machine learning models by using resampling to determine which is better at predicting credit risk. We used the oversampling RandomOverSampler and SMOTE algorithms, and then used the undersampling ClusterCentroids algorithm. Using these algorithms, resampled the dataset, viewed the count of the target classes, trained a logistic regression classifier, calculated the balanced accuracy score, generated a confusion matrix, and generate a classification report.
* 
<img width="818" alt="Screen Shot 2022-03-07 at 11 56 08 PM" src="https://user-images.githubusercontent.com/91306158/157191993-a4f6f803-e166-4e3a-807a-01c0af7db602.png">

-Balanced accuracy score: 65%
-Precision high risk: 0.01%
-Precision low risk: 1%
-recall high risk: 63%
-recall low risk: 67%

------------------------------
# Use the SMOTE Algorithm to Predict Credit Risk:
We used a combinatorial approach of over- and undersampling with the SMOTEE algorithm to determine if the results from the combinatorial approach are better at predicting credit risk than the resampling algorithms. Using the SMOTEE algorithm, we resampled the dataset, viewed the count of the target classes, trained a logistic regression classifier, calculated the balanced accuracy score, generated a confusion matrix, and generate a classification report.

<img width="977" alt="Screen Shot 2022-03-08 at 12 03 18 AM" src="https://user-images.githubusercontent.com/91306158/157193098-1b612ecd-1926-4d9c-bc84-930d78afeb9a.png">
-Balanced accuracy score: 79%
-Precision high risk: 0.1%
-Precision low risk: 1%
-recall high risk: 64%
-recall low risk: 66%

--------------------------------
# Random Forest Classifier: 

<img width="1044" alt="Screen Shot 2022-03-08 at 12 12 46 AM" src="https://user-images.githubusercontent.com/91306158/157194660-58481659-ca7b-4939-817a-1034a2800d19.png">

-Balanced accuracy score: 79%
-Precision high risk: 0.4%
-Precision low risk: 1%
-recall high risk: 67%
-recall low risk: 91%


----------------------------
# Use the SMOTEEN algorithm:  
Use the SMOTEEN Algorithm to Predict Credit Risk: We used a combinatorial approach of over- and undersampling with the SMOTEEN algorithm to determine if the results from the combinatorial approach are better at predicting credit risk than the resampling algorithms. Using the SMOTEENN algorithm, we resampled the dataset, viewed the count of the target classes, trained a logistic regression classifier, calculated the balanced accuracy score, generated a confusion matrix, and generate a classification report.

<img width="996" alt="Screen Shot 2022-03-08 at 12 30 00 AM" src="https://user-images.githubusercontent.com/91306158/157197466-c6b683b1-28eb-422e-8284-e0c6b0a4b2f6.png">

-Balanced accuracy score: 61%
-Precision high risk: 0.1%
-Precision low risk: 1%
-recall high risk: 69%
-recall low risk: 55%
  
---------------------------------


# Use Ensemble Classifiers to Predict Credit Risk: 
using imblearn.ensemble library, trained and compared two different ensemble classifiers, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk and evaluated each model. Using both algorithms,resampled the dataset, viewed the count of the target classes, trained the ensemble classifier, calculated the balanced accuracy score, generated a confusion matrix, and generated a classification report.

<img width="1020" alt="Screen Shot 2022-03-08 at 12 28 01 AM" src="https://user-images.githubusercontent.com/91306158/157197132-21dd0372-bce8-457b-a629-3207e3ecf758.png">

-Balanced accuracy score: 92%
-Precision high risk: 7%
-Precision low risk: 1%
-recall high risk: 91%
-recall low risk: 94%

------------------------------------
# Summary on the Credit Risk Analysis
Algorithms used were:
-Resampling Models
-Ensemble Classifiers
-SMOTEEN algorithm
-Random Forest Classifier
 SMOTE Algorithm
 
 Among all the given algorithm Ensemble classifers using imblearn.ensemble library, which has the accuracy rate of 92%. but also has the high recall of 91%. all the algorithms have higher recall risk. When working with balanced accuracy, the highest compared accuracy between 0 and 1 and is closest to 1 is the best machine learning model. Hence, this algorithm is recommened.  
