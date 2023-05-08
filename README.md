# Data Analyst and Analyst-Related Job Roles


This is a data analysis project that explores job posts related to data analysts and analyst-related roles from LinkedIn job posts. 
The dataset was sourced from Kaggle and contains information on job titles, companies, job locations, employment types, job categories, salaries and so on.

The project aims to extract insights from the dataset by performing different forms of data cleaning and analyses. The analyses were done using Python libraries such as Pandas, Numpy, Matplotlib, Seaborn, zipfile, glob and others.


## Dataset

The dataset used in this project was sourced from Kaggle and contains information on data analyst and analyst-related job roles from LinkedIn job posts. It consists of over 8,000 job posts and contains the following columns:

- `Title`: The title of the job post.
- `Company`: The name of the company posting the job.
- `Location`: The location of the job.
- `Employment Type`: The type of employment (e.g., full-time, part-time, internship, contract).
- `Onsite_remote`: The type of job category (e.g., on-site, hybrid, remote).
- `Posted_date`: Date the job post feature,
- `link`: Job link post, 
- `Salary`: The salary range offered by the job post.
- `Criteria`: Comprises job functions, level, industries, etc.


## Data Cleaning

The dataset required several forms of data cleaning, which included:

- Removing removing unwanted characters and dealing with null values.
- Standardizing column names.
- Separating salary into minimum and maximum values.
- Removing currency symbols and commas from salary values.
- Converting salary values to float data type
- Carrying out feature engineering by creating derived columns from existing columns to aid analyses


## Analysis

Several analyses were performed on the dataset to extract insights, including:

- The period of job posts for the 3 regions (Africa, Canada and US).
- Companies with most analyst job posts over the period 
- Insights from salaries and companies that pay in the 90 percentile.
- How different regions have job categories (hybrid, remote and on-site) compared.
- The prevailing employment types (contract, full time, internship, etc.).
- Ranks of industries which require data analyst and related roles, the most.
- And many more insights


## Conclusion

This project provides insights into the data analyst and analyst-related job roles from LinkedIn job posts. The analyses performed provide information on job categories, employment types, salaries, and job locations. These insights can be used to guide job seekers in their job search by seeing trends, industries, salary insights and many more.


## Tags

Data Analysis, Pandas, Matplotlib, Seaborn, Kaggle, LinkedIn, Job Posts, Data Cleaning.

