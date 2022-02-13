# Probability Theory

You want to frame probability in terms of a random process giving rise to an outcome.

The probability of an outcome is the proportion of times the outcome would occur if we
observed the random process an infinite number of times

**LAW OF LARGE NUMBERS**
As more observations are collected, the proportion p̂ n of occurrences with a particular outcome
converges to the probability p of that outcome.

Where  p̂ n be the proportion of outcomes that are 1 after the first n rolls.

![Probability%20Theory%20b8ea50e148eb4491b3fc37738a2efd22/Untitled.png](Probability%20Theory%20b8ea50e148eb4491b3fc37738a2efd22/Untitled.png)

Disjoint or mutually exclusive outcomes are 2 outcomes which cannot both happen.

![Probability%20Theory%20b8ea50e148eb4491b3fc37738a2efd22/Untitled%201.png](Probability%20Theory%20b8ea50e148eb4491b3fc37738a2efd22/Untitled%201.png)

Venn diagrams are useful when outcomes can be categorized as “in” or “out” for two or three
variables, attributes, or random processes.

![Probability%20Theory%20b8ea50e148eb4491b3fc37738a2efd22/Untitled%202.png](Probability%20Theory%20b8ea50e148eb4491b3fc37738a2efd22/Untitled%202.png)

A probability distribution is a table of all disjoint outcomes and their associated probabilities.

This set of all possible outcomes is called the sample space (S) for rolling a die.

If D is an event that is a set of outcomes, a complement, Dc is the set of all possible outcomes not already included in D.

![Probability%20Theory%20b8ea50e148eb4491b3fc37738a2efd22/Untitled%203.png](Probability%20Theory%20b8ea50e148eb4491b3fc37738a2efd22/Untitled%203.png)

**INDEPENDENCE** 

Two processes are independent if knowing the outcome of one provides no useful information
about the outcome of the other.

![Probability%20Theory%20b8ea50e148eb4491b3fc37738a2efd22/Untitled%204.png](Probability%20Theory%20b8ea50e148eb4491b3fc37738a2efd22/Untitled%204.png)

**MARGINAL AND JOINT PROBABILITIES**
If a probability is based on a single variable, it is a marginal probability. 

The probability of outcomes for two or more variables or processes is called a joint probability i.e. P(X='1') and P(X='1' AND Y='2')

**Binomial Probability Calculator - At Least Probability**

![Probability%20Theory%20b8ea50e148eb4491b3fc37738a2efd22/Untitled%205.png](Probability%20Theory%20b8ea50e148eb4491b3fc37738a2efd22/Untitled%205.png)

**CONDITIONAL PROBABILITY**

[https://www.mathsisfun.com/data/probability-events-conditional.html](https://www.mathsisfun.com/data/probability-events-conditional.html)

The | symbol means given... We call this a conditional probability because we computed the probability under a condition

There are two parts to a conditional probability, the outcome of interest and the condition.

*P (truth is fashion given mach learn is pred fashion) → the ML classifier prediction said the photo was about fashion.*

![Probability%20Theory%20b8ea50e148eb4491b3fc37738a2efd22/Untitled%206.png](Probability%20Theory%20b8ea50e148eb4491b3fc37738a2efd22/Untitled%206.png)

**General Multiplication Rule** for events that might not be independent.

![Probability%20Theory%20b8ea50e148eb4491b3fc37738a2efd22/Untitled%207.png](Probability%20Theory%20b8ea50e148eb4491b3fc37738a2efd22/Untitled%207.png)

![Probability%20Theory%20b8ea50e148eb4491b3fc37738a2efd22/Untitled%208.png](Probability%20Theory%20b8ea50e148eb4491b3fc37738a2efd22/Untitled%208.png)

**Independence considerations in conditional probability**

If two events are independent, then knowing the outcome of one should provide no information
about the other.

![Probability%20Theory%20b8ea50e148eb4491b3fc37738a2efd22/Untitled%209.png](Probability%20Theory%20b8ea50e148eb4491b3fc37738a2efd22/Untitled%209.png)

Tree diagrams are a tool to organize outcomes and probabilities around the structure of the
data.

**Rules about independence in probability to speed things up**

[https://people.richland.edu/james/lecture/m170/ch05-rul.html](https://people.richland.edu/james/lecture/m170/ch05-rul.html)

**BAYES THEOREM**

Basically a formula which generalizes a tree diagram

![Probability%20Theory%20b8ea50e148eb4491b3fc37738a2efd22/Untitled%2010.png](Probability%20Theory%20b8ea50e148eb4491b3fc37738a2efd22/Untitled%2010.png)

![Probability%20Theory%20b8ea50e148eb4491b3fc37738a2efd22/Untitled%2011.png](Probability%20Theory%20b8ea50e148eb4491b3fc37738a2efd22/Untitled%2011.png)

**To apply Bayes’ Theorem correctly, there are two preparatory steps:**

1. First identify the marginal probabilities of each possible outcome of the first variable: P (A1 ), P (A2 ), ..., P (Ak ).
2. Identify the probability of the outcome B, conditioned on each possible scenario for the first variable: P (B|A1 ), P (B|A2 ), ..., P (B|Ak ).

[Example of Bayes Theorem](Probability%20Theory%20b8ea50e148eb4491b3fc37738a2efd22/Example%20of%20Bayes%20Theorem%20cfd4f8e6075c4ba3862dcd9c501b5651.md)

**Hack**: for P(B), calculate the sum of the conditional probabilities based on whether A has happened or not

![Probability%20Theory%20b8ea50e148eb4491b3fc37738a2efd22/Untitled%2012.png](Probability%20Theory%20b8ea50e148eb4491b3fc37738a2efd22/Untitled%2012.png)

[Random Variables](Probability%20Theory%20b8ea50e148eb4491b3fc37738a2efd22/Random%20Variables%20de0d5a2dcdc34ea99cdc6c1d33315d21.md)

## Cumulative Distribution Function

Probability that a random variable / distribution function X will take a value less than or equal to x. 

![Probability%20Theory%20b8ea50e148eb4491b3fc37738a2efd22/Untitled%2013.png](Probability%20Theory%20b8ea50e148eb4491b3fc37738a2efd22/Untitled%2013.png)

![Untitled](Probability%20Theory%20b8ea50e148eb4491b3fc37738a2efd22/Untitled%2014.png)