# A/B Testing & Hypothesis Testing

## Project Overview

This project analyzes an A/B testing experiment to compare the
conversion performance of Variant A and Variant B.

## Dataset

- Total Visitors: 1,200
- Variant A: 600 users
- Variant B: 600 users
- Total Conversions: 128

## Results

| Metric | Variant A | Variant B |
|---|---:|---:|
| Users | 600 | 600 |
| Conversions | 57 | 71 |
| Conversion Rate | 9.50% | 11.83% |

## Hypothesis Testing

### Two-Proportion Z-Test
- Z-statistic: 1.309
- P-value: 0.190

### Chi-Square Test
- Chi-square statistic: 1.478
- P-value: 0.224
- Degrees of freedom: 1

## Conclusion

Variant B showed a higher observed conversion rate than Variant A.
However, both statistical tests produced p-values greater than 0.05.
Therefore, there is insufficient statistical evidence to conclude that
the observed difference in conversion rates is statistically significant.

## Tools Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- SciPy
- Statsmodels

