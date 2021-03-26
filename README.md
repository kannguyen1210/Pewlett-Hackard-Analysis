# Pewlett-Hackard-Analysis

## Challenge Overview
In this challenge, we will be using SQL and PostGres database to extract multiple lists of employees to analyze the impact of the upcoming "silver tsunami"  such as how many employees will be retiring and that how many current employees are eligible to mentor the upcoming generation of workforce.

## Resources
- Data source: Please reference the Data folder in the repository
- Queries: Please reference the Queries folder in the repository
- Software/Libraries: PostGresSQL database, SQL Queries

## Challenge Results
![alt text](/Retiring_Titles.png)

As we can see from the screenshot above we have a total of 
- 29414 Senior Engineers
- 28254 Senior Staff
- 14222 Engineer
- 12243 Staff
- 4502 Technique Leader
- 1716 Assistant Engineer
- 2 Manager
Who will be retiring as the "silver tsunami" comes.

Regarding the Mentorship program, we have 1549 eligible current employees to partcipate in the program (reference mentorship_eligibility.csv file).


## Challenge Summary
In addition to the tables created in Deliverable 1 and 2, there are two more tables I have included: "total_retiring_count.csv" and "mentor_by_dept.csv" to have more insight on the impact of the silver tsunami.

Looking at the total number of retiring, we are seeing an astonishing number of 90398 of roles to be filled, meanwhile, we are only having 1549 eligible mentor (please look at the mentor_by_dept.csv for more details regarding the mentors in each department). Therefore, it is clear that we lack the sufficient numbers of mentor and will need to look for alternatives solution on top of in-house mentorship such as out-sourcing the mentoring effort or expand the criteria of eligibility for Mentorship to increase the number.