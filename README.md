# Health Sciences & Clinical Psychometry Data Analyses

This repository contains two end-to-end data analysis case studies conducted for empirical research projects in the fields of occupational health and physical therapy (associated with Adam Mickiewicz University / AWF research cohorts). 

The projects demonstrate practical skills in **data cleaning, data wrangling, psychometric index calculation, statistical hypothesis testing, and data visualization** using Python.

---
## Project 1: Occupational Stress, Anxiety, and Gastrointestinal Symptoms ##

Objective: Investigate the relationship between generalized anxiety (GAD-7), perceived occupational stress (PSS-10 / Work Stress Score), and gastrointestinal discomfort symptoms (GSRS) across diverse professional positions.

Key Analysis Steps:
Data Wrangling: Handled missing values, mapped Likert scales to numeric scores, and reversed items for standardized psychometric instruments (GAD-7, GSRS, PSS-10).

Statistical Testing:

Pearson Correlation: Evaluated relationships between generalized anxiety, work stress, and somatic gastrointestinal symptoms.

Welch’s t-Test: Compared stress scores across subgroups based on biochemical diagnostics (cortisol tests).

Chi-Square Test: Examined associations between weekly physical activity and job roles.

Key Findings:

Strong positive correlation between generalized anxiety (GAD-7) and gastrointestinal discomfort (r=0.585,p<0.001).

Moderate correlation between work stress and gastrointestinal symptoms (r=0.430,p=0.004).

## Project 2: Physical Activity vs. Lower Back Pain & Mobility in Pregnancy##


Objective: Assess the impact of physical activity volume (calculated in minutes/week based on WHO guidelines) on low back pain disability (Roland-Morris Disability Questionnaire - RMDQ) and pain intensity (VAS scale) among pregnant women.

Key Analysis Steps:
Feature Engineering: Calculated weekly activity volume (min_tydz) by multiplying frequency midpoint and duration midpoint. Categorized participants into WHO compliance groups (≥150 min/week).

Clinical Index Calculation: Automatically summed 24 binary items to construct the RMDQ disability score.

Statistical Testing:

Kruskal-Wallis Test & Spearman Rank Correlation: Analyzed differences in pain and disability across physical activity tiers and trimesters.
