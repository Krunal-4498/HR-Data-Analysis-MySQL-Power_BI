# HR-Data-Analysis-MySQL-Power_BI

The HR Data Analysis: Employee Distribution project integrates MySQL for data storage, retrieval, cleaning and analyzing with Power BI for dynamic and insightful visualizations. This project explores multifaceted aspects of employee distribution within an organization from 2000 to 2020. It provides actionable insights to HR professionals and decision-makers, covering changes in employee count, gender distribution, remote and HQ work patterns, state-wise distribution, racial demographics, age group-wise gender distribution, department-wise gender distribution, department-wise termination rates, and age group-wise employee counts.


![HR_data_analysis](https://github.com/Krunal-4498/HR-Data-Analysis-MySQL-Power_BI/assets/134350505/b93aa8ab-20b4-4a89-8f79-535fa05e7f05)


![HR_data_analysis (2)](https://github.com/Krunal-4498/HR-Data-Analysis-MySQL-Power_BI/assets/134350505/1adb83bf-6735-4c45-86cc-3ed6a5d38ef5)



## Data Sources

The HR data for this project originates from an initial CSV file, which was subsequently imported into a MySQL database using MySQL Workbench. 
The MySQL database served as the primary data repository for various analyses. Different CSV files were then extracted from the MySQL database using specific queries, each catering to a distinct aspect of the analysis. These extracted CSV files were utilized in Power BI for creating a comprehensive and dynamic visualization report.

### Initial CSV File

- **File Name:** `hr_data.csv`
- **Format:** Comma-separated

## Tools Used

1. **MySQL:**
   - Utilized for storing, managing, and querying the HR data.

2. **Power BI:**
   - Employed for creating dynamic and insightful visualizations based on the analyses performed on the MySQL data.



## Questions Answered

1. What is the gender breakdown of employees in the company?
2. What is the race/ethnicity breakdown of employees in the company?
3. What is the age distribution of employees in the company?
4. How many employees work at headquarters versus remote locations?
5. What is the average length of employment for employees who have been terminated?
6. How does the gender distribution vary across departments and job titles?
7. What is the distribution of job titles across the company?
8. Which department has the highest turnover rate?
9. What is the distribution of employees across locations by state?
10. How has the company's employee count changed over time based on hire and term dates?
11. What is the tenure distribution for each department?

## Summary of Findings
 - There are more male employees
 - White race is the most dominant while Native Hawaiian and American Indian are the least dominant.
 - The youngest employee is 20 years old and the oldest is 57 years old
 - 5 age groups were created (18-24, 25-30, 31-36, 37-42, 43-50, 51-60+). A large number of employees were between 43-50 followed by 31-36 while the smallest group was 18-24.
 - A large number of employees work at the headquarters versus remotely.
 - The average length of employment for terminated employees is around 8 years.
 - The gender distribution across departments is fairly balanced but there are generally more male than female employees.
 - The Auditing department has the highest turnover rate followed by Legal. The least turn over rate are in the Marketing, Bussiness Development and Support.
 - A large number of employees come from the state of Ohio.
 - The net change in employees has increased over the years.
- The average tenure for each department is about 8 years with Legal and Auditing having the highest and Services, Sales and Marketing having the lowest.
