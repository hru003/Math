
Used to estimate the characteristics of population from a sample.
Because of sampling error, you cannot expect $\bar{x}$ to equal μ exactly.

Hypothesis Testing
Regression Analysis

A hypothesis is a statement assuming that something is true. It provides the relationship between variables or distribution of the population.

Hypotheses are typically formulated based on: 
1. Prior knowledge 
2. Observations 
3. Assumptions

<font color="#00b0f0">Null hypothesis:</font> A hypothesis to be tested. We use the symbol H0 to represent the null hypothesis. "Contains ="

<font color="#00b0f0">Alternative hypothesis:</font> A hypothesis to be considered as an alternative to the null hypothesis. We use the symbol Ha to represent the alternative hypothesis. 'Contains !=, <, >'

<font color="#00b0f0">Hypothesis test:</font> The problem in a hypothesis test is to decide whether the null hypothesis should be rejected in favor of the alternative hypothesis.

Examples:

Two tailed and One-tailed tests

Basic Logic of Hypothesis Testing 
- Take a random sample from the population. 
- If the sample data are consistent with the null hypothesis, reject the Alternative hypothesis and accept the null hypothesis
- If the sample data are in-consistent with the null hypothesis, accept the Alternative hypothesis and reject the null hypothesis

Example


Type I and Type II Errors

- Type I error: Rejecting the null hypothesis when it is in fact true. 
- Type II error: Not rejecting the null hypothesis when it is in fact false.

- ![](images/Pasted%20image%2020231206162116.png) 
- The Type I error probability, is commonly called the significance level of the hypothesis test, is denoted $\alpha$.
- The standard values for $\alpha$ are 10%, 5%, and 1%.
- The Type II error probability, is denoted β
- $\alpha + \beta = 1$ 

P-value

- Rule: When the p-value is less than $\alpha$, reject H0.
- It also indicates the [probability](https://www.cuemath.com/data/probability/) of making an error in rejecting or not rejecting the null hypothesis.
- This value is always a number between 0 and 1.


Rejection region: The set of values for the test statistic that leads to rejection of the null hypothesis. 

Nonrejection region: The set of values for the test statistic that leads to non-rejection of the null hypothesis. 

Critical value(s): The value or values of the test statistic that separate the rejection and nonrejection regions. A critical value is considered part of the rejection region.

![](images/Pasted%20image%2020231206160413.png)

![](images/Pasted%20image%2020231206160431.png)


Hypothesis Testing

1. Formulate Hypothesis
2. Determine the significance level
3. Determine the type of the test
4. Calculate the test values and p-value
5. Make a decision

Parametric Tests

T-test
There are 3 types of t-tests that could be performed on the n number of samples collected.
- One-sample test,
- Independent sample t-test and
- Paired samples t-test
The critical value is obtained from the t-table looking for the degree of freedom(df = n-1) and the corresponding α value(usually 0.05 or 0.1). If the t-test obtained statistically > CV then the initial hypothesis is wrong.

For comparing the mean of a population from n samples
$t= \dfrac{\overline{x}- μ}{\dfrac{\sigma}{\sqrt{n}}}$

Compare the mean of two groups of samples
$t = \dfrac{\overline{x_{1}}-\overline{x_{2}}}{\sqrt{(\dfrac{s_{1}^2}{n_{1}}+\dfrac{s_{2}^2}{{n_{2}}}})}$

Whenever two distributions of the variables are highly correlated
$t = \dfrac{Σ(x_{1}-x_{2})}{\dfrac{s}{\sqrt{n}}}$

[t-test formula - Derivation, Examples (cuemath.com)](https://www.cuemath.com/t-test-formula/)
[Student's t-distribution - Wikipedia](https://en.wikipedia.org/wiki/Student%27s_t-distribution#Table_of_selected_values)

Z-test

- One-Sample Z Test $z = \frac{\overline{x}-\mu}{\frac{\sigma}{\sqrt{n}}}$
- 
ANOVA
- ANOVA means analysis of variance.
- The ANOVA test applies when there are more than two independent groups.
- The goal of the ANOVA test is to check for variability within the groups as well as the variability among the groups.
- The data sets must be normally distributed.
- ANOVA coefficient, F= Mean sum of squares between the groups (MSB)/ Mean squares of errors (MSE).
- F = MST / MSE
- ![](images/Pasted%20image%2020231216181103.png)
- ![](images/Pasted%20image%2020231216181451.png)
- Check with the f-distribution table.
- **One-Way ANOVA:** This test is used to see if there is a variation in the mean values of three or more groups. Such a test is used where the data set has only one independent variable.
- **Two-Way ANOVA:** Two independent variables are used in the two-way ANOVA.

Non-Parametric Tests 

- Nonparametric tests are used when a population distribution is unknown.
- 

Chi-square test
- Testing categorical data for variation
- ![](images/Pasted%20image%2020231215164536.png)
- The value of $X^2$ is then compared to the critical chi-square score obtained from the Reference Table corresponding to the degree of freedom (k-1) to determine whether to reject the null hypothesis.
- $X^2$ < value from the table then accept H0
- $X^2$ > value from the table then reject H0
- ![](images/Pasted%20image%2020231215191408.png)
- 
	
	
Sign Test

- Mainly used to test median, other than mean, proportion and variance.
- Assign +, -, 0 -> improve, lowered, remained same
	
	
	
Kruskal-Wallis Test
Mann-Whitney-Wilcoxon Test
- Used to
Run Test

Regression
	Linear Regression


