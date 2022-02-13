# Model Selection

The best model might not be the most complicated

- Don't include variables that aren't important to the accuracy of predictions
- Models which have variable pruning are parsimonious
- All explanatory variables are called full models.

## How to know which variables in a model are not helpful

Adjusted R2 describes the strength of the model fit and can be used to evaluate which variables improve the fit.

### Step-wise model selections

Add / delete one variable at a time as you step through candidate predictors

### Backward Elimination

Start off with model that includes all potential predictor variables. Eliminate variables one-at-a-time until you cannot improve adjusted R2

Strategy within each elimination step is to eliminate the variable that leads to the largest improvement in adjusted R2

### Forward Selection

The forward selection strategy is the reverse of the backward elimination technique. Instead of eliminating variables one-at-a-time, we add variables one-at-a-time until we cannot find any variables that improve the model (as measured by adjusted R2)

- Remove the ones with the highest adj R2
- Add the ones with highest R2 adjusted

You can use the P-value approach as well

- For backward elimination, identify the predictor corresponding to the largest p-value
    - P-Value > a (0.05), drop the variable, refit the model and repeat the process.
    - If P-Value < 0.05, do not eliminate
- For forward elimination, reverse the process. If p-value is smaller than 0.05, then add it to the model, repeat etc. until p-value > 0.05

If the sole goal is to improve prediction accuracy, use Adjusted R2.

If we care about understanding which variables are statistically significant predictors of a response or interest in producing simple models at the cost of accuracy, use p-value