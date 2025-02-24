what is statistics and its types?
Statistics deals with the collection, organization, analysis, interpretation, and presentation of data.
Statistics is widely used in various fields such as business, healthcare, economics, social sciences, and engineering to analyze real-world problems and draw meaningful conclusions.

Types of Statistics:
Descriptive Statistics
Inferential Statistics

1. Descriptive Statistics:
Descriptive statistics summarize and organize data to make it easily understandable.It involves the use of numerical and graphical methods.
Techniques of Descriptive Statistics:
1. Measures of Central Tendency:(mean, mode, median)
2. Measures of Dispersion (Variability): (Variance, Standard Deviation)
3. Graphical Representation of Data: (Bar Graphs, Histograms, Pie Charts, Box Plots)

2. Inferential Statistics:
Inferential statistics allows us to make predictions or generalizations about a larger population based on a sample of data. It is used to analyze relationships, test hypotheses, and make forecasts.
Techniques of Inferential Statistics:
1. Hypothesis Testing 
2. Z- test
3. chi-square test
4. Anova test or F-test

what is population and sample and sampling techniques?
Population
A population refers to the entire group of individuals, objects, or events that share a common characteristic and are the subject of a statistical study.
Example:
All students in a university.
All patients in a hospital.

Sample
A sample is a subset of the population selected for analysis.
Example:
200 students selected from a university for a survey.

Sampling Techniques
Since studying an entire population is impractical, researchers use sampling techniques to select a subset of data.

Types of Sampling:
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

What are Variables in Statistics?
A variable is any characteristic, number, or quantity that can change or vary across individuals or observations in a dataset. Variables are used to collect and analyze data in statistics.

Example:

Height of students (can be different for each student).
Age of employees (varies from person to person).
Number of sales in a store (changes daily).

Types of Variables

Quantitative Variables (Numerical Data) – Variables that represent numerical values.
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
