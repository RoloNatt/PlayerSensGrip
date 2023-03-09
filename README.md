# PlayerSensGrip

## Insights

### box plots generated for grip styles - claw, fingertip, palm

Median: The median 'eDPI' value for the claw grip is around 1200, which is higher than the median values for both the palm and fingertip grips (around 1100 and 900, respectively). 
> Players who use a claw grip tend to use a higher 'eDPI' value than players who use palm or fingertip grip.

Interquartile range (IQR): The IQR for the claw grip is wider than the IQRs for both the palm and fingertip grips. 
> 'eDPI' for claw grip is more spread out than other grips.

Outliers: There is one outlier in the fingertip grip, with an 'eDPI' value of 1200. There is also one outlier in the palm grip, with an 'eDPI' value of 2250.
> There may be some players who use very high or very low 'eDPI' values, regardless of their grip type.

Range: The range of 'eDPI' values for the claw grip is the widest, with the lowest value at around 300 and the highest value at around 1900. The range for the palm grip is narrower, with the lowest value at around 800 and the highest value at 2250. The range for the fingertip grip is the narrowest, with the lowest value at around 900 and the highest value at 1200.
___________________________________________________________________

### Box plots generated for playstyle - aim, movement

> Movement Players prefer higher sensitivity while the Aim Players prefer lower sensitivity.

### Count plot

> Movement players prefer to play on a stretched resolution.

### Histogram

![image](https://user-images.githubusercontent.com/15999442/223740170-f035e076-d19a-4e8f-a0c3-440b1ac3441c.png)

Also, using Shapiro-Wilk test

> The distribution is **Normal**

### Confidence Intervals
p=0.85, mean = 1109.14 ± 84.05
p=0.90, mean = 1109.14 ± 96.36
p=0.95, mean = 1109.14 ± 115.53

### Hypothesis Testing

![image](https://user-images.githubusercontent.com/15999442/223740627-e83fe879-4de0-4d92-8f8d-cb1b7fc4c0d1.png)

#### Student t-test
t-value: -0.25
> The negative t-value indicates that the mean 'eDPI' value for the 'claw' group is slightly lower than that of the 'palm' group, but this difference is not statistically significant. Therefore, we cannot conclude that one grip type is better than the other based on this data.

p-value: 0.8060187480194614
> Since the p-value is greater than the commonly used significance level of 0.05, we cannot reject the null hypothesis that the means of the two groups are equal. In other words, there is not enough evidence to suggest that the difference between the mean 'eDPI' values of the two grip types is statistically significant.

### Covariance & Correlation

- between DPI and eDPI

Covariance matrix:
[[376666.66666667  48716.66666667]
 [ 48716.66666667 128949.33333333]]
 
Covariance: 48716.66666666667
> The covariance between 'DPI' and 'eDPI' is 48716.6667, indicating a positive relationship between the two variables.

Correlation: 0.22104944050197176
> The correlation coefficient between 'DPI' and 'eDPI' is 0.221, which also suggests a positive, but weak relationship between the two variables. Since the correlation is less than 0.5, it can be interpreted as a weak correlation.



The correlation coefficient between 'Grip' and 'eDPI' is 0.221, which also suggests a positive, but weak relationship between the two variables. Since the correlation is less than 0.5, it can be interpreted as a weak correlation.
