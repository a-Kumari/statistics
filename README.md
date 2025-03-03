# what is statistics and its types?
Statistics deals with the collection, organization, analysis, interpretation, and presentation of data.
Statistics is widely used in various fields such as business, healthcare, economics, social sciences, and engineering to analyze real-world problems and draw meaningful conclusions.

# Types of Statistics:
Descriptive Statistics
Inferential Statistics

## 1. Descriptive Statistics:
Descriptive statistics summarize and organize data to make it easily understandable.It involves the use of numerical and graphical methods.
Techniques of Descriptive Statistics:
1. Measures of Central Tendency:(mean, mode, median)
2. Measures of Dispersion (Variability): (Variance, Standard Deviation)
3. Graphical Representation of Data: (Bar Graphs, Histograms, Pie Charts, Box Plots)

# 2. Inferential Statistics:
Inferential statistics allows us to make predictions or generalizations about a larger population based on a sample of data. It is used to analyze relationships, test hypotheses, and make forecasts.
Techniques of Inferential Statistics:
1. Hypothesis Testing 
2. Z- test
3. chi-square test
4. Anova test or F-test

# what is population and sample and sampling techniques?
# Population
A population refers to the entire group of individuals, objects, or events that share a common characteristic and are the subject of a statistical study.
Example:
All students in a university.
All patients in a hospital.

# Sample
A sample is a subset of the population selected for analysis.
Example:
200 students selected from a university for a survey.

# Sampling Techniques
Since studying an entire population is impractical, researchers use sampling techniques to select a subset of data.

# Types of Sampling:
1. Simple Random Sampling
Every member of the population has an equal chance of being selected.
Example:
Selecting 100 employees randomly from a company using a lottery system.
2. Stratified Sampling
The population is divided into subgroups based on characteristics like age, gender, or income. Then, a random sample is taken from each group.

3. Systematic Sampling
A starting point is chosen randomly, and then every kth element is selected.

4. Convenience Sampling
The researcher selects individuals based on their expertise or relevance to the study.

# What are Variables in Statistics?
A variable is any characteristic, number, or quantity that can change or vary across individuals or observations in a dataset. Variables are used to collect and analyze data in statistics.

Example:

Height of students (can be different for each student).
Age of employees (varies from person to person).
Number of sales in a store (changes daily).

# Types of Variables

#Quantitative Variables (Numerical Data) – Variables that represent numerical values.
1. Discrete Variables (Countable Data)
Variables that take specific, finite values (whole numbers).
They cannot take decimal or fractional values.

Examples:
Number of students in a class (10, 25, 30).
Number of cars in a parking lot (2, 5, 8).

2. Continuous Variables (Measurable Data)
Variables that take any value within a given range (can be decimal or fractional).
They are measured rather than counted.

Examples:
Height of students (5.4 ft, 6.1 ft).
Weight of a person (70.5 kg, 65.3 kg).
Temperature of a city (27.8°C, 30.2°C).

Qualitative Variables (Categorical Data) – Variables that represent categories or labels
1. Nominal Variables (No Order, Only Categories)
These are categories without any natural order or ranking.
Used for labeling groups.

Examples:
Gender: Male, Female, Other.
Eye Color: Brown, Blue, Green.
Blood Group: A, B, AB, O.

2. Ordinal Variables (Ordered Categories)
These are categories with a meaningful order or ranking, but the difference between them is not measurable.

Examples:
Education Level: Primary, Secondary, Higher Education.
Satisfaction Level: Very Satisfied, Satisfied, Neutral, Dissatisfied, Very Dissatisfied.
Ranking in a Competition: 1st, 2nd, 3rd, etc.

## 1. Measures of Central Tendency

Measures of central tendency describe the central value of a dataset. Common measures include:

* **Mean (Average):**
    * The sum of all values divided by the number of values.
    * Sensitive to outliers.
    * Formula: μ = Σx / n (for population), x̄ = Σx / n (for sample)
* **Median:**
    * The middle value when the data is ordered.
    * Less sensitive to outliers.
    * If there are an even number of values, the median is the average of the two middle values.
* **Mode:**
    * The value(s) that appear most frequently.
    * Useful for categorical data and datasets with distinct peaks.
    * A dataset can have multiple modes (bimodal, multimodal) or no mode.

## 2. Measures of Dispersion

Measures of dispersion describe the spread or variability of data. Common measures include:

* **Range:**
    * The difference between the maximum and minimum values.
    * Simple but sensitive to outliers.
    * Formula: Range = Maximum value - Minimum value
* **Variance:**
    * The average of the squared differences from the mean.
    * Measures how far the data points are spread out from the mean.
    * Formula: σ² = Σ(x - μ)² / N (for population), s² = Σ(x - x̄)² / (n - 1) (for sample)
* **Standard Deviation:**
    * The square root of the variance.
    * Provides a measure of dispersion in the same units as the data.
    * Formula: σ = √σ² (for population), s = √s² (for sample)
* **Interquartile Range (IQR):**
    * The difference between the third quartile (Q3) and the first quartile (Q1).
    * Represents the range of the middle 50% of the data.
    * Less sensitive to outliers than the range.
    * Formula: IQR = Q3 - Q1

## 3. Percentiles and Quartiles

* **Percentiles:**
    * Divide a dataset into 100 equal parts.
    * The *k*th percentile is the value below which *k*% of the data falls.
    * Example: The 75th percentile is the value below which 75% of the data falls.
* **Quartiles:**
    * Specific percentiles that divide a dataset into four equal parts.
    * Q1 (First Quartile): 25th percentile.
    * Q2 (Second Quartile): 50th percentile (median).
    * Q3 (Third Quartile): 75th percentile.
    * To calculate quartiles, the data must first be sorted. Then the location of each quartile can be found.

## 4. Outlier Detection

Outliers are data points that significantly deviate from the rest of the data. Common methods for identifying outliers include:

* **IQR Method:**
    * Calculate the IQR (Q3 - Q1).
    * Calculate the lower bound: Q1 - (1.5 * IQR).
    * Calculate the upper bound: Q3 + (1.5 * IQR).
    * Any data point below the lower bound or above the upper bound is considered an outlier.
* **Z-Score Method:**
    * Calculate the Z-score for each data point.
    * The Z-score represents the number of standard deviations a data point is from the mean.
    * Formula: Z = (x - μ) / σ
    * Data points with a Z-score greater than a certain threshold (e.g., ±3) are considered outliers.


## 1. Normal Distribution

The normal distribution, also known as the Gaussian distribution, is a symmetric, bell-shaped distribution. It is characterized by its mean (μ) and standard deviation (σ).

* **Key Properties:**
    * Symmetric around the mean.
    * Mean, median, and mode are equal.
    * Determined by two parameters: mean (μ) and standard deviation (σ).

###  Empirical Rule (68-95-99.7 Rule)

The empirical rule describes the percentage of data that falls within a certain number of standard deviations from the mean in a normal distribution:

* **68%:** Approximately 68% of the data falls within one standard deviation of the mean (μ ± 1σ).
* **95%:** Approximately 95% of the data falls within two standard deviations of the mean (μ ± 2σ).
* **99.7%:** Approximately 99.7% of the data falls within three standard deviations of the mean (μ ± 3σ).

## 2. Central Limit Theorem (CLT)

The Central Limit Theorem states that the distribution of the sample mean approaches a normal distribution as the sample size increases, regardless of the shape of the original population distribution.

* **Key Points:**
    * Applies to the distribution of sample means, not individual data points.
    * Requires a sufficiently large sample size (typically n ≥ 30).
    * The mean of the sample means is equal to the population mean (μ).
    * The standard deviation of the sample means (standard error) is σ / √n, where σ is the population standard deviation and n is the sample size.
    * This theorem is fundamental for statistical inference.

## 3. Log-Normal Distribution

The log-normal distribution is a probability distribution of a random variable whose logarithm is normally distributed. It is often used to model variables that are positively skewed and bounded by zero.

* **Key Properties:**
    * Positively skewed.
    * Defined for positive values only.
    * If Y has a log-normal distribution, then ln(Y) has a normal distribution.
    * Used to model things like asset prices, income, and survival times.

## 4. Power Law Distribution

A power law distribution is a probability distribution where the frequency of an event is inversely proportional to a power of its size or rank. It is characterized by a "long tail," meaning that rare events have a significant impact.

* **Key Properties:**
    * Scale-free.
    * Long-tailed.
    * Common in natural and social phenomena (e.g., city sizes, website traffic, earthquakes).
    * Examples include the Pareto distribution, and Zipf's law.

## Pareto Distribution

The Pareto distribution, also known as the power law distribution, is a probability distribution that models phenomena where a small number of items account for a large proportion of the total activity or value. It's often described by the "80/20 rule," where 80% of the effects come from 20% of the causes.

**Key Characteristics:**

* **Skewed Distribution:** It's heavily skewed to the right, meaning most values are small, with a long tail of large values.
* **Power Law:** The probability of observing a large value decreases as a power of the value.
* **Scale and Shape Parameters:** It's defined by two parameters:
    * **Scale (x_m):** The minimum possible value.
    * **Shape (alpha):** Determines the shape of the distribution. Higher alpha values result in a steeper decline in probability.

**Applications:**

* Income distribution
* Website traffic
* Size of cities
* File sizes

## Hypothesis Testing

Hypothesis testing is a statistical method used to determine whether there is enough evidence in a sample of data to infer that a certain condition is true for the entire population. It involves formulating two competing hypotheses:

* **Null Hypothesis (H0):** A statement that there is no effect or no difference. It's the default assumption.
* **Alternative Hypothesis (H1 or Ha):** A statement that there is an effect or a difference. It's what the researcher is trying to find evidence for.

**Steps in Hypothesis Testing:**

1.  **Formulate Hypotheses:** Define the null and alternative hypotheses.
2.  **Choose a Significance Level (alpha):** This is the probability of rejecting the null hypothesis when it's actually true (Type I error). Common values are 0.05 and 0.01.
3.  **Select a Test Statistic:** Choose a statistic that measures the difference between the sample data and what is expected under the null hypothesis (e.g., t-statistic, z-statistic, chi-square statistic).
4.  **Calculate the Test Statistic and p-value:** Compute the value of the test statistic and the p-value, which is the probability of observing a test statistic as extreme as or more extreme than the one calculated, assuming the null hypothesis is true.
5.  **Make a Decision:**
    * If the p-value is less than the significance level (p < alpha), reject the null hypothesis.
    * If the p-value is greater than or equal to the significance level (p >= alpha), fail to reject the null hypothesis.
6.  **Draw a Conclusion:** Interpret the results in the context of the research question.

**Example:**

Suppose we want to test if the average income in a city follows a Pareto distribution with a specific alpha value.

* **H0:** The average income follows a Pareto distribution with alpha = X.
* **H1:** The average income does not follow a Pareto distribution with alpha = X.
* We would then collect sample income data, perform a statistical test (e.g., goodness-of-fit test), calculate the p-value, and make a decision based on the significance level.


* Failing to reject the null hypothesis does not mean it's true; it simply means there's not enough evidence to reject it.
* Hypothesis testing relies on probability and statistical inference, so there's always a chance of making an error.
* The correct test to use depends on the underlying data, and the question being asked.

## Probability Distributions

Probability distributions describe the likelihood of different outcomes in a random experiment.

### Probability Mass Function (PMF)

* The PMF, denoted as P(X=x), gives the probability that a discrete random variable X takes on a specific value x.
* Used for discrete random variables (e.g., number of coin flips, number of defective items).
    * P(X=x) ≥ 0 for all x.
    * Σ P(X=x) = 1 (sum of probabilities over all possible values is 1).

* **Example:** For a fair coin flip, the PMF is P(Heads) = 0.5 and P(Tails) = 0.5.

### Probability Density Function (PDF)

* The PDF, denoted as f(x), describes the relative likelihood of a continuous random variable X taking on a given value x.
* Used for continuous random variables (e.g., height, weight, temperature).
    * f(x) ≥ 0 for all x.
    * The area under the PDF curve over a given interval represents the probability that X falls within that interval.
    * ∫ f(x) dx = 1 (total area under the curve is 1).

* **Example:** The normal distribution's bell-shaped curve is a PDF.

### Cumulative Distribution Function (CDF)

* The CDF, denoted as F(x), gives the probability that a random variable X takes on a value less than or equal to x.
* Used for both discrete and continuous random variables.
    * F(x) = P(X ≤ x).
    * F(x) is a non-decreasing function.
    * F(-∞) = 0 and F(∞) = 1.
* **Relationship to PMF/PDF:**
    * For discrete variables: F(x) = Σ P(X=xi) for all xi ≤ x.
    * For continuous variables: F(x) = ∫ f(t) dt from -∞ to x.

## Z-Test in Hypothesis Testing

The Z-test is a statistical test used to determine whether there is a significant difference between a sample mean and a population mean, or between two sample means, when the population standard deviation is known.

### Z-Test Formula

The Z-test statistic is calculated as:
Z = (X̄ - μ) / (σ / √n)

Where:

* X̄ is the sample mean.
* μ is the population mean.
* σ is the population standard deviation.
* n is the sample size.

### Assumptions

* The population standard deviation (σ) is known.
* The sample is randomly selected.
* The sample size is sufficiently large (typically n ≥ 30) or the population is normally distributed.

### Steps for Performing a Z-Test

1.  **State the hypotheses:** Define the null and alternative hypotheses.
2.  **Determine the significance level (α).**
3.  **Calculate the Z-test statistic.**
4.  **Determine the critical value or p-value:** Using the standard normal distribution table or a statistical calculator.
5.  **Make a decision:** Compare the Z-test statistic to the critical value or compare the p-value to α.
6.  **Draw a conclusion:** Interpret the results in the context of the problem.

### Example

Suppose we want to test if the average height of students in a school is significantly different from 170 cm. We know the population standard deviation is 10 cm and we take a sample of 100 students with a mean height of 172 cm.

* H0: μ = 170
* H1: μ ≠ 170
* α = 0.05

Calculate the Z-statistic: Z = (172 - 170) / (10 / √100) = 2.


##  T-Test

The t-test is a statistical hypothesis test used to determine if there is a significant difference between the means of two groups. It's particularly useful when dealing with small sample sizes or when the population standard deviation is unknown.


* Assumptions: Data should be approximately normally distributed.
* P-value: The probability of observing the results if the null hypothesis is true. A small p-value (typically < 0.05) indicates strong evidence against the null hypothesis.
* Degrees of freedom: number of independent pieces of information that went into calculating the estimate.

##  Type I and Type II Errors

In hypothesis testing, there's always a risk of making incorrect conclusions.

* **Type I Error (False Positive):** Rejecting the null hypothesis when it is actually true.
    * Symbolized as α (alpha).
    * Example: Concluding that a drug is effective when it is not.
* **Type II Error (False Negative):** Failing to reject the null hypothesis when it is actually false.
    * Symbolized as β (beta).
    * Example: Failing to detect that a drug is effective when it actually is.
* **Power (1 - β):** The probability of correctly rejecting the null hypothesis when it is false.

* There's often a trade-off between Type I and Type II errors. Decreasing one increases the other.
* The significance level (α) determines the probability of a Type I error.

##  Confidence Interval and Margin of Error

A confidence interval provides a range of values within which we are reasonably confident that the true population parameter lies.

* **Confidence Interval (CI):** A range of values, calculated from sample data, that is likely to contain the true population parameter.
    * Example: A 95% confidence interval for the average height of a population.
* **Margin of Error (ME):** The range of values above and below the sample statistic that defines the confidence interval.
    * It is directly related to the standard error and the chosen confidence level.
    * A larger margin of error results in a wider confidence interval.

* Confidence Interval = Sample Statistic ± Margin of Error
* The confidence level (e.g., 95%) determines the margin of error. Higher confidence levels result in wider intervals.
* The margin of error is affected by the standard deviation of the sample, and the sample size. Larger sample sizes reduce the margin of error.

### Formula example:

For a sample mean:

ME = Z * (standard deviation / sqrt(sample size))

Where Z is the z-score corresponding to the desired confidence level. For a 95% confidence interval, Z is approximately 1.96.

##  Chi-Square Test

The Chi-Square test is a statistical test used to analyze categorical data. It helps determine if there's a significant association between two categorical variables or if observed frequencies differ significantly from expected frequencies.

### Types:

* **Goodness-of-fit test:** Determines if the observed frequency distribution of a single categorical variable matches an expected distribution.
* **Test of independence:** Determines if there's a significant association between two categorical variables.

* Uses the Chi-Square distribution.
* Involves comparing observed and expected frequencies.
* Sensitive to sample size.
* Degrees of freedom are calculated based on the number of categories.

##  Analysis of Variance (ANOVA)

ANOVA is a statistical technique used to compare the means of two or more groups. It determines if there are statistically significant differences between the group means.

* Used for comparing means of multiple groups.
* Partitions the total variance into between-group and within-group variance.
* Uses the F-distribution and F-test.
* Assumptions include normality of data and homogeneity of variances.

### Types:

* **One-way ANOVA:** Compares means of groups based on one factor.
* **Two-way ANOVA:** Compares means of groups based on two factors.
* **Repeated Measures ANOVA:** Compares means of groups when the same subjects are used in each group.

##  F-Distribution

The F-distribution is a continuous probability distribution used in hypothesis testing, particularly in ANOVA and regression analysis. It describes the ratio of two variances.

* Defined by two parameters: degrees of freedom for the numerator (df1) and degrees of freedom for the denominator (df2).
* Positively skewed.
* Used to calculate p-values for F-tests.
* Used to compare variances.

## F-Test

The F-test is a statistical test that uses the F-distribution to determine if there's a significant difference between variances or if a regression model is statistically significant.

### Applications:

* **ANOVA:** Used to determine if there are significant differences between group means.
* **Regression analysis:** Used to assess the overall significance of a regression model.
* **Comparing Variances:** Used to compare two variances.

### Relationship to ANOVA and F-Distribution:

* In ANOVA, the F-test calculates the F-statistic, which is the ratio of between-group variance to within-group variance.
* The F-statistic is then compared to the F-distribution to determine the p-value.
* If the P value is sufficiently small, we reject the null hypothesis, and conclude that there are significant differences between the means of the groups.
* The F distribution provides the probability of observing an F statistic given the null hypothesis is true.
