# Machine-Learning-Practice

## What is Machine Learning (ML) ?

Answer: Machine learning is an application of artificial intelligence (AI) that provides systems the ability to automatically learn and improve from experience without being explicitly programmed. Machine learning focuses on the development of computer programs that can access data and use it learn for themselves.

The process of learning begins with observations or data, such as examples, direct experience, or instruction, in order to look for patterns in data and make better decisions in the future based on the examples that anyone provide. The primary aim is to allow the computers learn or calculate automatically without human intervention or assistance and adjust actions accordingly...

There are three important libraries for Machine Learning. They are:
                                      
                                      i) numpy
                                      
                                     ii) pandas
                                     
                                    iii) matplotlib.pyplot
                                    
i) Numpy : import numpy as np

NumPy is the fundamental package for scientific computing with Python. 

Machine Learning total system is all about developing mathematical model. Everything is about mathematics in Machine Learning. 

ii) pandas: import pandas as pd

pandas is for importing dataset. This library is most important and the best one for importing dataset in Machine Learning. Without dataset Machine Learing cann't be started. So, dataset always needs to be imported while doing any project. Thats why this library is so important.

iii) matplotlib.pyplot: import matplotlib.pyplot as plt

matplotlib is a library and pyplot is a sub-library of matplotlib. This library is needed for ploting any graphical representation.

## What is Regression?

Answer: Regression is a model value based on independent predictors. This method is used for forecasting and finding out effect relationships between variables. Regression techniques are based on the number of independent variables and the type of relationship between the independent and dependent variables. There are two variables. Ther are:

                                           a) X - independent variable and
                                           b) y - dependant variable

Types of Regression:

  i) Linear Regression

 ii) Multiple Linear Regression

iii) Polynomial Regression

 iv) Decision Tree Regression

  v) Random Forest Regression

## 1. Linear Regression: 

Linear regression is called as simple linear regression. Simple linear regression is a type of regression analysis where the number of independent variables is one and there is a linear relationship between the independent(x) and dependent(y) variable. Equation for simple linear regression:

                                           y = b_0 + b_1 * x
                                      
Here, x is Independent variable and y is Dependent variable. In linear regression there will be always one Independent variable.

b_0 and b_1 are called as co-efficient. Co-efficient create relationship between Independent and Dependent variable.

The motive of the linear regression algorithm is to find the best values for b_0 and b_1. 

## 2. Multiple Linear regression: 

Equation for multiple linear regression:

                            y = b_0 + b_1 * x_1 +  b_2 * x_2 + ....... + b_n * x_n
                            
Here, x_1, x_2, ....., x_n are Independent variables and y is Dependent variable. In multiple linear regression there will be always multiple Independent variables.        

b_0, b_1, ..... , b_n are called as co-efficient. Co-efficient create relationship between Independent and Dependent variable.

## 3. Polynomial Regression:

Polynomial regression is a special case of linear regression. We can get good fit line on the data for linear regression. But considering real world examples the data might not be so linearly but more scattered. In such cases linear regression might not be the best way to describe the data. A curved or non linear line might be a better fit for such data.

Equation for polynomial regression:

                           y = b_0 + b_1 * x +  b_2 * x^2 + b_3 * x^3 + ....... + b_n * x^n

Here n is the degree of the polynomial, x are Independent variables and y is Dependent variable.


## 4. Support Vector Regression:

In simple regression we try to minimise the error rate. While in SVR we try to fit the error within a certain threshold.

## Decision Tree Regression :
Decision Tree is a decision-making tool that uses a flowchart-like tree structure or is a model of decisions and all of their possible results, including outcomes, input costs and utility.

## Random Forest regression :

Scenario 1: Facebook recognizes your friend in a picture from an album of tagged photographs
Explanation: It is supervised learning. Here Facebook is using tagged photos to recognize the person. 
Therefore, the tagged photos become the labels of the pictures and we know that when the machine is learning from labelled data, it is supervised learning.

Scenario 2: Recommending new songs based on someone’s past music choices
Explanation: It is supervised learning. The model is training a classifier on pre-existing labels (genres of songs).
This is what Netflix, Pandora, and Spotify do all the time, they collect the songs/movies that you like already, 
evaluate the features based on your likes/dislikes and then recommend new movies/songs based on similar features.

Scenario 3: Analyze bank data for suspicious looking transactions and flag the fraud transactions
Explanation: It is unsupervised learning. In this case, the suspicious transactions are not defined, 
hence there are no labels of "fraud" and "not fraud". The model tries to identify outliers by looking at anomalous transactions and flags them as 'fraud'

