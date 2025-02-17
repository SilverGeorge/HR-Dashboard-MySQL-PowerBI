# HR-Dashboard-MySQL-PowerBI

<img width="663" alt="Screenshot 2025-02-17 194428" src="https://github.com/user-attachments/assets/a849c397-b175-4e05-868f-d35939b171b2" />

## Analysis Questions
1. What is the gender breakdown of employees in the company?
2. What is the race/ethnicity breakdown of employees in the company?
3. What is the age distribution of employees in the company?
4. How many employees work at headquarters versus remote locations?
5. What is the average length of employment for employees who have been terminated?
6. How does the gender distribution vary across departments and job titles?
7. What is the distribution of job titles across the departments and job titles?
8. Which department has the highest turnover rate?
9. What is the distribution of employees across locations by state?
10. How has the company's employee count changed over time based on hire and termination dates?
11. What is the tenure distribution for each department?

## Summary of Findings
- There are more male employees.
- The White race is the most dominant, while Native Hawaiian and American Indian are the least dominant.
- The youngest employee is 20 years old, and the oldest is 57 years old.
- Employees were grouped into five age categories: **18-24, 25-34, 35-44, 45-54, and 55-64**.
  - The largest group of employees falls within **25-34**, followed by **35-44**.
  - The smallest group is **55-64**.
- A large number of employees work at headquarters rather than remotely.
- The average length of employment for terminated employees is around **7 years**.
- The gender distribution across departments is fairly balanced, but overall, **there are more males than females**.
- **Marketing** has the highest turnover rate, followed by **Training**.
  - The **Research & Development, Support, and Legal** departments have the lowest turnover rates.
- A significant number of employees are from **Ohio**.
- The net change in employees has **increased over the years**.
- The average tenure across departments is **8 years**.
  - **Legal and Auditing** departments have the highest tenure.
  - **Services, Sales, and Marketing** have the lowest tenure.
 
## Limitations
- Some records had **negative ages** and were excluded during querying (**967 records**). Only employees aged **18 years and above** were considered.
- Some **termination dates were far into the future** and were not included in the analysis (**1,599 records**). Only termination dates **less than or equal to the current date** were used.
