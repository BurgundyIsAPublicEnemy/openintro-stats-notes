# Hypothesis testing for a proportion

There are two hypothesis: null hypothesis (H0 and an alternative one (Ha)

Always play the sceptic 

Null hypothesis is sceptical of the claim to be tested

- Perspective of no difference
- Where H0 : p = 0.5 (for example, 0.5 is no difference though)

Alternative hypothesis represents an alternative claim under consideration and is represented by a range of possible parameter values.

- New perspective and should reference the null value
- Where HA : p =/= 0.5

We mathematically represent hypothesis as such: Ha : p = X where X is the proportion p of the ppt. who pick any chosen outcome.

We want to make a conclusion about the population parameter p. The value we are comparing the parameter is called the null value.

You can use confidence intervals to accept a hypothesis for an X% confidence within a given range of p

In many statistical explanations, we use double negatives. For instance, we might say that the
null hypothesis is not implausible or we failed to reject the null hypothesis. Double negatives
are used to communicate that while we are not rejecting a position, we are also not saying it is
correct.

**Decision Errors:**

![Hypothesis%20testing%20for%20a%20proportion%202a599481a79c46db814a9fe5578e2fbd/Untitled.png](Hypothesis%20testing%20for%20a%20proportion%202a599481a79c46db814a9fe5578e2fbd/Untitled.png)

**P-Value**

The p-value is the probability of observing data at least as favourable to the alternative hypothesis as our current data set, if the null hypothesis were true. 

We typically use a summary statistic of the data, in this section the sample proportion, to help compute the p-value and evaluate the hypotheses.

When using the p-value method to evaluate a hypothesis test:

1. Check the conditions for p̂ and construct the standard error using the null value, p0 , instead of using the sample proportion.
2. In a hypothesis test with a p-value, we are supposing the null hypothesis is true, which is a
different mindset than when we compute a confidence interval. 

This is why we use p 0 instead of p̂ when we check conditions and compute the standard error in this context.

![Hypothesis%20testing%20for%20a%20proportion%202a599481a79c46db814a9fe5578e2fbd/Untitled%201.png](Hypothesis%20testing%20for%20a%20proportion%202a599481a79c46db814a9fe5578e2fbd/Untitled%201.png)

The Z score is given by $(p-hat) -p /SE_p$ for a one tailed area
You have to multiply by 2 to get the P-value which you can compare back to a 

If less than a, reject null hypothesis 

**Significance Level**

Choosing a significance level for a test is important in many contexts, and the traditional level
is α = 0.05.

- If making a Type 1 Error is dangerous or especially costly, we should choose a small significance level (e.g. 0.01).
    - Under this scenario we want to be very cautious about rejecting the null hypothesis, so we demand very strong evidence favouring Ha before we would reject H0.
- If a Type 2 Error is relatively more dangerous or much more costly than a Type 1 Error, then
we might choose a higher significance level (e.g. 0.10).
    - Here we want to be cautious about failing to reject H 0 when the alternative hypothesis is actually true.

First talk to experts / scientific literature to learn what is the smallest meaningful difference from a null value.

Then suggest a sample size large enough that if there is a meaningful difference, it can be detected 

When sample size becomes larger, point estimates become more precise and any real differences in the mean and null value become easier to detect and recognize. 

**One-sided hypothesis tests**

Two sided hypothesis tests are where we care about detecting whether p is either above or below some null value p0

One sided tests take either one of two forms:

- Value in detecting if the population parameter is less than some value Po. In this case, alternative hypothesis is written as p < po for some null value p0
- Only value in detecting if the population parameter is more than some value p0: in this case, alternative hypothesis is p > p0

We compute the p-value as the tail area in the direction of the alternative hypothesis only, meaning it is represented by a single tail area.

If we don’t have to double the tail area to get the p-value, then the p-value
is smaller and the level of evidence required to identify an interesting finding in the direction of the
alternative hypothesis goes down.