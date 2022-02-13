# Statistic Basics

Summary statistics are single number summarising large amounts of data

- Chance always can play a part in variation. For example, discrepancies between 2 groups might just be due to chance.

[Data Matrix](Statistic%20Basics%206ffac73af81e49bb9438d87b443b6ee8/Data%20Matrix%20a330ec7e0b80410ba1eb07cc3c33bcf9.csv)

When reading observations, it's best to write them in a data matrix, where rows are cases and columns are features / variables.

**Types of variable**

- Numerical variables (numbers)
    - Continuous [0-1]
    - Discrete [0,1,2]
        - Discrete values basically takes a number value and increments in jumps
- Categorical variables (types)
    - Nominal (unordered) [red, yellow, green]
    - Ordinal (ordered) [1st, 2nd, 3rd]
    

**Relationships between variables**

If a relationship exists between 2 variables, they are **dependent** else **independent**

- You can draw on a scatter graph and see on a trend
- Independent variable is what we change
- Dependent variable is what we are hoping to see a change in (result)

Explanatory variables might affect a response variable. To prove this, it requires another experiment 

Co-founding variable: variable that is correlated with both explanatory and response variables.

Control variable: constant variable to keep the same.

**Populations**

All research refers to a target population but sometimes, this is too large, so we take a sample. 

- Sample is a subset of the population

Always be careful of anecdotal evidence. Cases are few, but can be true and verifiable.

1. Simple random sample: Pick a random selection from a population to reduce bias. 
    - If **non-response rate** is high, be careful. For example, 30% of people who answer a survey means results are unclear of being representative of entire population.
    - Unintentional bias can skew results
    - **Convenience sample:** individuals who are more easily accessible are more likely to be included in the sample.
        - Difficult to discern sub-population a convenience sample represents

**If the sample can is representative of the general population, then study can be generalized**

Volunteers can not be generalized as they chose to turn up → bias

Data where no treatment has been done is called **observational data**

- Can make casual conclusions but anything beyond is a bad idea.
- Prospective study collects data as events unfold
- Retrospective studies collect data after events have taken place

**Experiments**

To find casual relationships, you must do an experimental study where variables are controlled.

When researchers assign treatments to cases → experiments

Randomized experiments are where assignment includes randomization 

**Key definitions:**

Observation: a value of something of interest you're measuring or counting during a study or experiment: a person's height, a bank account value at a certain point in time, or number of animals.

Variable: an attribute that describes a person, place, thing, or idea.

Sample statistic: value calculated based on the observed sample

Population parameter: number that describes something about an entire group or population

**Sampling Strategies**

1. Simple random sampling: like a raffle as each case in population has chance of being in final sample and knowing that a case is included in a sample doesn't provide useful information about which cases are included.
2. Stratified sampling: divide and conquer sampling strategy.
    1.  Population is split in groups (**strata)**, and strata is chosen so similar cases are grouped together.
    2. THEN Simple random sampling is applied to each stratum 
    - It can be good to get a more stable estimate for a subpopulation in a stratum if the cases are very similar, leading to more precise estimates within each group.
    
    In image 1, random points are chosen
    
    In image 2, samples are split into strata and then random points are picked 
    
    ![Statistic%20Basics%206ffac73af81e49bb9438d87b443b6ee8/Untitled.png](Statistic%20Basics%206ffac73af81e49bb9438d87b443b6ee8/Untitled.png)
    
3. Cluster sample: break population into many groups called clusters. 
    1. Data should be close together. 
    2. Sample a fixed number of clusters and include all observation from each cluster in sample. Ignore all other clusters.
4. Multistage sample: Like cluster, but you take a random sample out of each cluster instead of the entire cluster.

Image 1 shows cluster

Image 2 shows multistage

![Statistic%20Basics%206ffac73af81e49bb9438d87b443b6ee8/Untitled%201.png](Statistic%20Basics%206ffac73af81e49bb9438d87b443b6ee8/Untitled%201.png)

**Principles of experimental design**
**1. Controlling.** 

Researchers assign treatments to cases, and they do their best to control any other
differences in the groups. 

For example, when patients take a drug in pill form, some patients take the pill with only a sip of water while others may have it with an entire glass of water. To control for the effect of water consumption, a doctor may ask all patients to drink a 12 ounce glass of water with the pill.

**2. Randomization.** 

Researchers randomize patients into treatment groups to account for variables
that cannot be controlled. 

For example, some patients may be more susceptible to a disease than others due to their dietary habits. Randomizing patients into the treatment or control group helps even out such differences, and it also prevents accidental bias from entering the study.

**3. Replication.** 

The more cases researchers observe, the more accurately they can estimate the effect
of the explanatory variable on the response. 

In a single study, we replicate by collecting a sufficiently large sample. Additionally, a group of scientists may replicate an entire study to verify an earlier finding.

**4. Blocking.** 

Researchers sometimes know or suspect that variables, other than the treatment, influence the response. Under these circumstances, they may first group individuals based on this
variable into blocks and then randomize cases within each block to the treatment groups. This
strategy is often referred to as blocking. 

For instance, if we are looking at the effect of a drug on heart attacks, we might first split patients in the study into low-risk and high-risk blocks, then randomly assign half the patients from each block to the control group and the other half to the treatment group. This strategy ensures each treatment group has an equal number of low-risk and high-risk patients.

**Reducing bias**

- Use a control group to test if a difference has occurred.
- When subject doesn't know about their test, study is blind.
- Placebos can be used here to convince the subject, but sometimes, they can improve performance. This is the placebo effect.
- When testee and tester don't know, its double blind

![Statistic%20Basics%206ffac73af81e49bb9438d87b443b6ee8/Untitled%202.png](Statistic%20Basics%206ffac73af81e49bb9438d87b443b6ee8/Untitled%202.png)

**Proof is final and conclusive. Evidence is tentative.**

Proof is a fact that demonstrates something to be real or true. 

Evidence is information that might lead one to believe something to be real or true.