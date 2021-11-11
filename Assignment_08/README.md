# ENSEMBLES
_____________________________________________________________________________________________________________________________________________________________________________
## DATASET DESCRIPTION
This dataset is about the information regarding flights.Few of them are timing related to arrival, departure, seats, company , destination, etc. This dataset can be available from many sources eg. Kaggle. This datset consist of a lot of missing values.
- https://www.kaggle.com/search?q=flight-data+in%3Adatasets

This analysis contains the visualization in the form of various graphs and Python libraries which are used in this notebook are Numpy, Pandas, Matplotlib, Seaborn. There are 24 columns in total with a significant number of missing values.
_____________________________________________________________________________________________________________________________________________________________________________
## PROBLEM STATEMENT
To predict the delay of flight due to several reasons. Also checking the performance of each model.
_____________________________________________________________________________________________________________________________________________________________________________
## STEPS PERFORMED IN THIS ANALYSIS
- Data inspection and checking the missing values.
- Splitting data into train and test data.
- Creation of pipeline.
- Checking the performance of Logistic regression, decision tree, and SVM using grid search
- Using ensemble and checking its performance
- Checking whether the performance has been improved or not after implementing a model using Adaboost.
- Coming to a conclusion for the best performance.
_____________________________________________________________________________________________________________________________________________________________________________
## CONCLUSION
We were able to get an accuracy score of around 67%. Adaboost not helping in improving the performance and Ensemble has good accuracy in comparision to others.
______________________________________________________________________________________________________________________________________________________________________________
## NEXT STEPS
Can try it with different columns i.e. to check for some more reasons of flight delay. Or can look out for more data.


