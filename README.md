# Overview 
## Why do this
In order to determine which credit card loan applications should be considered as high risk vs low risk, we are going to use supervised machine learning to find out. 
## How to do this 
we will build and evaluate models using resampling like imbalanced-learn; scikitlearn; RandomOverSampler; SMOTE; BalancedRandomForestClassifier;ClusterCentroids; SMOTEENN; EasyEnsembleClassifier.Totally we will test 4 resampling models and 2 ensemble models.
# Results
* ### Naive Random Oversampling results
![Screenshot (252)](https://user-images.githubusercontent.com/100504550/178140640-39aef413-bd04-4836-a12b-ebe43db14161.png)
* ### SMOTE oversampling results
![Screenshot (253)](https://user-images.githubusercontent.com/100504550/178140703-fd2757a7-4500-4291-b1eb-10c7f6aaa698.png)
* ### Undersampling
![Screenshot (254)](https://user-images.githubusercontent.com/100504550/178140735-09f452db-0651-48d0-a39a-40ed86140969.png)
* ### Combination(over and undersampling) results
![Screenshot (255)](https://user-images.githubusercontent.com/100504550/178140769-819dd84f-1cff-44ad-b3c1-782538327d5d.png)
# Summary 
In the first couple models that we undersampled, oversampled and did a combination of both to try and determine which model is best at predicting which loans that withthe higher risk and what loans are good loans.Next two models we resampled the data using ensemble classifiers to try and predict which which loans are high or low risk. It appears that the Easy Ensemble had the best balance of all the models because of it's high accuracy score and good balance of precision and recall scores.
