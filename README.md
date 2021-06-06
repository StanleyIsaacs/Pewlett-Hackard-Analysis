# Pewlett-Hackard-Analysis

## Purpose
### We are helping Pewlett- Hackard prepare for the "silver tsunami' where in we have been tasked with finding the probale number of retiring employees and how many roles will need to be filled. We have been asked to provide a broad number of tables using PostgresSQL. We have been tasked with two main objectives, determine the number of retiring employees by titles and also determine how many managers will need to be replaced and if there are enough managers to mentor eligible employees for a future in management.

## Results:
### Retirees by department: After creating an EDR to map out the connections between the tables we can see (use the below pciture of the EDR and tables for reference)

![EmployeeDB](https://user-images.githubusercontent.com/82114481/120935779-64b5cd00-c6d2-11eb-8280-254b10342e35.png)

[retiring_titles.csv](https://github.com/StanleyIsaacs/Pewlett-Hackard-Analysis/files/6604658/retiring_titles.csv)

[emp_info.csv](https://github.com/StanleyIsaacs/Pewlett-Hackard-Analysis/files/6604659/emp_info.csv)


* 90,398 employees fit the criteria of "retirement" age specified as born bewtween the beginning of 1952 and the end of 1955
* The two most pressing titles to be filled are senior engineer and senior staff 29,414 and 28,254 roles opening up with the "silver tsunami"
* Only two managers are predicted to be retiring. 
* There are 1,549 eligible employees for the mentorship program


## Summary:
### There's a big wave coming:
#### It is time for Pewlett-Hackard to prepare for the "silver tsunami" in a major way with over 90,000 employees nearing the company's predicted retirement age. While not that many managers are getting ready to retire, there are about 1500 employees eligible for the mentorship program. Unfortunately that probably means not enough mentors available for all the potential mentees. Additioanlly I have broken the numbers down by department to see which ones have the most eligible mentors (development and production). Please see that table below as well as the complete table of employees eligible for mentorship.

[eligible_mentors_depts.csv](https://github.com/StanleyIsaacs/Pewlett-Hackard-Analysis/files/6604646/eligible_mentors_depts.csv)

[mentorship_eligibilty.csv](https://github.com/StanleyIsaacs/Pewlett-Hackard-Analysis/files/6604654/mentorship_eligibilty.csv)



