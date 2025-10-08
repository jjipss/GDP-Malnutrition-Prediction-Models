#  GDP + Malnutrition Prediction Models

# Overview

This project develops and evaluates statistical and machine learning models to predict child wasting prevalence using GDP and other socio-economic/environmental factors. The motivation is to investigate whether national economic indicators can serve as effective predictors of malnutrition, and to identify patterns that may support public health interventions and policy-making.

# Why It Matters

Child wasting is a serious public health issue, and while GDP often gets used as a quick measure of a country’s well-being, it doesn’t always reflect the full picture. By digging into the data, I wanted to see where GDP works as a predictor, and where it falls short.

# The Data

From: WHO, UNICEF, FAO, plus some scraped GDP data to fill in gaps.
Targets:
- GDP per capita (economic outcome).
- Child wasting prevalence (% of children under 5 affected by wasting).

# The Approach

Here’s what we did step by step:

1. Cleaned the data → handled missing values, grouped countries by region, and transformed variables when needed.
2. Built models → Linear Regression (baseline), Random Forest, and Polynomial Regression.
3. Evaluated results → used R², RMSE, and compared regional vs location-based models.

# What We Found

- GDP alone explains a lot, but not enough.
- Adding environmental and regional features gave much stronger results.
- Random Forest performed best, hitting ~94% accuracy for GDP prediction and ~77% for malnutrition.
- Regional models revealed big differences across the world, showing that context matters.

# How to Use This Notebook

1. Clone this repo.
2. Open GDP:ChildWasting_Model.ipynb in Jupyter.
3. Run all cells to reproduce the results.

