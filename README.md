# Glassdoor Data Science Jobs - Data Cleaning

## Project Overview
This project involves cleaning a raw dataset of data science job postings scraped from Glassdoor. The goal was to transform messy, unstructured data into a clean, analysis-ready format using Python and pandas.

## Dataset
- **Source:** [Data Science Job Posting on Glassdoor](https://www.kaggle.com/datasets/rashikrahmanpritom/data-science-job-posting-on-glassdoor) by Rashik Rahman on Kaggle
- **License:** CC0 Public Domain

## Tools Used
- Python
- pandas
- numpy
- Jupyter Notebook
- openpyxl

## Cleaning Steps
1. Renamed columns for consistency and readability
2. Cleaned `salary_estimate` — removed Glassdoor est., `$`, `K`, split into `min_salary` and `max_salary`
3. Cleaned `company_name` — removed appended `\n` and rating numbers
4. Cleaned `job_description` — removed `\n` characters
5. Replaced `-1` values with `NaN` in `rating`, `founded`, `type_of_ownership`, `industry`, `competitors`
6. Cleaned `type_of_ownership` — removed dashes and extra spaces
7. Cleaned `revenue` — removed `$` signs and replaced unknown values with `NaN`
8. Reordered columns and exported to Excel

## Output
- `data cleaning.xlsx` — fully cleaned dataset ready for analysis

