# An Analysis of Pewlett Hackard Employees

Analysing Data from Pewlett Hackard to find out which employees are eligible for either retirement or mentoring other employees

## Resources

- Data:
  - departments.csv
  - dept_emp.csv
  - dept_managers.csv
  - employees.csv
  - salaries.csv
  - titles.csv
- Software:
  - PostgreSQL 14.4
  - pgAdmin 4

## Overview

In preperation for a wave of retirements, we have been tasked with determining the number of employees per title that are retiring. From there, we also determined the number of employees eligible to shift to part time work while mentoring other employees.

## Results

| Number of Employees   | Title  |
| :-------------------: | -----  |
| 25,916 	|  Senior Engineer     |
| 24,926  |  Senior Staff        |
| 9,285   |  Engineer            |
| 7,636   |  Staff               |
| 3,603   |  Technique Leader    |
| 1,090   |  Assistant Engineer  |
| 2       |  Manager             |

- Number of Employees Retiring by Title
  - Out of the 72,458 total employees eligible for retirement, majority of the employees are Senior-level staff (50,842 employees or 70.17%)
  - 68,853 retirement eligible employees are Engineers and Staff, which makes up 95.02% of the retiring employees

[Link to the Mentorship Program Employee list](https://github.com/bradleywb426/Pewlett-Hackard-Analysis/blob/main/Data/mentorship_eligibility.csv)

- Employees Eligible for the Mentorship Program
  - Of the 1549 employees eligible for the mentorship-program, 1026 employees (or 66.24%) have had their position since the 1990's, meaning they've had the position for 20 to 30 years
  - Engineers make up 74.11%, which is 1,148 employees, of the employees eligible for the mentorship-program

## Summary 

### How many roles will need to be filled?

By the end of this wave of retirement, 72,458 positions will need to be filled full-time due to retirements. An additional 1,549 positions will be requiring at least part-time fulfillment as current retirement-eligible employees agree to shift to mentor roles, assuming all employees eligible for the mentorship program agree to participate.

### Are there enough employees to mentor the next generation of Pewlett Hackard employees?

No, there are not enough potential mentors to foster the new employees. As it stands, each mentor would have approximately 47 students to be responsible for, which is too high of a margin.

Provide high-level responses to the following questions, then provide two additional queries or tables that may provide more insight into the upcoming "silver tsunami."

### Further Queries

To better gauge the effect of the upcoming retirement wave:

- The breakdown of retiring employees by birth year can be insightful, as it can help show if more employees are likely to retire at the start, end, middle, or spread throughout the wave. Knowing this can inform how to hire the new employees and if it would be possible to have mentors train new hires in multiple rounds. This would increase the number of mentored hires while keeping the number of new hires lower for mentors at a given time.

- Looking at the breakdown by department, such as in the [retirements by department table](https://github.com/bradleywb426/Pewlett-Hackard-Analysis/blob/main/Data/dept_retire.csv), can give insight into what departments will be hit the hardest and where to focus hiring efforts on. This could then be further utilized by applying the previous query (retirements by year) with retirements by department to see approximately when each department will be hit and how severe. This can allow for a far more dynamic hiring and mentoring strategy.
