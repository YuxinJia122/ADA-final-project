# Advanced Data Analysis Final Project: ASSOCIATION BETWEEN DURATION OF  PHYSICAL ACTIVITY AND DIABETES AMONG U.S. ADULTS AGED 40 AND OLDER, NHANES 2017–2018

## Project Description
This repository includes the dataset of all the variables (Diabetes,Daily Duration Physical Activity 
,Age (years), Sex, BMI (kg/m²), Race/Ethnicity, poverty level, smoking Status,cardiovascular disease, cancer) used and R markdown code used
to analyze it. 

## Files Included

NHANES 2017–2018 Datasets Used:
- `BMX_J.xpt` – Body Measures data  
- `DEMO_J.xpt` – Demographics data  
- `DIQ_J.xpt` – Diabetes questionnaire data  
- `INQ_J.xpt` – Income data  
- `MCQ_J.xpt` – Medical conditions questionnaire data  
- `PAQ_J.xpt` – Physical activity questionnaire data  
- `SMQ_J.xpt` – Smoking questionnaire data  

 These are the raw NHANES datasets. A cleaned, merged version was created for analysis.

- `ADA_yuxin.Rmd`: R script used to summarize and visualize the data
- `README.md`: This file

## What the Code Does
- Loads multiple NHANES 2017–2018 datasets (BMX_J.xpt, DEMO_J.xpt, DIQ_J.xpt, INQ_J.xpt, MCQ_J.xpt, PAQ_J.xpt, SMQ_J.xpt)
- Cleans and merges the datasets into a single analytic dataset
  - Renames variables for clarity
  - Handles missing or implausible values
  - Converts physical activity variables to hours
- Creates summary statistics for key variables (e.g., age, BMI, physical activity, diabetes status)
- Performs logistic regression analysis to evaluate the association between physical activity and diabetes
- Checks model assumptions (linearity, multicollinearity, influence) and evaluates model fit
- Generates tables and figures for analysis results

## How to Run the Code
1. Download or clone this repository to your computer
2. Place all NHANES `.xpt` files in the same folder as the script
3. Open `analysis_code.R` (or `analysis_code.Rmd`) in RStudio
4. Make sure your working directory is set to the folder containing the files
5. Run the script step by step to clean data, generate summary statistics, and run the regression analyses

## Author
- Name: Yuxin Jia
- Course: Advanced Data Analysis
- Date: 12/2025
