# Check model conditions

![Check%20model%20conditions%2079e92fec367846d2bccde862c752b1c8/Untitled.png](Check%20model%20conditions%2079e92fec367846d2bccde862c752b1c8/Untitled.png)

## Diagnostic Plots

Check each condition. 

- **Check for outliers**
    - In theory, residuals should be nearly normal.
    - If we want to construct a prediction interval for future observation, then you gotta be strict and require residuals to be nearly normal
    
    ![Check%20model%20conditions%2079e92fec367846d2bccde862c752b1c8/Untitled%201.png](Check%20model%20conditions%2079e92fec367846d2bccde862c752b1c8/Untitled%201.png)
    
- **Absolute values of residuals against fitted values**
    - A plot of absolute value of the residuals against corresponding fitted values (y^i)
    - Checks conditions that the variance of the residuals is approximately constant, and a smooth plot line shows the approximate trend of the plot
    - Does it follow the constant variance assumption

![Check%20model%20conditions%2079e92fec367846d2bccde862c752b1c8/Untitled%202.png](Check%20model%20conditions%2079e92fec367846d2bccde862c752b1c8/Untitled%202.png)

- **Residuals in order of their data collection**
    - Type of plot is useful when observations are collected in a sequence like a time series
    - Plot identifies connection between cases next to each other.
    - Time series methods may be useful
- **Residuals against each predictor variable**
    - Consider a plot of the residuals against each of the predictors
    - For 2-3 groups, box plots are shown
    - For numerical outcomes. a smooth line can be fit to date to help with a review.
    - Looking for change in variability between groups or patterns in data.
    - Does show some pattern for this check, time series methods may be useful.
    - Check if there are minor differences between groups
    - Check the skew
    - Check the curve to see if there are minor mis-fittings
    
    Having reviewed the diagnostic plots, there are two options. The first option is to, if we’re not concerned about the issues observed, use this as the final model; if going this route, it is important to still note any abnormalities observed in the diagnostics. 
    
    The second option is to try to improve the model, which is what we’ll try to do with this particular model fit
    
    **Options for improving the model fit** 
    
    - Transforming variables
        - Log transformation
        - Square root transform
        - Inverse transform
        - Truncations (cap the max value)
    - Seeking out additional variables to fill model gaps
    - Can account for inconsistent variability or non-linear relationships between predictors and outcomes.
    
    The truth is that no model is perfect. However, even imperfect models can be useful. 
    
    Reporting a flawed model can be reasonable so long as we are clear and report the model’s shortcomings
    
    If model conditions are violated, make a new one.