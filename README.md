# Read-from-CSV
### NAME: SHYAM S
### REG.NO: 23012478
### DEPT; AIML
## AIM:To Write a python program for reading content from a CSV file

## ALGORITHM:
### Step 1:
import sys module.
### Step 2:
Using sys module,open a file with read mode.
### Step 3:
Read the file and split the file and store it in the variable.
### Step 4:
print the length of the variable.
### Step 5:
End the program.

## PROGRAM:
```
#Program for Multivariate Linear Regression
#Developed by: SHYAM S
#Register Number: 23012478

import pandas as pd
from sklearn import linear_model

df=pd.read_csv('cars[1].csv')
a=df[["Weight","Volume"]]
b=df[["CO2"]]
regr=linear_model.LinearRegression()
regr.fit(a,b)
print("Coefficient:",regr.coef_)
print("Intercept:",regr.intercept_)
print("Amount:",regr.predict([[3300,1300]]))
```


## OUTPUT:

![Screenshot 2024-01-02 204543](https://github.com/SridharShyam/Read-from-CSV/assets/144871368/80e7cd6f-2393-4434-9e7e-450cc1038813)


## RESULT:
Thus the program is written to read a csv file.
