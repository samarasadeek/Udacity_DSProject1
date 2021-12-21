# Udacity_DSProject1

# Description:
There are numerous articles on the gender imbalance in the field of data science. Being a female and looking to break into the field of data science I was interested to see if there has been a change in this imbalance over time and if there are inequalities in different avenues (e.g. salary) that are driving this imbalance. I used the data from Stack Overflow’s 2019, 2020 and 2021 Annual Developer Surveys to gain some insight to being a female  data scientist. 
Available at: https://insights.stackoverflow.com/survey 
1.  What is the most popular developer role based on the 2021 survey results? 
2.	Is there a difference in proportion of females between the field of data science and the most popular developer role from the 2021 survey results?
3.	Have there been changes in the gender and age demographics in the field of data science between 2019 and 2021 survey results?
4.	Within the field of data science, is there a difference in job satisfaction, hours worked, salary between male and females? How has this changed between 2019 and 2020 survey results?

# Files in repository: 
dfY1: Stack Overflow 2019 Annual Developer Survey Results
dfY2: Stack Overflow 2020 Annual Developer Survey Results
dfY3: Stack Overflow 2021 Annual Developer Survey Results

# Libraries used: 
Numpy
Pandas
Matplotlib

# Notes: 
•	Respondents that did not give a gender or selected ‘Prefer not to say’, were dropped from the data set. 
•	Some respondents reported weekly working hours larger than the number of hours in a week (168 hours). Respondents reporting weekly working hours greater than 90 hours (equivalent to around 7 days a week, 13 hours per day) were removed when visualising weekly working hours as these were thought to be errors. 
•	Respondents reporting compensation greater than $bn were deleted when visualising compensation data as these were thought to be errors.

# Results summary: 
1.	There is a higher proportion of female data scientist than full-stack developers (the most popular developer field). 
2.	The age group of young (18 – 24) female data scientist is relatively high and growing. 
3.	Female data scientists work on average the same hours per week and are just as satisfied or more satisfied with their jobs than other respondents.
4.	The compensation gap between women and men has been closing and was as low as $1k in 2020.
