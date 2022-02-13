# Testing differences in population proportions

1. Identify a point estimate of p1 - p2 based on the sample
2. Guess p1-hat - p2-hat

Can be modelled using a normal distribution when certain conditions are met 

- Success failure condition must be met by both groups

![Testing%20differences%20in%20population%20proportions%2076c9bbc7347340738bc221ddfc5aa04f/Untitled.png](Testing%20differences%20in%20population%20proportions%2076c9bbc7347340738bc221ddfc5aa04f/Untitled.png)

Standard error = variance of estimate.

If X and Y are random variables with variances, X - Y is calculated by adding variance. Therefore, we add them here.

Confidence Intervals is given by:

![Testing%20differences%20in%20population%20proportions%2076c9bbc7347340738bc221ddfc5aa04f/Untitled%201.png](Testing%20differences%20in%20population%20proportions%2076c9bbc7347340738bc221ddfc5aa04f/Untitled%201.png)

`**When Null Hypothesis is 0... (p1 = p2) aka no difference between two populations...**

![Testing%20differences%20in%20population%20proportions%2076c9bbc7347340738bc221ddfc5aa04f/Untitled%202.png](Testing%20differences%20in%20population%20proportions%2076c9bbc7347340738bc221ddfc5aa04f/Untitled%202.png)

If it isn't 0... the null hypothesis wants to know if there is a difference, use p1-hat / p2-hat to check the success-failure condition and construct standard error.

If null hypothesis wants a difference, use sample proportion 

If you need to compare difference between two populations:
1. H0 and HA set up. H0 can be no difference between them. Pick a p value to reject or accept

2. Get p1, p2 and n1, n2

3. Calculate SE

4. Calculate Ppooled

5. Use Ppooled in : Z = Point Estimate - Null Value / SE 

6. And convert Z into a p-score to test the hypothesis