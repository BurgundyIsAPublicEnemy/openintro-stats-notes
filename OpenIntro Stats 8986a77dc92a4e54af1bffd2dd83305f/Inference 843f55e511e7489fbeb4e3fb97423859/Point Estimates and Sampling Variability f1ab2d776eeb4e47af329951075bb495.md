# Point Estimates and Sampling Variability

This framework follows a single proportion context

## Point Estimates and Error

If a study with a sample says something is true for 50%, then consider the 50% to be a **point estimate** of the variable we are testing in the study for the entire population

The entire population response proportion is known as the parameter of interest, denoted as P
Sample proportion denoted as p-hat

Unless we collect samples from everyone in the population, p will be unknown and we must use p-hat as our estimate. The difference we observe is called **the standard error in the estimate.**

**Sampling Error / Bias**

- **Sampling error / uncertainty** describes how much an estimate will vary from one sample to the next.
    - Sample size is represented by n
- **Bias** is a systematic tendency to over/under estimate the true population value.
    - We want to minimize this
    

**Example**:
Given the proportion of men who support solar power is p = 0.88 (parameter of interest)

We want to know how the sample proportion behaves when the true population proportion is 088

1. Simulate responses we would get from a simple random sample of N people.
- *Assume p = p-hat*
- *Given there are 250 million Americans, write support on 88% of them and not for the 12%*
- *Mix the papers up and pull out N sample*
- *Compute fraction of sample to say support.*
- *Calculate point estimate of sample (p1-hat)*
- *Error is p - p1-hat*

Run the simulation a lot more times and take the distribution of sample proportions. This is the **sampling distribution**. 

## Sampling Distribution

You can make a histogram out of this!

![Untitled](Point%20Estimates%20and%20Sampling%20Variability%20f1ab2d776eeb4e47af329951075bb495/Untitled.png)

- Center - The centre of the distribution should be the same as the population proportion p. By mimicking a simple random sample of the population, this avoids sampling bias.
    - Sampling distribution of p-hat is always centred at population parameter p, it means p-hat is unbiased when taken from independent samples from population.
- Spread - standard deviation of the distribution. When talking about sampling distribution, use the term standard error (SEp)
- Shape - Is it normal?

To know if a sampling distribution has skew, test for its **success-failure criteria** 

The variability in the sampling distribution decreases as sample size n becomes larger.

The variability will be the largest if p = 0.5 

It helps to imagine point estimates as coming from hypothetical distributions to help characterize them. 

[Central Limit Theorem](Point%20Estimates%20and%20Sampling%20Variability%20f1ab2d776eeb4e47af329951075bb495/Central%20Limit%20Theorem%20a6da569a614f44019f86640e4c2c08ae.md)

[Sampling Distribution](Point%20Estimates%20and%20Sampling%20Variability%20f1ab2d776eeb4e47af329951075bb495/Sampling%20Distribution%202f90edc7bce147c6a55d27dbce35d8cd.md)