# Least Squares Regression

Ideally, you want the lowest residuals in your line plot, so... choose a line which minimizes the sum of the squared residuals.

![Least%20Squares%20Regression%2083e68e0fe29e48939017b864fda1fab2/Untitled.png](Least%20Squares%20Regression%2083e68e0fe29e48939017b864fda1fab2/Untitled.png)

The line which minimizes this least squares criterion is called the least squares line,

**Why?**

1. Most commonly used method 
2. A residual twice as large as another residual is twice as bad so squaring them accounts for discrepancy.

## Conditions

1. Linearity. Data must show a linear trend
2. Nearly normal residuals. If unreasonable, due to outliers or concerns for influential points.
3. Constant Variability. Variability around the line remains constant. This happens is the variability of y when x is larger 
4. Independent Observations → be careful around time series data.

![Least%20Squares%20Regression%2083e68e0fe29e48939017b864fda1fab2/Untitled%201.png](Least%20Squares%20Regression%2083e68e0fe29e48939017b864fda1fab2/Untitled%201.png)

## Finding the Least Squares Line

- Slope of least squares line is given by:

![Least%20Squares%20Regression%2083e68e0fe29e48939017b864fda1fab2/Untitled%202.png](Least%20Squares%20Regression%2083e68e0fe29e48939017b864fda1fab2/Untitled%202.png)

Where R is the correlation of the two variables, and Sx and Sy are the standard deviations of the samples of the explanatory variable and response.

If x̄ is the sample mean of the explanatory variable and ȳ is the sample mean of the vertical variable, then the point (x̄, ȳ) is on the least squares line

![Least%20Squares%20Regression%2083e68e0fe29e48939017b864fda1fab2/Untitled%203.png](Least%20Squares%20Regression%2083e68e0fe29e48939017b864fda1fab2/Untitled%203.png)

The slope describes the estimated difference in the y variable if the explanatory variable x for a case happened to be one unit larger. 

The intercept describes the average outcome of y if x = 0 and the linear model is valid all the way to x = 0, which in many applications is not the case

## $R^2$ - strength of a fit

The strength is given by R-squared.

Describes the amount of variation in response that is explained by the least squares line.

Aka - R2 explains X% of variability of results due to explanatory variabl

## Categorical Predictors with 2 Levels

Predict outcomes.

1. Convert categories to a numerical form.
    1. This is called the indicator variable