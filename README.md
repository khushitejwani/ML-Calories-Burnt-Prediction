# ML-Calories-Burnt-Prediction
Implemented and analyzed regression techniques (XGBoost, Linear Regression, Ridge Regression) to predict post-workout calorie burn based on biological features (age, gender, height, weight, exercise duration, heart rate, body temperature).

This problem uses supervised learning techniques as the data that has been used for training
the models is labelled data, i.e. data that has an output tagged to it. The types of regression
used in this project are supervised machine learning techniques.
Further, this project is a prediction problem as the target feature is ‘Calories Burned’ which
is a numeric problem and has to be predicted by the different regression techniques.

The libraries used in this project are as follows:
I. Pandas
II. Numpy
III. Matplotlib
IV. Seaborn
V. Sklearn
VI. Xgboost

There are two csv files, exercise.csv and calories.csv which needed to be uploaded to Google
Colaboratory and combined into one data frame which was then used for processing.
Exercise.csv has 8 attributes and 15000 instances whereas calories.csv has 2 attributes and
15000 instances. 

It can be concluded that XGBoost Regressor is the best regression technique for the above
dataset or any dataset which includes numeric attributes only and the attributes have high
multicollinearity. Ridge regression may outperform MLR as it improves the accuracy of the
regression model and prevents overfitting.
