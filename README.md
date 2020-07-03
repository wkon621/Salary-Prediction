# Predicting Salaries of Future Job Postings

## Introduction
How is a salary for specific job position determined? Is it simply based on experience, industry, years of experience, or is there more to it? I would like to investigate this question using data on present job postings, and their associated salaries. After exploring the data, I will develop a model and plot which features are the most important in determining salaries of newly posted positions. The language of implementation is Python, using packages such as pandas, numpy, matplotlib, seaborn, and sklearn.

## Data Cleaning
This dataset contains one million observations, and variables included are:

 -  company ID: comapny Id in which posts the opening 
 -  job type: level of seniority, such as CEO, CFO, or junior
 -  degree: level of degree, such as Phd, Masters, Bachelors or None
 -  major: university major included in job description
 -  industry: industry in which the company operates in
 -  experience: number of years of experience required for the listed job
 -  distance: number of miles away from major city
 -  salary (target): posted salary in a job posting
  
Although the data is relatively clean, I deleted 5 observations becasue salary is listed 0. I kept the outliers because less than 1% of data points. 
