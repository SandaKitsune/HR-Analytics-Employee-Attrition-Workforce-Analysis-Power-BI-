# HR-Analytics-Employee-Attrition-Workforce-Analysis-Power-BI-
An interactive Power BI dashboard that explores employee demographics, workforce distribution, compensation, career progression, satisfaction, and attrition patterns to identify where turnover is concentrated and what may be driving it.


**Business Questions**

Which departments and job roles experience the highest attrition?

How does employee turnover relate to overtime, tenure, and income?

How does monthly income vary across job roles, education levels, and education fields?

How satisfied are employees (job, environment, involvement, work-life balance), and how do employees who left differ from those who stayed?

Where are the biggest opportunities to improve retention and engagement?



**Data**

Source: IBM HR Analytics Employee Attrition & Performance dataset ([Kaggle](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset/data))
Fields: gender, age, education and education field, department, job role, monthly income, years at company, years since last promotion, years in current role, business travel, overtime, attrition, job satisfaction, environment satisfaction, job involvement, work-life balance, relationship satisfaction



**Tools**

Power BI Desktop · Power Query · DAX



**Dashboard Structure**
|Page|Content|
|------|---------|
|**Overview**|Purpose, dataset description, and analysis objectives|
|**Employee overview**|	KPI cards (headcount, average age, average tenure, average monthly income), employees by department and job role, education and education field, gender, business travel, and attrition split, with gender / department / education field slicers|
|**Employee Performance and Compensation**|	Monthly income by education and education field, average monthly income by job role, income by years at company and department, employees by years since last promotion, and an employee-level detail table, with attrition / job role / department / education field slicers|
|**Attrition analysis**|	Attrition % by department and job role, employees by overtime, years at company vs. annual income, tenure and promotion trends, with attrition / education / job role / department slicers|
|**Employee Satisfaction**|	Employees by job satisfaction, environment satisfaction, job involvement, and work-life balance, plus satisfaction score cards, with attrition / education / department / job role slicers|
|**Analysis 1 / Analysis 2**|	Written findings on workforce metrics, compensation, attrition, and satisfaction|


**Key Findings**

Workforce profile

1,470 employees, average age 37, average tenure 7 years, average monthly income about $6.5K.
60% male, 40% female; about 71% travel rarely for business.
Most employees hold higher education or postgraduate degrees; Research & Development is the largest department and Sales Executive the most common job role.


Compensation and career progression

Promotions are concentrated within the first three years of employment.
Managers and Research Directors are the highest-paid roles (Managers average about $20K per month).
Employees with master's and doctoral degrees have the highest average income by education level.
Income patterns by tenure differ by department: Human Resources rises after about 11 years then declines, R&D rises steadily until about 14 years, and Sales fluctuates strongly between 14 and 18 years.


Attrition

Overall attrition is about 16%: 237 employees left.
Employees who left averaged 33 years of age, 5 years of tenure, and about $4.8K monthly income (about $57K annually).
Employees who stayed averaged 7 years of tenure and about $6.83K monthly income (about $82K annually).
Around half of those who left worked overtime, while 76% of those who stayed did not, pointing to a possible link between overtime and retention.
R&D accounts for 56% of departures; Laboratory Technician and Sales Executive roles account for 26% and 24%.


Satisfaction and work-life balance

Most satisfaction indicators are above average (over 2.7), with small differences between leavers and stayers.
Environment satisfaction stands out: employees who stayed report higher levels.
Leavers in Human Resources show some of the lowest satisfaction: work-life balance of 2.9 and relationship satisfaction above 3, but environment and job satisfaction below 2.5.


Recommendations

Review overtime practices, especially in the departments and roles with the highest attrition.
Prioritize retention efforts for R&D, Laboratory Technician, and Sales Executive roles.
Look at early-tenure compensation and promotion paths, since leavers earn less and have shorter tenure.
Improve the workplace environment and job experience, particularly in Human Resources.

<img width="590" height="330" alt="employee" src="https://github.com/user-attachments/assets/61515a8e-0107-4094-86d0-615c5459526a" />
<img width="584" height="332" alt="performance" src="https://github.com/user-attachments/assets/0d83a402-5e5a-4562-84bf-8e113680e32d" />
<img width="587" height="326" alt="attrition" src="https://github.com/user-attachments/assets/dc1eea7b-69e6-4415-91e7-36190e5ed49e" />
<img width="589" height="326" alt="Satisfaction" src="https://github.com/user-attachments/assets/cd0c5e6f-61b0-45c1-951e-280529e1f180" />


**How to Open**


Download report/Budget vs Actual Spending.pbix and open it with Power BI Desktop (Windows).
