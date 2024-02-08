*2/8/2024*

# Brief Report

## Basic Data Exploration and Data Cleaning:
* The dataset of salaries contains 148654 rows and 13 columns.
* Upon counting missing values, it was discovered that the 'Notes' and 'Status' columns are entirely null and can be safely deleted.
* The column “Agency” has a unique value, so it can also be deleted.
* Many other columns have null values, so I proceeded to the deletion of the rows containing null values
* Since the “Benefits” column have 36160 null values, it's not correct to drop all of these columns, what I did instead is filling them with the median of benefits
* The average salary of employees is $74768.32.

## Visualization:
* I used the histogram to visualize salary distribution
![Salary distributions](https://github.com/Malak-Kanaan/ShAI/assets/58569038/1542ba48-1f05-4169-ac5d-7b44aff91c8f)

* I used a pie chart to represent the proportion of employees in different departments.
![Pie chart](https://github.com/Malak-Kanaan/ShAI/assets/58569038/0b7033e8-ffab-4aee-8d48-1d2d4d3d48a6)


## Grouped Analysis:
* I calculated the average salary by job title and by year.
* I observed huge variations in compensation across different job titles and over time.

## Simple Correlation Analysis:
* The correlation coefficient between BasePay and TotalPay was calculated to be 0.954, indicating a strong positive linear relationship between the two variables.
* This suggests that changes in base pay are closely impacted by changes in total pay, emphasizing the significance of base salary in determining overall compensation levels.

## Conclusion:
* The analysis provides valuable insights into the organization's compensation structure, highlighting disparities in pay across job titles and fluctuations over time.
* Further analysis and action may be required to address missing data and optimize compensation strategies for organizational success.
