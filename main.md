# Math 210 – Assignment 1 B (Statistics)

## Question 1

1\. For the data below, representing a sample of heights (in metres) for
10 years old males at a certain school, find:

Data: 1.3, 1.5, 1.4, 1.3, 1.2, 1.4

\[8 marks\]

a)The mean

b\) The median

c\) The mode

d\) The standard deviation

e\) The 72<sup>nd</sup> percentile

**Solve by hand (without the use of software) and include full
solutions.**

### a) Mean

The mean is the average of all the data points. It is calculated as
follows:

$$
\text{Mean} (\bar{x}) = \frac{\sum x_i}{n}
$$

Where $\sum x_i$ is the sum of all data points and $n$ is the number of
data points.

$$
\sum x_i = 1.3 + 1.5 + 1.4 + 1.3 + 1.2 + 1.4 = 8.1
$$

$$
n = 6
$$

$$
\text{Mean} (\bar{x}) = \frac{8.1}{6} = 1.35
$$

### b) Median

The median is the middle value when the data points are arranged in
ascending order. If the number of data points is even, the median is the
average of the two middle numbers.

Arranging the data in ascending order: 1.2, 1.3, 1.3, 1.4, 1.4, 1.5

Since there are 6 data points (even number), the median is the average
of the 3rd and 4th values:

$$
\text{Median} = \frac{1.3 + 1.4}{2} = \frac{2.7}{2} = 1.35
$$

### c) Mode

The mode is the value that appears most frequently in the data set.

The frequencies are: - 1.2: 1 time - 1.3: 2 times - 1.4: 2 times - 1.5:
1 time

Both 1.3 and 1.4 appear twice, so there are two modes:

$$
\text{Mode} = 1.3 \text{ and } 1.4
$$

### d) Standard Deviation

The standard deviation measures the dispersion of the data points from
the mean. It is calculated as follows:

$$
\sigma = \sqrt{\frac{\sum (x_i - \bar{x})^2}{n}}
$$

First, find the squared deviations from the mean:

$$
(x_i - \bar{x})^2 = (1.3 - 1.35)^2, (1.5 - 1.35)^2, (1.4 - 1.35)^2, (1.3 - 1.35)^2, (1.2 - 1.35)^2, (1.4 - 1.35)^2
$$

$$
= (-0.05)^2, (0.15)^2, (0.05)^2, (-0.05)^2, (-0.15)^2, (0.05)^2
$$

$$
= 0.0025, 0.0225, 0.0025, 0.0025, 0.0225, 0.0025
$$

$$
\sum (x_i - \bar{x})^2 = 0.0025 + 0.0225 + 0.0025 + 0.0025 + 0.0225 + 0.0025 = 0.055
$$

$$
\sigma = \sqrt{\frac{0.055}{6}} \approx \sqrt{0.009167} \approx 0.096
$$

### e) 72nd Percentile

To find the 72nd percentile, we first need to determine the position in
the ordered list.

$$
\text{Position} = P \times (n + 1) = 0.72 \times (6 + 1) = 0.72 \times 7 = 5.04
$$

Since the position is between the 5th and 6th values in the ordered
list, we need to interpolate between these values (1.4 and 1.5):

$$
\text{72nd Percentile} = 1.4 + 0.04 \times (1.5 - 1.4) = 1.4 + 0.04 \times 0.1 = 1.4 + 0.004 = 1.404
$$

### Summary

- Mean: 1.35
- Median: 1.35
- Mode: 1.3 and 1.4
- Standard Deviation: 0.096
- 72nd Percentile: 1.404