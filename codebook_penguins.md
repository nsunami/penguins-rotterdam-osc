Codebook created on 2020-10-26 at 2020-10-26 11:43:19
================

## Dataset description

The data contains 344 cases and 8 variables.

## Codebook

| name                | type    |   n | missing | unique |    mean |  median |    mode | mode\_value |     sd |    v |    min |    max |  range |  skew | skew\_2se |  kurt | kurt\_2se |
|:--------------------|:--------|----:|--------:|-------:|--------:|--------:|--------:|:------------|-------:|-----:|-------:|-------:|-------:|------:|----------:|------:|----------:|
| species             | factor  | 344 |    0.00 |      4 |         |         |  152.00 | Adelie      |        | 0.64 |        |        |        |       |           |       |           |
| island              | factor  | 344 |    0.00 |      4 |         |         |  168.00 | Biscoe      |        | 0.61 |        |        |        |       |           |       |           |
| bill\_length\_mm    | numeric | 342 |    0.01 |    165 |   43.92 |   44.45 |   44.45 |             |   5.46 |      |   32.1 |   59.6 |   27.5 |  0.05 |      0.20 | -0.89 |     -1.70 |
| bill\_depth\_mm     | numeric | 342 |    0.01 |     81 |   17.15 |   17.30 |   17.30 |             |   1.97 |      |   13.1 |   21.5 |    8.4 | -0.14 |     -0.54 | -0.92 |     -1.76 |
| flipper\_length\_mm | integer | 342 |    0.01 |     56 |  200.92 |  197.00 |  197.00 |             |  14.06 |      |  172.0 |  231.0 |   59.0 |  0.34 |      1.30 | -1.00 |     -1.90 |
| body\_mass\_g       | integer | 342 |    0.01 |     95 | 4201.75 | 4050.00 | 4050.00 |             | 801.95 |      | 2700.0 | 6300.0 | 3600.0 |  0.47 |      1.77 | -0.74 |     -1.41 |
| sex                 | factor  | 333 |    0.03 |      3 |         |         |  168.00 | male        |        | 0.50 |        |        |        |       |           |       |           |
| year                | integer | 344 |    0.00 |      3 | 2008.03 | 2008.00 | 2008.00 |             |   0.82 |      | 2007.0 | 2009.0 |    2.0 | -0.05 |     -0.20 | -1.51 |     -2.88 |

### Legend

-   **Name**: Variable name
-   **type**: Data type of the variable
-   **missing**: Proportion of missing values for this variable
-   **unique**: Number of unique values
-   **mean**: Mean value
-   **median**: Median value
-   **mode**: Most common value (for categorical variables, this shows
    the frequency of the most common category)
-   **mode\_value**: For categorical variables, the value of the most
    common category
-   **sd**: Standard deviation (measure of dispersion for numerical
    variables
-   **v**: Agresti’s V (measure of dispersion for categorical variables)
-   **min**: Minimum value
-   **max**: Maximum value
-   **range**: Range between minimum and maximum value
-   **skew**: Skewness of the variable
-   **skew\_2se**: Skewness of the variable divided by 2\*SE of the
    skewness. If this is greater than abs(1), skewness is significant
-   **kurt**: Kurtosis (peakedness) of the variable
-   **kurt\_2se**: Kurtosis of the variable divided by 2\*SE of the
    kurtosis. If this is greater than abs(1), kurtosis is significant.

This codebook was generated using the [Workflow for Open Reproducible
Code in Science (WORCS)](https://osf.io/zcvbs/)
