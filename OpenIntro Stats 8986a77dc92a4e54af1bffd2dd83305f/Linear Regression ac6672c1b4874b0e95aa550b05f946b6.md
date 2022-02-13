# Linear Regression

Two variables who's relationship can be modelled with a straight line is called a perfect linear relationship. 

Linear regression is the statistical method for fitting a line to data where the relationship between two variables, x and y, can be modelled by a straight line with some error:

$y = β_0 + β_1 x + ε$

where B0 and b1 is the model's parameters and epsilon is error. These are estimated by using data and when we use x to predict y, x is the predictor variable.

Y is the response. It can be a hat to signify that it's an estimate

You can drop epsilon to predict the average outcome.

## Residuals

Leftover variation in the data after accounting for a model fit
Data = Fit + Residual 

If an observation is above the regression line, it's residual is positive (vertical distance from line) else negative if below.

Residuals are calculated as observed vs predicted

You want the residuals to be as small as possible when fitting a model

![Linear%20Regression%20ac6672c1b4874b0e95aa550b05f946b6/Untitled.png](Linear%20Regression%20ac6672c1b4874b0e95aa550b05f946b6/Untitled.png)

You can plot out residuals in a residual plot and the regression line is horizontal.

## Correlation

![Linear%20Regression%20ac6672c1b4874b0e95aa550b05f946b6/Untitled%201.png](Linear%20Regression%20ac6672c1b4874b0e95aa550b05f946b6/Untitled%201.png)

![Linear%20Regression%20ac6672c1b4874b0e95aa550b05f946b6/Untitled%202.png](Linear%20Regression%20ac6672c1b4874b0e95aa550b05f946b6/Untitled%202.png)

where $x̄, ȳ, s_x, s_y$ are sample means and standard deviations for each variable

Correlations are for quantifying the strength of a linear trend

Negative R = negative linear relationship

As R tends to 0, this means non linear relationship

As R tends to 1, stronger trend 

Correlation has no units! 

[Least Squares Regression](Linear%20Regression%20ac6672c1b4874b0e95aa550b05f946b6/Least%20Squares%20Regression%2083e68e0fe29e48939017b864fda1fab2.md)

[Outliers in Linear Regression](Linear%20Regression%20ac6672c1b4874b0e95aa550b05f946b6/Outliers%20in%20Linear%20Regression%209eebe061ade04fc6bc7535ddc7ae4c34.md)

[Inference for Linear Regression](Linear%20Regression%20ac6672c1b4874b0e95aa550b05f946b6/Inference%20for%20Linear%20Regression%200e47f54a34bf47a5ad71a010f2ab5f28.md)