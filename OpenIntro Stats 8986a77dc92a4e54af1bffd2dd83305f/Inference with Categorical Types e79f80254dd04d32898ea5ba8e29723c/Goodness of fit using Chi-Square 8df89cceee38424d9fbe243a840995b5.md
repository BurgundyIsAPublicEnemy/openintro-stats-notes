# Goodness of fit using Chi-Square

[https://www.simplypsychology.org/chi-square.html](https://www.simplypsychology.org/chi-square.html)

Used when data is binned:

- Given a sample of cases that can be classified into several groups, determine if sample is representative of general population
- Evaluate whether data resembles a particular distribution

1. Create a test statistic for one way tables.
    1. Create two hypotheses as normal (null and alternative) concerning sample
2. Consider the following test statistic:

![Goodness%20of%20fit%20using%20Chi-Square%208df89cceee38424d9fbe243a840995b5/Untitled.png](Goodness%20of%20fit%20using%20Chi-Square%208df89cceee38424d9fbe243a840995b5/Untitled.png)

- Made by identifying the difference between a point estimate and the expected value if the null hypothesis is true
- Point estimate can be the observed count,
- Standardizing the difference using the Standard Error of point estimate.

![Goodness%20of%20fit%20using%20Chi-Square%208df89cceee38424d9fbe243a840995b5/Untitled%201.png](Goodness%20of%20fit%20using%20Chi-Square%208df89cceee38424d9fbe243a840995b5/Untitled%201.png)

3. This gives a Z score. You do this for every bin, square them, and add them up.

- This makes standardized differences positive
- Unusual differences are smaller.

4. This is referred to $X^2$

Follows a Chi-Square distribution.

- Right skew
- Always positive
- One parameter: degree of freedom (controls shape, centre, spread of distribution)

![Goodness%20of%20fit%20using%20Chi-Square%208df89cceee38424d9fbe243a840995b5/Untitled%202.png](Goodness%20of%20fit%20using%20Chi-Square%208df89cceee38424d9fbe243a840995b5/Untitled%202.png)

Finding the area in the tail of the distribution gives p-value.

If P1 = P2, then follows Chi distribution 

![Goodness%20of%20fit%20using%20Chi-Square%208df89cceee38424d9fbe243a840995b5/Untitled%203.png](Goodness%20of%20fit%20using%20Chi-Square%208df89cceee38424d9fbe243a840995b5/Untitled%203.png)

- If table has just two bins, pick a single bin, use one-proportion method'

X2 ⇒ P

[https://www.gigacalculator.com/calculators/chi-square-to-p-value-calculator.php](https://www.gigacalculator.com/calculators/chi-square-to-p-value-calculator.php)