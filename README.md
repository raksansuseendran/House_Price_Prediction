# House_Price_Prediction

Project Description
---------------------

• The goal of this web application is to predict the price of the house by utilizing the relation between house 
features and how these variables are affecting the target attribute. 

• Implemented a model using the Random Forest algorithm in terms of minimizing the difference between 
predicted and actual price of the house.

Atrributes of the data
-----------------------

1. CRIM: per capita crime rate by town
2. ZN: proportion of residential land zoned for lots over 25,000 sq.ft.
3. INDUS: proportion of non-retail business acres per town
4. CHAS: Charles River dummy variable (= 1 if tract bounds river; 0 otherwise)
5. NOX: nitric oxides concentration (parts per 10 million)
6. RM: average number of rooms per dwelling
7. AGE: proportion of owner-occupied units built prior to 1940
8. DIS: weighted distances to five Boston employment centres
9. RAD: index of accessibility to radial highways
10. TAX: full-value property-tax rate per $10,000
11. PTRATIO: pupil-teacher ratio by town
12. B: 1000(Bk - 0.63)^2 where Bk is the proportion of blacks by town
13. LSTAT: % lower status of the population
14. MEDV: Median value of owner-occupied homes in

Inference
----------

#Results:-
**for LinearRegression**

Rmse =  4.22823975454173

Rmse cross val scores = 
 [4.21674442 4.26026816 5.1071608  3.82881892 5.34093789 4.3785611
 7.47384779 5.48226252 4.14885722 6.0669122 ]

**for DecisionTreeRegressor**

Rmse =  4.579825752315106

Rmse cross val scores =
 [4.00051826 3.99264568 5.5571751  4.12458424 4.09615674 2.79986607
 5.19155564 3.746465   3.25326759 4.28893926]

 **for SGDRegressor**
 
 Rmse =  4.252223739738116
 
Rmse cross val scores = 
 [4.24276292 4.20132664 5.16754377 3.81191694 5.30153767 4.41060904
 7.56190827 5.47565146 4.16871895 6.12701213]

 **for KNeighborsRegressor**
 
 Rmse =  4.312169282573288
 
Rmse cross val scores = 
 [3.61967119 4.70763158 5.16523463 4.45849805 4.6198777  3.46735923
 8.47209655 5.52478235 3.22961608 4.1353174 ]

**for RandomForestRegressor**

Rmse =  3.3789639901985953

Rmse cross val scores = 
 [2.87667815 2.90645052 4.44626112 2.62887072 3.43234611 2.54121222
 4.512502   3.27714691 3.44440933 3.21893902]

Appropriate Model
------------------

**RandomForestRegressor model** is the most accurate one in this case(as it is giving lowest rmse)
