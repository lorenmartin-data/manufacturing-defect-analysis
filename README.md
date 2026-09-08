# Manufacturing Defect Analysis

## Project Overview

This project analyzes manufacturing defects in electronic board production to identify the production models and defect categories contributing most heavily to quality issues. The analysis combines exploratory data analysis, Power BI visualization, root-cause analysis, and statistical hypothesis testing to support process-improvement decisions.

## Business Objective

The organization sought to reduce welding-related defects by 20% while supporting a 20% increase in production capacity without increasing the overall defect percentage.

## Tools and Technologies

- Power BI
- Python
- Pandas
- SciPy
- Jupyter Notebook
- Statistical Hypothesis Testing
- Pareto Analysis
- Root-Cause Analysis

## Analytical Approach

The project followed an end-to-end analytical process that included:

1. Identifying the production models responsible for the highest defect volumes.
2. Analyzing defect categories within the highest-defect models.
3. Using Pareto analysis to identify priority areas for improvement.
4. Developing a fishbone diagram to organize potential operational contributors.
5. Performing a one-way ANOVA to evaluate whether mean defect frequency differed significantly among the three highest-defect production models.
6. Developing a Power BI dashboard to communicate findings and recommendations.

## Key Findings

- Production Models 595130, 595214, and 595242 accounted for approximately 69% of the defects analyzed.
- Model 595130 showed a greater concentration of assembly and component-placement defects.
- Models 595214 and 595242 showed more prominent soldering-related defect patterns.
- The one-way ANOVA produced a p-value of approximately 0.565, providing insufficient evidence that mean defect frequency differed significantly among the three production models.
- The combined findings supported a broader process-improvement approach while continuing to monitor model-specific defect patterns.

## Recommendations

The analysis identified four initial process-improvement priorities:

- Standardize work instructions and assembly procedures.
- Review soldering equipment performance, maintenance, and process controls.
- Strengthen targeted employee training and inspection consistency.
- Continue monitoring defects by production model and defect category using the Power BI dashboard.

## Repository Contents

- `notebooks/` — Python and Jupyter analysis
- `power-bi/` — Power BI dashboard files
- `images/` — Dashboard screenshots and project visualizations
- `presentation/` — Final project presentation
- `data/` — Information regarding the project dataset

## Data Note

The original course-provided dataset is not included in this repository.

## Project Background

This analysis was originally developed as part of an applied data analysis course and has been reformatted and expanded as a professional portfolio case study.
