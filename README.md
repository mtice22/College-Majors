# Introduction
This project is based on a Five Thirty-Eight article that used college major data to find the highest paying majors. 

Five Thirty-Eight article: https://fivethirtyeight.com/features/the-economic-guide-to-picking-a-college-major/ 

The original article only ranked the highest and lowest median salaries. With so much valuable data, there is room for a lot more analysis. This project uses SQL and Python to visualize and rank majors in a variety of ways:
  - Percentage of women vs median income
  - Median salaries by women-dominated 
  - Unemployment rates by major
  - Degrees and their percentage of jobs that require college degrees
  

# Description

| Command | Description |
| --- | --- |
| `rank` | Rank by median earnings |
| `major` | Major description |
| `major_category` | Category of major from Carnevale et al |
| `median` | Median earnings of full-time, year-round workers |
| `total` | Total number of people with major |
| `men` | Male graduates |
| `women` | Female graduates |
| `sharewomen` | Women as share of total |
| `employed` | Number employed (ESR == 1 or 2) |
| `unemployed` | Number unemployed (ESR == 3) |
| `unemployment_rate` | Unemployed / (Unemployed + Employed) |
| `college_jobs` | Number with job requiring a college degree |
| `noncollege_jobs` | Number with job not requiring a college degree |
| `rate_noncollege_jobs` | Noncollege / (Noncollege + College) |
| `rate_college_jobs` | College / (Noncollege + College) |
| `sharemen` | Men as share of total |


# Programs Used
MySQL, Python 3.7.2

Due to how MySQL functions, the file "raw data.txt" does not have the feature names as it is much easier to manually enter them in MySQL Workbench 8.0. 
