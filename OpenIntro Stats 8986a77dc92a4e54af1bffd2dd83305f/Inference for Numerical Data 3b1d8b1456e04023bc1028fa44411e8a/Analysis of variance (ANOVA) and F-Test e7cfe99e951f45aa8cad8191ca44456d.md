# Analysis of variance (ANOVA) and F-Test

Is the variability in the sample means so large that it seems unlikely to be from chance alone?

Consider many groups simultaneously and evaluate whether their sample means differ more than expected from natural variation.

Variability is called the mean square between groups (MSG) and has an associated degrees of freedom: dfG = k - 1 with k groups

MSG is a scaled variance formula for means

If null hypothesis is true, any variation in the sample means is due to chance and shouldn't be too large.

The mean square is compared to a benchmark value for how much variability should be expected among the sample means if the null hypothesis is true.

- Compute a pooled variance estimate (MSE)
- MSE Is the variability within the groups
- When null hypothesis is true, any differences among the sample means are due to chance and MSG and MSE are roughly equal.
- ANOVA, F = MSG / MSE where the MSG represents a measure of the between-group variability, and MSE measures the variability
within each of the group
    - Conditions need to be met:
        - Independence
        - Approximately normal
        - Constant variance → variance in the groups is equal from one group to another

![Analysis%20of%20variance%20(ANOVA)%20and%20F-Test%20e7cfe99e951f45aa8cad8191ca44456d/Untitled.png](Analysis%20of%20variance%20(ANOVA)%20and%20F-Test%20e7cfe99e951f45aa8cad8191ca44456d/Untitled.png)

If you reject the null hypothesis in ANOVA, which of the groups have a different mean? 

![Analysis%20of%20variance%20(ANOVA)%20and%20F-Test%20e7cfe99e951f45aa8cad8191ca44456d/Untitled%201.png](Analysis%20of%20variance%20(ANOVA)%20and%20F-Test%20e7cfe99e951f45aa8cad8191ca44456d/Untitled%201.png)

It is possible to reject the null hypothesis using ANOVA and then to not subsequently identify differences in the pairwise comparisons. However, this does not invalidate the ANOVA conclusion. It only means we have not been able to successfully identify which specific groups differ in their means

The ANOVA procedure examines the big picture: it considers all groups simultaneously to decipher whether there is evidence that some difference exists. Even if the test indicates that there is strong evidence of differences in group means, identifying with high confidence a specific difference
 as statistically significant is more difficult.