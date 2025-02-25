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