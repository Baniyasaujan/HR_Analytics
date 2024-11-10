# Employee Attrition Dashboard

## Description

The **Employee Attrition Dashboard** is a Power BI project focused on understanding the factors driving employee turnover in a company. This dashboard provides an in-depth view of various employee demographics and job attributes, including age, education, job role, salary, and tenure, to help HR professionals analyze and interpret trends in attrition. By identifying high-risk groups for turnover, this tool supports strategic, data-driven decision-making aimed at improving employee retention and satisfaction.

The dashboard is built to be interactive, allowing users to drill down into specific segments and filter results based on different criteria. This flexibility enables HR teams to gain actionable insights into the causes of attrition and prioritize initiatives that address those issues effectively.

## Key Metrics
1. **Count of Employees**: The total number of employees analyzed is 925.
2. **Attrition**: 132 employees left the organization, which is 14.3% of the workforce.
3. **Average Age**: The average age of employees is 36.84 years.
4. **Average Income**: The average income across employees is $6,100.
5. **Average Years in Company**: Employees have been with the company for an average of 6.4 years.

## Visualizations and Insights
This dashboard features various visualizations designed to make attrition patterns clear and actionable:

1. **Attrition by Education**: This donut chart categorizes attrition by education fields. The breakdown reveals that Life Sciences graduates make up the largest group (44%) experiencing turnover, followed by those in Medical (36%) and Technical degrees (15%).

2. **Attrition by Age**: This bar chart highlights the age groups with the highest attrition rates. Employees aged 26-35 are the most likely to leave, which may indicate mid-career transitions or opportunities outside the organization.

3. **Attrition by Salary Slab**: This bar chart categorizes employees by salary brackets, showing the highest turnover in the "Up to 5K" bracket. This suggests that lower compensation may be a factor in employee decisions to leave.

4. **Attrition by Years at Company**: This line chart displays attrition by tenure, revealing that employees with 0-1 years at the company have the highest attrition rates. This insight can prompt a closer look at onboarding and early career support.

5. **Attrition by Job Role**: This bar chart breaks down turnover by job roles. Laboratory Technicians (61) and Research Scientists (47) show the highest attrition numbers, which could help HR prioritize interventions for these roles.

6. **Attrition by Gender**: A simple bar chart that compares attrition rates by gender, showing that 88 males and 38 females left the organization. This may indicate different retention challenges for each gender.

7. **Job Role Distribution Table**: This table provides a cross-reference of attrition across job roles and departments, allowing HR professionals to pinpoint departments with higher attrition rates and prioritize targeted retention efforts.

## Data Source

The data used to create this dashboard is sourced from a CSV file (`HR_Analytics.csv`) containing anonymized information for 1480 employees, covering the following key columns:

- **EmpID**: Unique identifier for each employee.
- **Age, AgeGroup**: Age of the employee, both as a number and a categorized group.
- **Attrition**: Indicates whether the employee left the company.
- **JobRole, Department**: Details of the employee’s role and department.
- **MonthlyIncome, SalarySlab**: Salary details for each employee, with salary slabs categorized for easier analysis.
- **YearsAtCompany, YearsSinceLastPromotion**: Information on tenure and promotions.

The Power BI file (`HR_Analytics.pbix`) contains the pre-configured visualizations and calculations based on this data.

