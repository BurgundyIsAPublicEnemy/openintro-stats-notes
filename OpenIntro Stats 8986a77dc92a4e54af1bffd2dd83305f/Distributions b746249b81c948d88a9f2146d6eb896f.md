# Distributions

A function that shows the possible values for a variable and how often they occur. If we plot the probability of the values, we get a distribution.

## Normal Distribution

![Distributions%20b746249b81c948d88a9f2146d6eb896f/Untitled.png](Distributions%20b746249b81c948d88a9f2146d6eb896f/Untitled.png)

Most common occurring one (for example, IQ scores or heights of US adult males)

- Always describes a symmetric, unimodal, bell-shaped curve.
- Parameters: can adjusted using mean and standard deviation.
    - Std Deviation stretches or constricts curve.
    - Mean shifts whether bell curve moves left or right
- Normal distributions has mean μ and standard deviation σ, can be written as *N* (μ, σ)
- When  mean μ = 0 and standard deviation σ = 1, this is standard normal distribution

## Standardizing with Z Scores

Makes comparisons more reasonable. 

Best employed for nearly normal observations but that may be used with any distribution.

- Even ones that are not nearly normal

The Z-score of an observation is defined as the number of standard deviations it falls above or below the mean.

$Z = (x - μ) / σ$

- Used to identify which observations are more unusual than others.
    - An observation x1 is said to be more unusual than another observation x2 if the absolute value of its Z-score is larger than the absolute value of the other observation’s Z-score: |Z1| > |Z2 |.
- Observations above mean have positive Z scores
- Those below the mean are negative
- Equal to mean gives a value of 0

### Tail area

Area under curve shows fraction of sample with that case.

The total area adds up to 1

Done using statistical software or a calculator or Normal Probability Table

### Normal Probability table

Used to find percentiles of normal distribution using a Z-Score

![Distributions%20b746249b81c948d88a9f2146d6eb896f/Untitled%201.png](Distributions%20b746249b81c948d88a9f2146d6eb896f/Untitled%201.png)

![Distributions%20b746249b81c948d88a9f2146d6eb896f/Untitled%202.png](Distributions%20b746249b81c948d88a9f2146d6eb896f/Untitled%202.png)

![Distributions%20b746249b81c948d88a9f2146d6eb896f/Untitled%203.png](Distributions%20b746249b81c948d88a9f2146d6eb896f/Untitled%203.png)

This is because is the Z score is 1, it's 1.00 therefore, row is 1.0 and column is 0.00

## 68-95-99.7 Rule

![Distributions%20b746249b81c948d88a9f2146d6eb896f/Untitled%204.png](Distributions%20b746249b81c948d88a9f2146d6eb896f/Untitled%204.png)

This means 

68% of observations fall within 1 standard deviation (0.8413 - 0.1587 = 0.6826)

95% with 2 sds, and 99.7 within 3 sds.

When the Z score is an absolute aka |Z|, it means it wants the probability from both sides like |Z| < 2 is:

![Distributions%20b746249b81c948d88a9f2146d6eb896f/Untitled%205.png](Distributions%20b746249b81c948d88a9f2146d6eb896f/Untitled%205.png)

[Geometric Distribution / Bernoulli](Distributions%20b746249b81c948d88a9f2146d6eb896f/Geometric%20Distribution%20Bernoulli%20369424dd6994419f9dd3cc62d1170f9f.md)

[Binomial Distribution](Distributions%20b746249b81c948d88a9f2146d6eb896f/Binomial%20Distribution%203ce80ef66c8942c8a9941f45194684e1.md)

[Negative binomial distribution](Distributions%20b746249b81c948d88a9f2146d6eb896f/Negative%20binomial%20distribution%2090d81815582d44778049f7c1da5fc9a5.md)

[Poisson Distribution](Distributions%20b746249b81c948d88a9f2146d6eb896f/Poisson%20Distribution%200f6ec7bbe792401f84876bcecc17d3c7.md)

[Binomial coefficients](Distributions%20b746249b81c948d88a9f2146d6eb896f/Binomial%20coefficients%2067e89180e8974cc3b58182b987ee985d.md)

[Continuous Uniform Distribution  ](Distributions%20b746249b81c948d88a9f2146d6eb896f/Continuous%20Uniform%20Distribution%203cdda4febaab44edb6dcfa7ffb57f328.md)

[Discrete Uniform Distribution](Distributions%20b746249b81c948d88a9f2146d6eb896f/Discrete%20Uniform%20Distribution%203a4c0b07885041c9be1a0c76312e33e4.md)