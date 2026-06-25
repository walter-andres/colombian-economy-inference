# Colombian Economy Inferential Statistics Study

This repository contains a structured collection of Python notebooks designed to study the Colombian economy using inferential statistics.

The project applies statistical tests and regression-based methods to real economic questions related to Colombia. The main objective is to move from descriptive analysis to statistical inference, allowing us to evaluate whether observed differences, proportions, relationships, and model results are statistically meaningful.

## Project Purpose

This repository is intended as a practical study portfolio for applying inferential statistics to Colombian economic data.

The analysis may use public data sources such as:

- DANE — Departamento Administrativo Nacional de Estadística
- Banco de la República de Colombia
- Other official Colombian economic datasets

The notebooks are organized around common inferential statistics problems, including tests for means, proportions, confidence intervals, regression inference, multilevel models, and marginal models.

## Main Research Focus

The general research question behind this repository is:

> How can inferential statistics be used to analyze, compare, and explain relevant patterns in the Colombian economy?

Examples of possible applications include:

- Comparing unemployment rates between departments or years
- Testing whether inflation or income indicators changed significantly over time
- Comparing economic indicators between independent groups
- Estimating confidence intervals for national or regional economic variables
- Modeling economic outcomes using regression
- Studying department-level or city-level variation with multilevel models
- Applying marginal models to repeated or grouped economic observations

## Repository Contents

The repository includes notebooks for the following inferential statistics topics:

### 1. Mean Difference and Mean Tests

These notebooks focus on testing whether average economic indicators differ across time, regions, or groups.

Topics include:

- Estimating a mean difference for paired data
- Mean difference for two independent groups
- Testing a population mean difference
- One-sample test for means
- Comparing means for two independent samples
- Comparing means on paired data
- Confidence interval for a mean

Possible Colombian economy applications:

- Comparing unemployment rates in the same departments between 2024 and 2025
- Comparing average household income between urban and rural areas
- Estimating the average inflation rate for a specific period
- Testing whether the average GDP growth rate differs from a target value

### 2. Proportion Tests

These notebooks focus on testing population proportions and comparing proportions between groups.

Topics include:

- Test for a population proportion
- Create a population proportion test
- One-sample test for proportions
- Compare proportions for two independent samples

Possible Colombian economy applications:

- Testing whether the proportion of informal workers exceeds a specific threshold
- Comparing the proportion of unemployed people between two regions
- Comparing the proportion of households with internet access across departments
- Testing whether poverty incidence changed between two periods

### 3. Regression Inference

These notebooks apply regression methods to study relationships between economic variables.

Topic included:

- Regression inference for independent data

Possible Colombian economy applications:

- Estimating the relationship between education level and income
- Modeling unemployment as a function of inflation, GDP growth, or regional indicators
- Estimating how household characteristics affect expenditure
- Analyzing the relationship between interest rates and economic activity

### 4. Multilevel Models

These notebooks focus on models where observations are grouped by departments, cities, households, firms, or time periods.

Topics include:

- Multilevel model for continuous dependent variable
- Multilevel logistic regression for binary dependent variable

Possible Colombian economy applications:

- Modeling income while accounting for department-level differences
- Studying unemployment risk across departments
- Estimating regional variation in poverty outcomes
- Modeling whether a household is poor or not using individual and department-level predictors

### 5. Marginal Models

These notebooks apply Generalized Estimating Equations, also known as GEE, for correlated or grouped data.

Topics include:

- Marginal model — GEE for continuous variables
- Marginal model — GEE for binary variables

Possible Colombian economy applications:

- Studying repeated unemployment indicators across departments over time
- Modeling average income trends across regions
- Estimating population-level effects in grouped economic data
- Analyzing binary outcomes such as employment status or poverty status

## Planned Notebook List

The repository is planned around the following notebooks:

1. Estimating a mean difference for paired data
2. Mean difference for two independent groups
3. Test for a population proportion
4. Create a population proportion test
5. Testing a population mean difference
6. Confidence interval for a mean
7. One-sample test for proportions
8. One-sample test for means
9. Comparing means for two independent samples
10. Comparing means on paired data
11. Compare proportions for two independent samples
12. Regression inference for independent data
13. Multilevel model for continuous dependent variable
14. Multilevel logistic regression for binary dependent variable
15. Marginal model — GEE for continuous variables
16. Marginal model — GEE for binary variables

## Suggested Data Sources

The project may use data from:

### DANE

Possible datasets:

- Gran Encuesta Integrada de Hogares — GEIH
- Mercado laboral by department and city
- Poverty and monetary poverty indicators
- Consumer Price Index — CPI / IPC
- National accounts and GDP indicators
- Household surveys

### Banco de la República

Possible datasets:

- Inflation
- Interest rates
- Exchange rates
- Economic activity indicators
- Monetary policy variables
- Financial market indicators

## Methodological Approach

Each notebook should ideally follow this structure:

1. Define the economic question
2. Identify the statistical method
3. Load and clean the data
4. Define the null and alternative hypotheses
5. Run the statistical test or model
6. Interpret the p-value, confidence interval, and effect size
7. Explain the economic meaning of the result
8. Discuss limitations

## Technologies Used

The project is developed mainly with:

- Python
- Jupyter Notebook
- pandas
- NumPy
- scipy
- statsmodels
- matplotlib
- seaborn
- scikit-learn

Additional libraries may be added depending on the specific model or dataset.

## Expected Outcome

By the end of this project, the repository should provide a clear and practical framework for applying inferential statistics to real questions about the Colombian economy.

The final goal is not only to run statistical tests, but also to interpret the results in an economic context and communicate conclusions clearly.

## Repository Status

This repository is under development.

The notebooks will be progressively added, documented, and improved as the Colombian economic case studies are developed.
