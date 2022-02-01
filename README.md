# Pewlett-Hackard-Analysis

## Overview 

The goal of this project was to conduct a Database analysis for Pewlett Hackard to determine who will be retiring in the next few years and how many positions the company will need to fill. This information will be used to prepare a plan to hire new staff and prepare a mentorship initiative.  

## Data and Resources

**Downloaded datasets:** 
- departments.csv
- dept_emp.csv
- dept_manager.csv
- employees.csv
- salaries.csv
- titles.csv

**Software:**
- SQL 
- PostgresSQL 
- pgAdmin 

## Results
### Deliverable 1: 
- Using the ERD I created in this module as a reference and my knowledge of SQL queries, I created a Retirement Titles table that holds the titles of employees who were born between January 1, 1952 and December 31, 1955. This table allows us to see every employee eligible for retirement and how long they have worked at each positon over the course of their career. 
-The table is included here: [retirement_titles.csv](https://github.com/jpharvey8/Pewlett-Hackard-Analysis/files/7975256/retirement_titles.csv)

![EmployeeDB](https://user-images.githubusercontent.com/92167429/151896166-28682619-259b-40e7-accb-a4018b603e98.png)
***ERD referenced above***

- The unique titles table I created shows the most recent title for employees of retirement age. 
  [unique_titles.csv](https://github.com/jpharvey8/Pewlett-Hackard-Analysis/files/7975270/unique_titles.csv)


- There are a total of 90,398 employees retiring. Out of those employees leaving there are 32,452 Staff, 29,415 Senior Engineers, 14,221 Engineers, 8,047 Senior Staff, 4,502 Technique Leaders, and 1,761 Assistant Engineers. 
<img width="114" alt="retiring_titles" src="https://user-images.githubusercontent.com/92167429/151897542-62558567-76f6-4a24-b474-7f922171a4df.png">

### Deliverable 2: 
- For deliverable 2, I created a list that includes candidates that can qualify to become a member of the mentorship program. 
[mentorship_eligibility.csv](https://github.com/jpharvey8/Pewlett-Hackard-Analysis/files/7975219/mentorship_eligibility.csv)

## Summary 
Pewlett Hackard is about to have 64% of their employees retire or join their mentorship program. This will require an extensive hiring process in order to keep up productivity to the necessary standards. The mentorship program will allow the senior employees to train the new workforce the skills necessary to fulfiil these roles and have a long, successful career at this company. 
