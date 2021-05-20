# BigMart-Sales-Prediction
The data scientists at BigMart have collected 2013 sales data for 1559 products across 10 stores in different cities. Also, certain attributes of each product and store have been defined. The aim is to build a predictive model and predict the sales of each product at a particular outlet.                                                          Using this model, BigMart will try to understand the properties of products and outlets which play a key role in increasing sales.

## Data Dictionary
We have train (8523) and test (5681) data set, train data set has both input and output variable(s). You need to predict the sales for test data set.

**Train file:** CSV containing the item outlet information with sales value
![image](https://user-images.githubusercontent.com/60176731/118969085-4b024f00-b98a-11eb-8fdf-8c6f7a51b9ad.png)

**Test file:** CSV containing item outlet combinations for which sales need to be forecasted
![image](https://user-images.githubusercontent.com/60176731/118969326-8e5cbd80-b98a-11eb-8806-266ff125c8ba.png)

## Evaluation Metric
 Model performance will be evaluated on the basis of prediction of the sales for the test data (test.csv), which contains similar data-points as train except for the sales to be predicted.

Root Mean Square Error value is a primary way to judge performance of code

## Exploratory Data Analysis : 
Both Univariate Analysis and Bivariate Analysis is performed in seperate file

## Data Preperation and Feature Engg:
Data cleaning using missing value treatment and created new features using Feature engg method. It comes in a seperate file

## Data Modelling
In a single file, all kinds of model is tried to reach min of Root mean square value alongwith hyperparameter tuning for Random Forest. Its regession type all all related model is used to predict the output

## Files Saved
All related csv files can be created and saved in the folder. Same has been used to submit in hackathon
