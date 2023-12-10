# Factor-Analysis-in-R
This R script performs factor analysis on a dataset related to a Social and Emotional Learning (SEL) assessment using several R packages, such as psych, EFA.dimensions, dplyr, corrr, irr, lavaan, semPlot, MVN, and others. The analysis involves data preprocessing, correlation analysis, visualization, EFA, CFA, reliability testing and measurement invariance testing.

## Data Loading
1. Loads the SEL dataset from the file "EFAData_EFA.csv".
## Exploratory Data Analysis
1. Conducts univariate and multivariate normality tests using the MVN package (on all scale items).
2. Creates a correlation matrix from the items and visualizes it as a correlogram.
## Pre-Requisite Testing
1. Tests sampling adequacy through Kaiser-Meyer-Olkin (KMO) value and factorisability through Bartlett's test.
## Factor Extraction
1. Extracts information on number of factors using the scree test, parallel analysis, MAP test.
## Exploratory Factor Analysis
3. Extracts factors using Principal Axis Factoring (PAF) with _oblimin_ rotation.
## Reliability Analysis
1. Tests reliability of extracted factors
## Confirmatory Factor Analysis
1. Performs CFA on hypothesised factor structure.
## Measurement Invariance
1. Tests for scale's measurement invariance across gender.

Results obtained from this analysis can be found in the following paper: **Sharma, M., Chheda, S., Piramal, R., Bhatia, N., Frazier, T., & Singh, N. C. (2022). The Social and Emotional Learning and Orientation Scale - Development and Validation of a Brief Measure in Hindi. Journal of Psychoeducational Assessment, 40(5), 571-591. https://doi.org/10.1177/07342829221075517**
