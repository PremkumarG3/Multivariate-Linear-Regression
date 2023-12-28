# Implementation of Multivariate Linear Regression
## Aim
To write a python program to implement multivariate linear regression and predict the output.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1
Import an package of panda and from sklearn import linear_model
### Step2
Then link the data available csv file as an variable data
### Step3
Then take weight and volume as x and CO2 as y
### Step4
Using linear_model.LinearRegression() fit as x and y Then predict the output
### Step5
End the program

## Program:
```
Implement of Multivariate linear regression and predict the output
Developed By:PREM KUMAR G
Reference number: 23003614
import pandas as pd
from sklearn Import linear model
data=pd.read_csv("cars (1).csv")
x=data['Weight', 'Volume']]
y=data[[C02']]
regr=linear_model.Linear Regression()
regr.fit(x,y)
print("Coefficients:",regr.coet_)
print('Intercept:',regr.intercept_)
predictCO2=regr.predict([[3300,1300]])
print("Predicted CO2 for the corresponding weight and volume",predictCO2)
```
## Output:
![Screenshot 2023-12-29 000223](https://github.com/PremkumarG3/Multivariate-Linear-Regression/assets/138955646/8b9db97e-34fd-432b-963c-3d7e5dcdfcba)

## Result
Thus the multivariate linear regression is implemented and predicted the output using python program.
