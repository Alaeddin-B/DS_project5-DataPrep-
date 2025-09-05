# Data Preparation and EDA of Job Applicants Data

## Overview
This project demonstrates efficient data cleaning, feature engineering, and exploratory data analysis for a large anonymized student dataset. The goal is to prepare the data for predictive modeling, specifically to identify students looking for a new job.

## Dataset
- **customer_train.csv**: Contains anonymized student information and job change status.

| Column               | Description                                      |
|----------------------|--------------------------------------------------|
| student_id           | Unique ID for each student                       |
| city                 | City code                                        |
| city_development_index| Scaled development index for the city            |
| gender               | Student's gender                                 |
| relevant_experience  | Work relevant experience indicator               |
| enrolled_university  | Type of university course enrolled in            |
| education_level      | Student's education level                        |
| major_discipline     | Educational discipline                           |
| experience           | Total work experience (years)                    |
| company_size         | Number of employees at current employer          |
| company_type         | Type of company employing the student            |
| last_new_job         | Years between current and previous jobs          |
| training_hours       | Hours of training completed                      |
| job_change           | Whether the student is looking for a new job     |

## Workflow
- Handle missing values with context-appropriate replacements
- Convert columns to efficient types (category, bool, int32, float16)
- Engineer features (ordered categoricals, binary conversion)
- Visualize distributions and relationships using Seaborn and Matplotlib
- Filter and analyze data using business logic
- Inspect and validate the final dataset

## Visualizations
- Bar plots, count plots, boxplots, violinplots, and 2D histograms
- Feature mixing: e.g., education level vs. job change, company size vs. job change
- Colorful plots using Seaborn palettes (Set2, Set3, tab20)
- Custom legend placement and plot formatting

## How to Run
1. Install requirements:
   ```bash
   pip install -r requirements.txt
   ```
2. Open `notebook.ipynb` in Jupyter or VS Code and run all cells.

## Requirements
See `requirements.txt` for dependencies.

## Core Concepts
- Data cleaning
- Data type optimization
- Feature engineering
- Data transformation
- Data visualization
- Filtering and selection
- Exploratory data analysis

## Author
Alaeddin-B
