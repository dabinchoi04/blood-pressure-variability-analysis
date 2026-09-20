# Determinants of Blood Pressure Variability

A statistical analysis investigating how physiological and lifestyle
factors are associated with systolic blood pressure using data from the
National Health and Nutrition Examination Survey (NHANES).

## Research Question

How do physiological and lifestyle factors influence systolic blood
pressure variability?

## Overview

This project applies multiple linear regression to examine the relationship
between systolic blood pressure and several physiological and lifestyle
factors:

- Gender
- Age
- Body Mass Index (BMI)
- Alcohol consumption frequency
- Physical activity

The analysis includes regression diagnostics, Box-Cox transformations,
hypothesis testing, variable selection, and influential-point analysis.

## Methodology

The analysis involved:

- Exploratory analysis and regression diagnostics
- Box-Cox transformations
- Variance Inflation Factor (VIF) analysis
- ANOVA and coefficient significance tests
- Partial F-tests
- All Possible Subsets selection
- Forward, backward, and stepwise selection
- Residual and influence diagnostics

## Results

The final model retained four predictors:

- Gender
- Age
- BMI
- Annual alcohol consumption frequency

Physical activity was excluded during model selection.

All automated selection approaches agreed with the manually selected
four-predictor model.

The final model achieved an adjusted R² of approximately 0.183, indicating
that the selected predictors explain a relatively limited proportion of
the variation in the response. The analysis also identified a violation
of the uncorrelated-error assumption, which limits the reliability of
statistical inference from the model.

## Repository Structure

- `analysis/` — R/RMarkdown analysis
- `reports/` — Final report and research poster

## Data

Data are sourced from the National Health and Nutrition Examination
Survey (NHANES).

## Authors

Dabin Choi, Katrina Sha, and Alisha Pham
