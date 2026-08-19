# Breast Cancer Diagnostics Model

# Project Overview

This project focuses on understanding EDA, machine learning model development, testing, and evaluating performance on the UCI Breast Cancer Wisconsin (Diagnostic) data set.

## Python Packages Used

- **Data Manipulation & Statistical Analysis:** pandas, numpy, scipy.stats, math
- **Data Visualization:** matplotlib
- **Machine Learning:** scikit-learn

# Data

This project utilizes UC Irvine Machine Learning Repository's [Breast Cancer Wisconsin (Diagnostic](https://archive.ics.uci.edu/dataset/17/breast+cancer+wisconsin+diagnostic) data set. It contains 32 features relating to radius, texture, perimeter, area, smoothness, compactness, concavity, concave points, symmetry, and fractal dimension measurements of malign and benign breast masses.

## Exploratory Data Analysis

Determined the independence (or lack there of) of features with the target, as well as how the features are distributed.

![](https://github.com/aidandig/dx601-final-project/blob/main/images/feature%20correlation%20matrix.png)

## Exploring the Value of Principal Components Analysis

Performed PCA analysis on the features to determine the explained variance on the first half of the principal components, then built a linear regression model using the coordinates.
  - The result was that the linear regression model using the first half principal components had a significantly lower MSE than the original linear regression model.

## Exploring Outlier Detection Methods

Identified outliers on a per-feature basis utilizing Z-Score with Median Absolute Deviation due to the not normally distributed data.

![](https://github.com/aidandig/dx601-final-project/blob/main/images/outlier%20detection%20example.png)

# What I learned from this project

I developed a better understanding of understanding data by exploring feature distribution, correlation, and other statistical checks to perform EDA. Another significant insight was understanding how to apply outlier detection techniques.

# Citation
Wolberg, W., Mangasarian, O., Street, N., & Street, W. (1993). Breast Cancer Wisconsin (Diagnostic) [Dataset]. UCI Machine Learning Repository. [https://doi.org/10.24432/C5DW2B](https://doi.org/10.24432/C5DW2B).

# License

The data set from this project is licensed under a [Creative Commons Attribution 4.0 International (CC BY 4.0) license](https://creativecommons.org/licenses/by/4.0/legalcode). It allows for the sharing and adaptation of the datasets for any purpose, provided that the appropriate credit is given.
