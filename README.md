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

We have been tasked with determining the number of employees per title that are retiring, as well as find employees that are eligible to participate in mentoring other staff members.

## Results

Provide a bulleted list with four major points from the two analysis deliverables. Use images as support where needed.

## Summary 

Provide high-level responses to the following questions, then provide two additional queries or tables that may provide more insight into the upcoming "silver tsunami."
How many roles will need to be filled as the "silver tsunami" begins to make an impact?
Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?

--------------

## Overview

V. Isualize has tasked us with analyzing the relationship between city types and how Pyber usage differs amongst the city types. First, we had to create and provide a Dataframe for our analysis, and then make a line plot illustrating the differences.

## Results

The first aspect of our Pyber Analysis involved creating a DataFrame of Pyber data (Total Rides, Total Drivers, Total Fares, Average Fare per Ride, Average Fare per Driver) that was grouped by different city types (Rural, Suburban, and Urban). The DataFrame is listed below, and contains the data discussed below.

<img src="">

### Total Rides

  There are a total of 125 rides in Rural-type cities, which is the smallest total number of rides of all city types. Suburban cities have 625 rides total, which is 5 times as many rides as in Rural-type cities. Urban-type cities have a total of 1,625 rides, which is 13 times as many rides in Rural-type cities and 2.6 times as many rides as Suburban-type cities. Therefore, Urban-type cities have the most total rides. 

### Total Drivers

  In Rural-type cities, there are a total of 78 drivers, which is the smallest number of drivers of all city types. For Suburban-type cities, there are a total of 490 drivers, which is about 6.3 times as many drivers as Rural-type cities. Urban cities have a a total of 2,405 drivers, which is about 30.8 times as many drivers as Rural-type cities and about 4.9 times as many drivers as Suburban-type cities. Therefore, Urban-type cities have the largest total number of drivers.

### Total Fares

  Rural cities have the lowest total fares, with a total of $4,327.93 in total fares. In Suburban-type cities, the total fare is $19,356.33, which is around 4.5 times greater than total fares in Rural cities. Urban-type cities have a total of $39,854.38 in fares, which is about 2.1 times the total fares for Suburban cities and about 9.2 times the total fares of Rural cities. Therefore, Urban-type cities have the largest total fares.

### Total Fares (Monthly)

The total fares for each city type can also be observed as monthly totals for each city type till the end of April, as seen in the line plot below. From the plot, it can be seen that total fares in Urban cities are always the greatest, total fares in Suburban cities are always less than Urban and greater than Rural, and Rural cities always have the smallest monthly totals. It can also be seen that the monthly total fares by city type exist in distinct bands, meaning that there is no overlap between the minimums and maximums of monthly totals by city type. Rural cities appear to have relatively consistent total monthly fares, while Suburban cities appear to have maximums and minimums over the course of around 4 weeks. Urban cities appear to dip in the colder winter months, and slowly increase as it approaches summer.

<img src="">

### Average Fare per Ride

Urban-type cities have $24.53 average fare per ride, which is the lowest average fare per ride out of all city types. For Suburban cities, the average fare per ride is $30.97, which is about 1.26 times the average fare for Urban cities. Rural cities have an average fare of $34.62 per ride, which is about 1.41 times the average fare per ride in Urban cities and about 1.12 times the average fare per ride for Suburban cities. Therefore, Rural-type cities have the greatest average fare per ride out of all city types.

### Average Fare per Driver

Urban cities have an average fare per driver of $16.57, which is the lowest average fare per driver. Suburban-type cities have an average fare of $39.50 per driver, which is about 2.38 times the Urban average. Rural cities have $55.49 average fare per driver, which is about 1.40 times the Suburban average and 3.35 times the Urban average. Therefore, Rural-type cities have the highest average fare per driver.

## Summary

Based on the above results, some business recommendations can be made to address disparites amongst city types:

- To raise total fares for Rural cities, riders will need to be further incentivised to use Pyber. Therefore, there will likely need to be both a decrease in ride fares and an increase in the number of drivers. A more affordable and reliable transportation service will draw in more users and increase profits.

- Suburban cities require a similar change as Rural cities, though to a lesser degree. They will likely require only either a slight decrease in ride fares or a small increase in drivers. 

- Urban cities would most likely benefit from increased incentives to using Pyber, as there are currently more drivers than riders. Given the already low average far per ride, these incentives will likely have to come in some form other than a decrease in ride shares.
