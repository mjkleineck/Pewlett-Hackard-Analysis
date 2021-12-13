# Pewlett-Hackard Analysis

## Overview
The purpose of this analysis is to determine the number of retiring employees per title, and identify employees who are eligible to participate in a mentorship program. This analysis includes recommendations for Pewlett-Hackard to navigate its "silver tsunami” as many current employees reach retirement age.

## Results
* There are 90,398 total employees set to retire.
* 57,688 of those retiring have a Senior designation in their title.
* Only 2 managers are set to retire.
* Only 1,549 employees are eligible for the mentorship program.

## Summary
### How many roles will need to be filled as the "silver tsunami" begins to make an impact?
Below is the query ran to calculate the the number of positions needing to be filled.

![Number of open positions](https://github.com/mjkleineck/Pewlett-Hackard-Analysis/blob/main/Queries/retiring_emp.png)

The total number of employees retiring is 90,398.

### Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?
The follow query will return the total number of eligible mentors by position.

![Number of eligible mentors](https://github.com/mjkleineck/Pewlett-Hackard-Analysis/blob/main/Queries/mentorship_emps.png)

![Mentor title breakdown](https://github.com/mjkleineck/Pewlett-Hackard-Analysis/blob/main/Data/mentor_titles.png)

With the current mentorship parameters, there are only 1,549 employees that would be eligible to be a mentor. That's a large ratio of open positions to be filled to mentors. Perhaps adjusting the parameters to be a mentor from employee's date of birth to the number of years in the employee's position would yield a wider rage of eligible mentors.
