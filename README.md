# Data Science Project 5: Data Preparation

## Overview
This project demonstrates efficient data cleaning and feature engineering for a large anonymized student dataset. The goal is to prepare the data for predictive modeling, specifically to identify students looking for a new job.

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
- Filter data using business logic
- Inspect and validate the final dataset

## How to Run
1. Install requirements:
   ```bash
   pip install -r pandas
   ```
2. Open `notebook.ipynb` in Jupyter or VS Code and run all cells.

## Requirements
pandas

## Core Concepts
- Data cleaning
- Data type optimization
- Feature engineering
- Data transformation
- Filtering and selection
- Exploratory data analysis

## Author
Alaeddin-B
