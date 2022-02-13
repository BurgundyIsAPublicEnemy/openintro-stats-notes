# Inference for a single proportion

## Telling if a sample proportion is nearly normal

Sample p-hat based on sample size n from population with a true proportion p is nearly normal when: 

- Sample's observations are independent
- Can expect to see at least 10 successes and failures in the sample (np ≥ 10 and n(1 − p) ≥ 10) → Success-Failure condition

![Inference%20for%20a%20single%20proportion%2002b81004253b4598891699ed32b02cce/Untitled.png](Inference%20for%20a%20single%20proportion%2002b81004253b4598891699ed32b02cce/Untitled.png)

We don't know true p so substitute values to check conditions and estimate the standard error. 

For confidence intervals, sample proportion p-hat checks success-failure condition and computes standard error.

For a hypothesis test, the null value (proportion claimed in null hypothesis) is used in place of p 

Plot the sampling distribution to know how the skew looks

- If SF fails, you can assume p^ is similar to the true population population proportion.

## Confidence Intervals for Proportion

A confidence interval provides a range of plausible values for the parameter p, and when p̂ can be modeled using a normal distribution, the confidence interval for p takes the form p̂ ± z x SE

Margin of error is given by z x SE

![Inference%20for%20a%20single%20proportion%2002b81004253b4598891699ed32b02cce/Untitled%201.png](Inference%20for%20a%20single%20proportion%2002b81004253b4598891699ed32b02cce/Untitled%201.png)

![Inference%20for%20a%20single%20proportion%2002b81004253b4598891699ed32b02cce/Untitled%202.png](Inference%20for%20a%20single%20proportion%2002b81004253b4598891699ed32b02cce/Untitled%202.png)

When the success-failure condition isn’t met for a hypothesis test, we can simulate the null distribution of p̂ using the null value, p 0 .

For a confidence interval when the success-failure condition isn’t met, we can use what’s called the Clopper-Pearson interval.

## Choosing a sample size when estimating a proportion

Pick one big enough to make margin of error small enough to make sample useful

![Inference%20for%20a%20single%20proportion%2002b81004253b4598891699ed32b02cce/Untitled%203.png](Inference%20for%20a%20single%20proportion%2002b81004253b4598891699ed32b02cce/Untitled%203.png)

If you double the sample size, it reduces the SE by a factor of 1 / sqrt(2)