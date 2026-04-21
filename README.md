# Implementation-of-Simple-Linear-Regression-Model-for-Predicting-the-Marks-Scored
# Date: 21-04-2025
## AIM:
To write a program to predict the marks scored by a student using the simple linear regression model.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Jupyter notebook

## Algorithm
1. Import the necessary libraries.
2. Get the input of mark and hours of study from the user.
3. Create the model using LinearRegression() function.
4. Train the model using fit() function.
5. Test the model using predict() function.
6. Plot the Datas in the graph using plt() function.

## Program:
```
/*
Program to implement the simple linear regression model for predicting the marks scored.

import numpy as np
import matplotlib.pyplot as plt
from sklearn.linear_model import LinearRegression
X=np.array([2,4,6,8,2,6]).reshape(-1,1)
Y=np.array([32,54,67,89,32,54])
model=LinearRegression()
model.fit(X,Y)
m = model.coef_[0]
c=model.intercept_
print("Slope:",m)
print("Intercept:",c)
x_new=int(input("Enter X value"))
Y_predicted=model.predict([[x_new]])
print("Y_predicted: ",Y_predicted)
Y_pred=model.predict(X)
plt.scatter(X,Y,label="Actual Values")
plt.plot(X,Y_pred,label="Best Fitted Line")
plt.xlabel("Hours")
plt.ylabel("Marks")
plt.title("Simple linear regression")
plt.legend()
plt.show()

Developed by: MUTTHU M
RegisterNumber:  212225040269
*/
```

## Output:
<img width="756" height="598" alt="image" src="https://github.com/user-attachments/assets/03b5f76b-534c-4eb5-8691-f5ebfa23bbb3" />


## Result:
Thus the program to implement the simple linear regression model for predicting the marks scored is written and verified using python programming.
