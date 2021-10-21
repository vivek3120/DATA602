## MODEL EVALUATION
In this we are using logistic regression model for this dataset. The project contains the visualization in the form of various graphs and Python libraries which are used in this notebook are Numpy, Pandas, Matplotlib, Seaborn. The modelling is done with the help of several modules of Scikit-Learn package. This dataset contains 9 columns and here we will be checking whether the patient is having diabetes or not on few measures.
_____________________________________________________________________________________________________________________________________________________________________________
## DATASET DESCRIPTION
This dataset is available on kaggle.
https://www.kaggle.com/uciml/pima-indians-diabetes-database
_____________________________________________________________________________________________________________________________________________________________________________
## STEPS PERFORMED IN THIS ANALYSIS
- Data inspection and checking the missing values.
- Splitting data into train and test data.
- Creation of pipeline using logistic regression and standard scalar.
- Running regression model with grid search cross-validation using 10 folds.
- Searching 5 different regularization strengths and 2 solvers.
- Coming to a conclusion for the best model and how it goes with test set.
_____________________________________________________________________________________________________________________________________________________________________________
## CONCLUSION
After using gridsearch recall score showed changes. Used recall metric as it focuses on positive instances. Accuracy got improved and as ROC area was more than 50%, which means it is a good model. The model with less false negatives is the best one.
