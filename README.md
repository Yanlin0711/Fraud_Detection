# Fraud_Detection
Fraud detection machine learning project with Logistic Regression, KNN and Random Forest

For this project, there are two main parts:
  1. Fix the imbalance dataset to make sure it is ready for machinne learning models
  2. Feed under-sampled and over-sampled dataset to Logistic Regression, KNN and Random Forest Model
 
There are two biggest challenge in this project:
In the first try with under-sampling, the performance of three classifier is extremely poor. The precision and recall are all below 0.5. The reason is that the procedure of under-sample was wrong. The correct procedure should be under-sample the origin dataset first then do the train-test spliting. But I did it in the ooposite way. When I correct the procedure, the precison for all three classifier went over 90%.
The second challenge is about parameter scaling. In the first try, I scaled both time and transaction amount. In the second try, I only scaled time. The result shows that scaling time only can bring better performance. Especially for the KNN model

For the future improvements, I think I can apply more advanced undersampling and oversampling methods, such as SMOTE and NEARMISS. For the model improvement, I think I can also apply unsupervised machine models, such as SVM, into this project. 
