# AI_MI_Intern_T15
# Anscombe's Quartet Dataset Summary

## Overview

This dataset, known as **Anscombe's Quartet**, was constructed in 1973 by the statistician Francis Anscombe. It consists of four datasets that have nearly identical simple descriptive statistical properties, yet appear very different when graphed. It is a classic example used in data science to demonstrate the importance of **data visualization** and the effect of outliers on statistical properties.

## File Structure

The file `anscombe.csv` contains 44 observations and 3 columns:

| Column | Data Type | Description |
| --- | --- | --- |
| `dataset` | Categorical (String) | Identifier for the quartet subset (I, II, III, or IV). |
| `x` | Numerical (Float) | The independent/input variable. |
| `y` | Numerical (Float) | The dependent/target variable. |

## Key Statistical Properties

Across all four datasets (I, II, III, and IV), the following statistical properties are almost identical:

* **Mean of **: 
* **Variance of **: 
* **Mean of **: 
* **Variance of **: 
* **Correlation between  and **: 
* **Linear Regression Line**: 

## Dataset Characteristics

Despite the identical statistics, each subset tells a different story:

1. **Dataset I**: Fits a linear relationship with some variance.
2. **Dataset II**: Follows a distinct non-linear (quadratic) curve.
3. **Dataset III**: A perfect linear relationship interrupted by one significant outlier.
4. **Dataset IV**: Shows no relationship except for one extreme outlier that forces a high correlation.

## Usage

This dataset is ideal for:

* Testing the robustness of machine learning models.
* Demonstrating the necessity of Exploratory Data Analysis (EDA).
* Practicing data preprocessing (scaling/encoding) and regression pipelines.
