# Logistic Regression aka GLM aka Logit

[https://boostedml.com/2018/11/what-is-the-difference-between-logit-and-logistic-regression.html](https://boostedml.com/2018/11/what-is-the-difference-between-logit-and-logistic-regression.html)

![Logistic%20Regression%20aka%20GLM%20aka%20Logit%20ff9c4817d4d444dfa8db9587efed44f4/Untitled.png](Logistic%20Regression%20aka%20GLM%20aka%20Logit%20ff9c4817d4d444dfa8db9587efed44f4/Untitled.png)

If the response is yes or no, use this (2 level categorical variable)

Type of generalized linear model (GLM) for response variables where regular multiple regression doesn't work very well. 

In particular, the response variable in these settings often takes a form where residuals look completely different from the normal distribution.

2 stage approach: 

1. Model response using a probability distribution like binomial / Poisson distribution 
2. Model parameter of the distribution using a collection of predictors and special form of regression

## Modelling the probability of an event

Outcome Yi takes value 1 with probability Pi, and a value 0 with probability 1 - Pi.

Each observation has a different context, so Pi will differ for each observation.

Ultimately, the probability you want to model is in relation to the predictor variables.

![Logistic%20Regression%20aka%20GLM%20aka%20Logit%20ff9c4817d4d444dfa8db9587efed44f4/Untitled%201.png](Logistic%20Regression%20aka%20GLM%20aka%20Logit%20ff9c4817d4d444dfa8db9587efed44f4/Untitled%201.png)

Logistic regression model relates to the probability of an event (pi) to the predictors x1, x2 etc. through a framework like multiple regression:

![Logistic%20Regression%20aka%20GLM%20aka%20Logit%20ff9c4817d4d444dfa8db9587efed44f4/Untitled%202.png](Logistic%20Regression%20aka%20GLM%20aka%20Logit%20ff9c4817d4d444dfa8db9587efed44f4/Untitled%202.png)

We want to choose a transformation in the equation that makes practical and mathematical sense.

- For example, we want a transformation that makes the range of possibilities on the left hand side of the equation equal to the range of possibilities for the right hand side; if there was no transformation for this equation, the left hand side could only take values between 0 and 1, but the right hand side could take values outside of this range.

## **Logit transformation**

A logit model is simply a style of model that takes some value and outputs a percentage chance of some event between 1 and 0.

![Logistic%20Regression%20aka%20GLM%20aka%20Logit%20ff9c4817d4d444dfa8db9587efed44f4/Untitled%203.png](Logistic%20Regression%20aka%20GLM%20aka%20Logit%20ff9c4817d4d444dfa8db9587efed44f4/Untitled%203.png)

![Logistic%20Regression%20aka%20GLM%20aka%20Logit%20ff9c4817d4d444dfa8db9587efed44f4/Untitled%204.png](Logistic%20Regression%20aka%20GLM%20aka%20Logit%20ff9c4817d4d444dfa8db9587efed44f4/Untitled%204.png)

**Example:**  

Given: 

![Logistic%20Regression%20aka%20GLM%20aka%20Logit%20ff9c4817d4d444dfa8db9587efed44f4/Untitled%205.png](Logistic%20Regression%20aka%20GLM%20aka%20Logit%20ff9c4817d4d444dfa8db9587efed44f4/Untitled%205.png)

Where outcome variable is 1 if possum is from Victoria else 0.

The logit transformation looks like:

![Logistic%20Regression%20aka%20GLM%20aka%20Logit%20ff9c4817d4d444dfa8db9587efed44f4/Untitled%206.png](Logistic%20Regression%20aka%20GLM%20aka%20Logit%20ff9c4817d4d444dfa8db9587efed44f4/Untitled%206.png)

= 33.5095 − 1.4207×sex male i −0.2787×skull width i +0.5687× total length i − 1.8057 × tail length i

### Difference between Multivariate and Multivariable Regresison

[https://academic.oup.com/ntr/advance-article/doi/10.1093/ntr/ntaa055/5812038](https://academic.oup.com/ntr/advance-article/doi/10.1093/ntr/ntaa055/5812038)

## Akaike Information Criterion

Help trim variables from the model