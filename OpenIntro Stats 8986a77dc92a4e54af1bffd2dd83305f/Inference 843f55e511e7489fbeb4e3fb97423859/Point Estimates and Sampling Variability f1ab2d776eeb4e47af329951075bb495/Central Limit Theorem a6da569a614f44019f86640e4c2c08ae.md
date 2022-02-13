# Central Limit Theorem

When observations are independent and the sample size is sufficiently large, sample proportion p-hat will tend to follow a normal distribution with the following mean and standard error:

![Central%20Limit%20Theorem%20a6da569a614f44019f86640e4c2c08ae/Untitled.png](Central%20Limit%20Theorem%20a6da569a614f44019f86640e4c2c08ae/Untitled.png)

In order for CLT to hold:

- Sample size must be sufficiently large when **np ≥ 10 and n(1 - p) ≥ 10** (success-failure condition)
    - Given a p = 0.88 and n = 1000... np = 1000 x 0.88 ≥ 10 and (1000 *(1-0.88)) ≥ 10 therefore, CTL applies
- All observations must be independent
    - Easiest way to do this is from a simple random sample
- Samples from a population must no larger than 10% of the population as we tend to overestimate the sampling error else results tend to be conservative.
    - If sample is larger, we can use a finite population correction finder:
        - Given a sample size n and population size , multiply the standard error formula by $sqrt(N-n/ N-1)$ to find a more precise estimate of the actual standard error. When n < 0.1 x N, then correction factor is small.
        - Larger sample reduces the margin of error
        - Margin of error is given by z*SEp
        

SEp follows the plug-in principle and is robust enough for change to not be detected when using only 3dp. This means it's relatively stable when observing slightly different proportions from one sample to another.

- Standard error describes the uncertainty in the overall estimate from natural fluctuations due to randomness, not the uncertainty corresponding to individuals’ responses.
- In the calculation of the standard error, we divide the standard deviation by the square root of the sample size.
    - To cut the SE (or margin of error) in half, we
    would need to sample 2 2 = 4 times the number of
    people in the initial sample.

When np or n(1-p) is small, distribution is more discrete, the skew is more noteworthy 

The larger, the more normal the distribution and discreteness is less evident 

- If it isn't met, simulate null distribution of p-hat using the null value p0
- For the confidence interval, use Clopper-Pearson interval