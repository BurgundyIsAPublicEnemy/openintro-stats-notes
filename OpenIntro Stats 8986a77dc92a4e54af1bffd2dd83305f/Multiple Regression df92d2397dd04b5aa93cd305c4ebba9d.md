# Multiple Regression

1 response but many predictors (denoted by $x_1,x_2 ... x_n$)

Used in scenarios where many variables are connected to an output

- If using a categorical variable, can substitute with an indicator variable
- When fitting a regression model with a categorical variable that has K levels where k > 2, you work out a coefficient for k-1 of those levels.
- Reference level is the last level which doesn't get a coefficient and all other levels are considered relative to the reference level.

![Multiple%20Regression%20df92d2397dd04b5aa93cd305c4ebba9d/Untitled.png](Multiple%20Regression%20df92d2397dd04b5aa93cd305c4ebba9d/Untitled.png)

Parameters are denoted by βx

Remember: β0 is given by intercept estimate, and the slope for the different variables give the other βx

They are estimated by minimizing the size of error e.g. sum of the squared residuals 

![Multiple%20Regression%20df92d2397dd04b5aa93cd305c4ebba9d/Untitled%201.png](Multiple%20Regression%20df92d2397dd04b5aa93cd305c4ebba9d/Untitled%201.png)

Yi and Y^i represent observed value and estimated values

![Multiple%20Regression%20df92d2397dd04b5aa93cd305c4ebba9d/Untitled%202.png](Multiple%20Regression%20df92d2397dd04b5aa93cd305c4ebba9d/Untitled%202.png)

## R2 for Multiple Regression

(1) R2 gives amount of variability that was explained by the model 

![Multiple%20Regression%20df92d2397dd04b5aa93cd305c4ebba9d/Untitled%203.png](Multiple%20Regression%20df92d2397dd04b5aa93cd305c4ebba9d/Untitled%203.png)

Where $e_i$ represents the residuals of the model and $y_i$ the outcomes. 

We can do better!

(2) R2 works well with one variable. So...

![Multiple%20Regression%20df92d2397dd04b5aa93cd305c4ebba9d/Untitled%204.png](Multiple%20Regression%20df92d2397dd04b5aa93cd305c4ebba9d/Untitled%204.png)

- K is not negative and Adjusted R2 will be smaller
- Degrees of freedom associated with each variance, equal to (n - k - 1)
- Adjusted R2 is slightly overoptimistic

[Model Selection](Multiple%20Regression%20df92d2397dd04b5aa93cd305c4ebba9d/Model%20Selection%2074a867f7b1404bffb49265b994cf611a.md)

[Check model conditions ](Multiple%20Regression%20df92d2397dd04b5aa93cd305c4ebba9d/Check%20model%20conditions%2079e92fec367846d2bccde862c752b1c8.md)

[Logistic Regression aka GLM aka Logit](Multiple%20Regression%20df92d2397dd04b5aa93cd305c4ebba9d/Logistic%20Regression%20aka%20GLM%20aka%20Logit%20ff9c4817d4d444dfa8db9587efed44f4.md)