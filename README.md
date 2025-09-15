# Assessing the Risk Factors Associated with Parkinson's Disease

This repository contains materials for the project "Assessing the Risk Factors Associated with Parkinson's Disease". The project investigates the relationships between various risk factors (e.g., age, BMI, cognitive measures, motor symptoms, and lifestyle factors) and Parkinson's Disease diagnosis. By employing statistical analysis and machine learning, we aim to provide insights that can aid healthcare decision-making and early intervention strategies.

## Project Overview

**Objective:** Investigate the impact of clinical and behavioral factors on Parkinson's Disease risk and identify patterns for healthcare interventions.

**Data Source:** Kaggle Parkinson's Disease Dataset Analysis.

**Key Models:** Logistic Regression, Cluster Analysis, Statistical Testing.

**Results:** The Cognitive and Functional Assessments cluster achieved the highest predictive performance (AUC = 0.7859), with the combined model reaching 82.6% accuracy (AUC = 0.8261).

## Files in the Repository

- `parkinsons_analysis.Rmd`: R Markdown Notebook containing the full data analysis, statistical tests, and predictive modeling workflows.
- `project_report.pdf`: A comprehensive project report summarizing the methodology, results, and key insights.
- `presentation.pdf`: The detailed project presentation outlining the methodology, data analysis, statistical results, and model performance.

## Methodology

### Data Preprocessing:
- Handling missing values and duplicates verification.
- Transforming categorical and numerical data.
- Normality testing using Shapiro-Wilk test.
- Feature normalization for comparability.

### Descriptive Statistics:
- Analyzed distributions of UPDRS, MoCA, age, and demographic factors.
- Computed summary statistics for all variable clusters.

### Exploratory Data Analysis:
- Visualized relationships between independent variables and Parkinson's diagnosis.
- Created correlation matrices and heatmaps for deeper insights.

### Statistical Analysis:
- Performed Mann-Whitney U tests for continuous variables.
- Conducted Chi-Square tests to evaluate associations between categorical factors and diagnosis.
- Applied Spearman correlation analysis for non-normal data.
- Verified statistical significance of key variables.

### Predictive Modeling:
- Trained and evaluated logistic regression models by cluster:
  - Demographics
  - Lifestyle Factors
  - Medical History
  - Clinical Measures
  - Cognitive and Functional Assessments
  - Symptoms
- Assessed model performance using Pseudo R², AUC, and confidence intervals.

## Key Findings

- Strong correlations were found between Parkinson's diagnosis and factors like UPDRS scores, MoCA scores, tremor, and rigidity.
- The Cognitive and Functional Assessments cluster outperformed other clusters, achieving AUC = 0.7859, indicating strong predictive performance.
- The combined model with UPDRS, MoCA, Tremor, Rigidity, and Age achieved the highest accuracy (AUC = 0.8261).
- Clinical measures like blood pressure and cholesterol showed moderate associations with diagnosis.

## Contributors

- Faizan Hussaini
- Sri Ramya Panja
- FNU Sahrash Fatima
- Yesseswini Yenigandla

## Contact

For questions or suggestions, please contact:
Sri Ramya Panja - [@sriramyapanja](https://github.com/sriramyapanja)

## About

Analyzes Parkinson's Disease risk factors using statistical analysis and machine learning, identifying key predictors like UPDRS and MoCA scores for early intervention and improved diagnostic accuracy.

**Course:** FA24 Applied Statistical Methods in Biomedical Informatics (B518: 27340)  
**Group 3**
