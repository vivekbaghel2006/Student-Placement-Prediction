# Student Placement Prediction

A B.Tech project exploring student placement outcomes through data preprocessing, exploratory data analysis, statistical analysis, and Power BI reporting.

## Project Overview

This project analyses a dataset of 1,500 student records and 17 columns to explore how academic performance and student-engagement indicators relate to placement status.

The submitted notebook performs data inspection and cleaning, creates visualisations, generates a Sweetviz exploratory report, flags unusual records with Isolation Forest, and compares final CGPA between placement groups using one-way ANOVA.

## Objectives

- Inspect and clean the student placement dataset.
- Explore placement distribution and patterns across branches.
- Visualise academic and engagement indicators.
- Generate an automated exploratory data analysis report.
- Identify unusual records for further review.
- Compare final CGPA across placement groups.
- Prepare data for Power BI reporting.

## Tools and Technologies

- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Sweetviz
- scikit-learn (Isolation Forest)
- SciPy (one-way ANOVA)
- Power BI

## Dataset Summary

- Records: 1,500
- Columns: 17
- Placed: 684 (45.6%)
- Not placed: 816 (54.4%)
- Duplicate rows reported before cleaning: 0

The dataset includes branch, previous-semester GPA, attendance, study hours, backlogs, internship completion, coding practice, certifications, internal assessment, communication score, final CGPA, and placement status.

> **Data privacy:** Do not commit raw student-level data or files containing personal or confidential information to this public repository. Share only data that is anonymised and approved for publication.

## Analysis Performed

1. Data loading and inspection
2. Missing-value handling and duplicate check
3. Exploratory visualisations:
   - Placement distribution
   - Placement by branch
   - Final CGPA by placement status
   - Attendance distribution
   - Study hours versus final CGPA
   - Correlation heatmap
   - Branch-wise CGPA and placement percentage
   - Internship, communication, coding practice, and internal assessment comparisons
4. Sweetviz automated EDA
5. Isolation Forest anomaly detection
6. One-way ANOVA for final CGPA across placement groups
7. Cleaned-data export for Power BI

## Key Findings

- The dataset contains 684 placed records out of 1,500 (45.6%).
- Average attendance is approximately 78.43%.
- Average final CGPA is approximately 7.06.
- Isolation Forest flagged 75 records (5%) as unusual for further review.
- The ANOVA test reported an F-statistic of approximately 210.03 and a p-value of approximately 1.22 × 10⁻⁴⁴, indicating a statistically significant difference in mean final CGPA between the two placement groups in this dataset.

These are descriptive/statistical findings from the supplied dataset. They do not establish causation or guarantee an individual student's placement.

## Predictive Modelling Status

The project presentation proposes Logistic Regression, Random Forest, and Gradient Boosting. Model training and evaluation outputs were not present in the submitted executed notebook used to prepare this repository, so no classifier accuracy or best-model claim is reported here.

## Project Files

- `Student_Placement_PBL.ipynb` — executed Python notebook
- `Student_Placement_Project_Report.docx` — project report
- `Student_Placement_Prediction.pptx` — project presentation
- `dashboard.pbix` — Power BI report

Add the files above to the repository after checking that they do not contain confidential student-level information.

## Team

- Atharva Kamthan
- Vivek Singh Baghel

ITM University, Gwalior  
B.Tech CSE (DSML)

## Disclaimer

This is an academic data-analysis project. The results are exploratory and should be interpreted in the context of the dataset and its limitations.
