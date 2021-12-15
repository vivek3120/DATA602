# PROJECT - Chicago Car Crashes
_____________________________________________________________________________________________________________________________________________________________________________
## DATASET DESCRIPTION
Using the data from "Chicago Car Crash Dataset" which as more than 569700 records. The dataset as details of date and time of accident occurred, location and cause of accident and soon. This dataset can be available from chicago government website. This dataset consist of a lot of missing values.
- https://data.cityofchicago.org/Transportation/Traffic-Crashes-Crashes/85ca-t3if/data

This analysis contains the visualization in the form of various graphs and Python libraries which are used in this notebook are Numpy, Pandas, Matplotlib, Seaborn.
pandas for data analysis
numpy for scientific computation
matplotlib for basic plotting
seaborn for advanced plotting
sci-kit learn for modeling & evaluations
_____________________________________________________________________________________________________________________________________________________________________________
## PROBLEM STATEMENT
Build a model to predict the severity of a traffic crashes based on Chicago Police Department crash dataset.
_____________________________________________________________________________________________________________________________________________________________________________
## STEPS PERFORMED IN THIS ANALYSIS
- Data inspection and checking the missing values.
- Splitting data into train and test data.
- Creation of pipeline.
- Checking the performance of Logistic regression, decision tree, and Random Forest.
- Checking whether the performance has been improved or not.
- Coming to a conclusion for the best performance.
- we'll focus on preprocessing our data.

Important steps such as identifying and handling null values in the columns.
Converted object type feature to int or float type using pandas functions.
Merged and capped the values of columns to reduce the outliers.
Dropped the column which are inconclusive.
Transformed categorical variables by using one-hot encoding or "dummy variables".
_____________________________________________________________________________________________________________________________________________________________________________
## CONCLUSION
We were able to get an accuracy score of around 0.8290781329331086
Final models show that certain columns have more of an effect on the severity of a car accident than others.
Demonstrated how different classification models work and how we can compare models using the roc_auc score metric.
I used Random Forest classifier due to its high score among the all models used.

Noticed increased number of the accidents is in the month closer to October.
Noticed increased number of the accidents in the rush hour.
Most accidents occurred in a clear weather condition.
Accidents are more likely to occur in Summer season.
Most accidents happened in a DRY Road condition.
Most severe and non severe accident damage cost is more than $1500.
______________________________________________________________________________________________________________________________________________________________________________
## NEXT STEPS
Looking to explore the dataset a little more to reduce the number of crashes.


