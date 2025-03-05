# Data Engineer Salary Prediction in 2024
***About Dataset***

This dataset provides insights into data engineer salaries and employment attributes for the year 2024. It includes information such as salary, job title, experience level, employment type, employee residence, remote work ratio, company location, and company size.

The dataset allows for analysis of salary trends, employment patterns, and geographic variations in data engineering roles. It can be used by researchers, analysts, and organizations to understand the evolving landscape of data engineering employment and compensation.

***Feature Description***

|Column|Meaning|
|:-----:|:-----:|
|work_year|The year in which the data was collected (2024)|
|experience_level|The experience level of the employee, SE (Senior Engineer), MI (Mid-Level Engineer), EL (Entry-Level Engineer)|
|employment_type|The type of employment, full-time (FT), part-time (PT), contract (C), freelance (F)|
|job_title|The title or role of the employee within the company (e.g., AI Engineer)|
|salary|The salary of the employee in the local currency (e.g., 202,730 USD)|
|salary_currency|The currency in which the salary is denominated (e.g., USD)|
|salary_in_usd|The salary converted to US dollars for standardization purposes|
|employee_residence|The country of residence of the employee|
|remote_ratio|The ratio indicating the extent of remote work allowed in the position (0 for no remote work, 1 for fully remote)|
|company_location|The location of the company where the employee is employed|
|company_size|The size of the company, small (S), medium (M), large (L)|
Complete the following requirements:

1. ***Explore the data*** and ***clean the data***. For example, remove abnormal instanaces and replace missing values.

2. ***Study the correlation*** between 'salary' with other features.
  
4. ***Split the dataset*** (Training set : Test set = 8 : 2)

5. ***Train a logistic regression model*** to predict 'salary' based on the selected features (from the second step). ***Calculate the accuracy*** of the model.

7. ***Train a KNN model*** to predict 'salary' based on the selected features.
