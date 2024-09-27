### Implementation-of-Decision-Tree-Classifier-Model-for-Predicting-Employee-Churn

## AIM:
To write a program to implement the Decision Tree Classifier Model for Predicting Employee Churn.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Jupyter notebook

## Algorithm
1.Import pandas module and import the required data set.
2.Find the null values and count them.
3.Count number of left values.
4.From sklearn import LabelEncoder to convert string values to numerical values.
5.From sklearn.model_selection import train_test_split.
6.Assign the train dataset and test dataset.
7.From sklearn.tree import DecisionTreeClassifier.
8.Use criteria as entropy.
9.From sklearn import metrics.
10.Find the accuracy of our model and predict the require values.

## Program:
```
/*
Program to implement the Decision Tree Classifier Model for Predicting Employee Churn.
Developed by: Jabez S
RegisterNumber: 212223040070
*/
import pandas as pd
data = pd.read_csv("Employee.csv")
data.head()
data.info()
```

## Output:
![Screenshot 2024-09-27 083656](https://github.com/user-attachments/assets/a0895965-953c-4f8d-867d-dad74f9f6f23)

## Result:
Thus the program to implement the  Decision Tree Classifier Model for Predicting Employee Churn is written and verified using python programming.
