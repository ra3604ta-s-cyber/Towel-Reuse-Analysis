# Towel-Reuse-Analysis

This project investigates whether a social norm intervention increases towel reuse in hotels.

## Method

A hierarchical binomial regression model is used:

`p(reuse, total) ~ intervention + (1 | study)`

The model accounts for differences between studies using study-level random intercepts.

## Results

The analysis provides strong evidence of a positive intervention effect. The estimated odds ratio is approximately 1.24.

## Reproducibility

The complete analysis is provided in the Jupyter Notebook and implemented in Python using Bambi/PyMC.
