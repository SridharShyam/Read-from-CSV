# Read-from-CSV
### NAME: SHYAM S
### REG.NO: 23012478
### DEPT: AIML
## AIM:
To Write a python program for reading content from a CSV file.

## ALGORITHM:
### Step 1:
Import pandas module as pd.
### Step 2:
Read a csv file name cars[1].csv.
### Step 3:
print the first five rows and last five rows.
### Step 4:
print the length of the rows and columns.
### Step 5:

End the program.

## PROGRAM:
```

#Program for Multivariate Linear Regression
#Developed by: SHYAM S
#Register Number: 23012478

import pandas as pd
df=pd.read_csv("cars[1].csv")
print(df.head(10))
print(df.tail(5))
print("Number of Rows:",len(df.axes[0]))
print("Number of Columns:",len(df.axes[1]))

```


## OUTPUT:

![Screenshot 2024-01-02 211328](https://github.com/SridharShyam/Read-from-CSV/assets/144871368/e3365462-e716-4971-a8ef-d7d30bc29723)

## RESULT:
Thus the program is written to read a csv file.
