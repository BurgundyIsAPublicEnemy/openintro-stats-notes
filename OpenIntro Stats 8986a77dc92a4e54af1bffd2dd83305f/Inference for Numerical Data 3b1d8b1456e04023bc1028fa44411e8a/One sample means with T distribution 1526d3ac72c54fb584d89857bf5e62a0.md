# One sample means with T distribution

Sample mean x̄ can be modelled using a normal distribution when certain conditions are met.

- This is called the t-distribution and used with sample mean .

Condition 1: Independence. Sample observations must be independent i.e. sample is a simple random sample from population

Condition 2: Normality. When sample is small, sample observations must come from a normally distributed population. This can be relaxed for larger sample sizes.

- If n < 30 with no clear outliers, assume data comes from a nearly normal distribution to satisfy the condition
- N ≥ 30 with no extreme outliers, assume sampling distribution of x̄ is nearly normal, even if underlying distribution of individual observations isn't

The sample mean tends to follow a normal distribution centred at the population mean, u when certain conditions are met:

- With large sample of n independent observations from a population with a mean u and a standard deviation o, the sampling distribution of x̄ will be nearly normal with:
    - **Mean = u**
    - **Standard error = o / sqrt(n)**
        - As standard deviation is rarely known, this must be estimated, where t-distribution comes in
        - Whereas when working this out with proportion, use a sample value in place of the population value when computing standard error.
        - Reminder: we substitute it for the sample standard deviation s in place of o:

![One%20sample%20means%20with%20T%20distribution%201526d3ac72c54fb584d89857bf5e62a0/Untitled.png](One%20sample%20means%20with%20T%20distribution%201526d3ac72c54fb584d89857bf5e62a0/Untitled.png)

Works great when you got a lot of data and can estimate o using s accurately. 

So... 

**T-Distribution!**

![One%20sample%20means%20with%20T%20distribution%201526d3ac72c54fb584d89857bf5e62a0/Untitled%201.png](One%20sample%20means%20with%20T%20distribution%201526d3ac72c54fb584d89857bf5e62a0/Untitled%201.png)

- Tails are thicker than normal distributions → observations are more likely to fall beyond 2 SDs from the mean than a normal one.
- Always centred at 0 and one parameter: degree of freedom
- General form is give by df = n - 1 to model the sample mean when the sample size is n.
    - More samples means DOF is larger and looks closer to a normal distribution.
    - When DOF ≥ 30, t-distribution is nearly the same as a normal distribution
    - To find the critical T-value for the given sample size, get the significant level by (1 - confidence level) / 2 and use this calculator [https://calculators.io/t-value-calculator/](https://calculators.io/t-value-calculator/)
    - To find the P-value for accepting / rejecting the null, use this [https://www.socscistatistics.com/pvalues/tdistribution.aspx](https://www.socscistatistics.com/pvalues/tdistribution.aspx)
    - The Margin Of Error is half the critical interval ([https://en.wikipedia.org/wiki/Margin_of_error](https://en.wikipedia.org/wiki/Margin_of_error))
    - Margin of Error is also given by Critical Value * SE
    - T statistic can be found by [http://www.learningaboutelectronics.com/Articles/Test-statistic-calculator.php#answer](http://www.learningaboutelectronics.com/Articles/Test-statistic-calculator.php#answer)

**So you established the conditions!**

![One%20sample%20means%20with%20T%20distribution%201526d3ac72c54fb584d89857bf5e62a0/Untitled%202.png](One%20sample%20means%20with%20T%20distribution%201526d3ac72c54fb584d89857bf5e62a0/Untitled%202.png)

In summary....

![One%20sample%20means%20with%20T%20distribution%201526d3ac72c54fb584d89857bf5e62a0/Untitled%203.png](One%20sample%20means%20with%20T%20distribution%201526d3ac72c54fb584d89857bf5e62a0/Untitled%203.png)

**One sample T-tests**

1. Come up with a hypothesis 
2. Pretty much the same as a hypothesis for a single proportion except use a T-distribution to find a T-score for tail area.
3. P-value is given by finding the one tail area under the sampling distribution and doubling it

![One%20sample%20means%20with%20T%20distribution%201526d3ac72c54fb584d89857bf5e62a0/Untitled%204.png](One%20sample%20means%20with%20T%20distribution%201526d3ac72c54fb584d89857bf5e62a0/Untitled%204.png)

[T-Value](One%20sample%20means%20with%20T%20distribution%201526d3ac72c54fb584d89857bf5e62a0/T-Value%20120c6c6557224cd2a6a7720d0974f991.md)