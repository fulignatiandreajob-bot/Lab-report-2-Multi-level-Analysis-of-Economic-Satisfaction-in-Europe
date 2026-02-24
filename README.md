# Lab-report-2-Multi-level-Analysis-of-Economic-Satisfaction-in-Europe
## Abstract
This study investigates the relationship between macro-economic contexts—specifically income inequality and regional unemployment—and individual satisfaction with the national economy. Using data from the European Social Survey (ESS), we apply three-level linear mixed models to account for the nested structure of individuals within regions and countries.

##Hypothesis
**H1:** Higher country-level income inequality (Gini index) is associated with lower satisfaction with the current state of the economy.
**H2:** Higher regional unemployment rates are associated with lower satisfaction with the state of the national economy.
The theoretical framework suggests that both national-level inequality and immediate regional economic conditions (unemployment) shape an individual's perception of economic performance.

##Methodology
The analysis proceeds in four steps:
1. **Descriptive Statistics:** An overview of Gini, regional unemployment, GDP per capita, and individual-level controls (Age, Education, Income, etc.).
2. **Empty Model (Null Model):** Calculation of the Intraclass Correlation Coefficient (ICC) to determine the variance explained by regional and national levels.
3. **Multilevel Model (LMM):** A comprehensive three-level regression including individual, regional, and national predictors.
4. **Predicted Values:** Calculation and visualization of the predicted marginal effects for the focal independent variables (Gini and Unemployment).


##Data
The analysis uses the European Social Survey (ESS11) dataset.
**Dependent Variable:** Satisfaction with the Economy (stfeco), measured on a 0–10 scale.
**Independent Variables:**
1. Gini Index: Country-level income inequality (2024).
2. Regional Unemployment: Percentage of unemployed persons by region (2024).
**Controls:**
- Contextual: GDP per capita (2023).
- Individual: Age, Gender, Years of Education, Born in Country, Personal Unemployment Status, and Household Income deciles.

##Key Findings Snapshot
**H2 Supported:** Regional unemployment has a significant negative effect on satisfaction (b=−0.045,p<0.05).
**H1 Partially Observed:** The Gini index showed a negative trend (b=−0.066) but was marginally non-significant (p=0.079).
**ICC:** 17% of the variability is explained by the contextual (regional and national) levels.
