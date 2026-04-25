# MajorProject
# Alumni Placement Analysis — IIT Bhilai 2025
### Data Analytics and Visualization — Major Project

## Overview
This project performs end-to-end data analytics on the IIT Bhilai
Alumni Placement Dataset (2025), covering 260 alumni records across
21 disciplines and 6 programme types.

## Project Structure
├── Alumnidata2025.xlsx        # Raw dataset (source file)
├── alumni_cleaned.csv         # Cleaned dataset (output of step1)
├── datacleaning.ipynb          # Data cleaning and preparation
├── eda.py               # Exploratory data analysis (8 plots)
├── modeLl.ipynb             # Linear & Polynomial Regression model
├── dashboard.html             # Interactive dashboard (open in browser)
├── plot_model.png             # Regression model visualizations
└── Student Placement Analysis Report.docx # Final project report

## Dataset
- Source  : IIT Bhilai Training & Placement Cell
- Records : 260 alumni
- Columns : 18 (after cleaning)
- Key fields: Course, Discipline, Status, Company, Role, Location

## Models Applied
- Linear Regression    : R² = 0.8416  RMSE = 3.2342
- Polynomial Regression: R² = 0.8938  RMSE = 2.6491
- Target: Predict placement count per discipline from cohort size

## Tools Used
Python, Pandas, NumPy, Matplotlib, Seaborn, Plotly, Scikit-learn
