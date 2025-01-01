# Implementation of Multivariate Linear Regression
## Aim
To write a python program to implement multivariate linear regression and predict the output.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1
<br>Import the required libraries: pandas for data manipulation
and linear_model from sklearn for regression modeling.

### Step2
<br>Load the dataset using pd.read_csv.
The dataset should contain columns such as volume, weight, and CO2.

### Step3
<br>Split the dataset into:
Features (X): Independent variables (volume and weight).
Target (y): Dependent variable (CO2 emissions).

### Step4
<br>Instantiate the Linear Regression model using
linear_model.LinearRegression().

### Step5
<br>Use the .fit(X, y) method to train the model
on the features (X) and target (y).

### step6
<br>Coefficients (regression.coef_): Indicate the strength
and direction of the relationship between each independent variable and the dependent variable.
Intercept (regression.intercept_): Represents the model's y-intercept
when all independent variables are zero

### step7
<br>Use the .predict() method to predict CO2 emissions
for new car data (e.g., a car with volume=3300 and weight=1300).

## Program:
```
import pandas as pd
from sklearn import linear_model
df-pd.read_csv("C:\\Users\\admin\\Downloads\\car.csv")
x=df[["volume", "Weight"]]
y=df["CO2"]
regression-linear_model.LinearRegression()
regression.fit(x,y)
print("Coefficient", regression.coef_)
print("Intercept", regression.intercept_)
print("CO2 required is", regression.predict([[3300,1300]]))

```
## Output:
![](<Screenshot 2024-12-23 144953.png>)


<br>

## Result
Thus the multivariate linear regression is implemented and predicted the output using python program.