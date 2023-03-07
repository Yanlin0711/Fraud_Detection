# Fraud_Detection
Fraud detection machine learning project with Logistic Regression, KNN and Random Forest
For this project, there are two main parts:
  1. Fix the imbalance dataset to make sure it is ready for machinne learning models
  2. Feed under-sampled and over-sampled dataset to Logistic Regression, KNN and Random Forest Model
There are two biggest challenge in this project:
  1. For the first try, I used Nearmiss method for under-sampling but I did the Nearmiss after spliting the original dataset, which caused bad performance of my models.
     Then I changed the method to regualr random over-sampling, and did the oversampling before the spliting. By doing so, the performance of three models I used 
     extremely increased. 
  2. The second challenge is tuning the machine learning model. Write the code for gridsearch is kinda difficult. But I did it! :)
