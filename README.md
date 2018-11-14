# NLP_SentiAnalysis_RFGridSearch
Code for Amazon product review dataset with RandomForest Gridsearch best parametes

Notes:
Dataset: Automotive, similar Amazon review datasets are available at http://jmcauley.ucsd.edu/data/amazon/

Step1: Import necessary libraries 
Step2: New features creation
       Created new feature "Review", which has all data points that has rating 4 and 5 as 1, leaving others i,e 1,2,3 as 0
Step3: Review Text preprocessing(includes stemming, lemmatization)
Step4: Output variable bias balancing using SMOTE
Step5: Intiate and predict a Random Forest classifier as base model
Step6: Initiate Grid search for best parameters
Step7: Initiate and predict Random Forest Classifier with step:6 best parameters
Step8: calculate the % increase of accuracy from base model to best parameters model    

This is just basic code to understand how tuning RF model increases the accuracy of the model.
