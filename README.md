# Psychometrics – Candidate Outcomes Analysis (Public Demo)

This repository contains a public example of an analysis evaluating the **predictive validity** of a psychometric risk assessment (DRA) for recruitment.

### Methods

- **Descriptive statistics** and visual comparisons of risk scores across outcome categories
- **SMOTE** oversampling to address class imbalance in predictive modelling
- **ROC curves** to assess discrimination ability
- **Random forest** modelling for classification and predictor importance

### Important notes

- **All data is fully synthetic** — generated to match realistic distributions, correlations, and broad patterns from the original analysis. No real individual, candidate, or client data is included.
- **Dimension names** have been generalised or renamed to protect intellectual property. The underlying constructs and relationships remain representative.
- Minor differences in subgroup averages or model performance compared to the original analysis are expected due to simulation noise.

![Infographic: Design & Insights Overview](infographic-analysis.png)

### How to view the report

The full rendered report is available via **GitHub Pages**:

→ [View the live report](https://ax-consult-group.github.io/psychometrics-DRA-candidate-outcomes/)

### Technologies used

The analysis was conducted in R using the following packages:

#### Data manipulation & pipelines
- tidyverse
- dplyr

#### Data import & export
- readxl
- writexl

#### Analysis
- psych
- lavaan
- smotefamily
- caret
- pROC
- randomForest
- copula

#### Visualisation & reporting
- ggplot2
- RColorBrewer
- jtools
- knitr
- ggcorrplot

R version 4.5.2 (2025-10-31)
RStudio Version 2026.01.0+392

---

*Last updated: January 2026*
