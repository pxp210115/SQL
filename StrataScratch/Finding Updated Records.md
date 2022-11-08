[Link to Question](https://platform.stratascratch.com/coding/10299-finding-updated-records?code_type=1)

## Question 35:

![image](https://user-images.githubusercontent.com/100412162/200645111-9e83b7c5-2021-41e9-be76-aa3aca3c9452.png)

My Solution:-

~~~~sql
select id,first_name, last_name, department_id, max(salary)
from ms_employee_salary
group by id,first_name, last_name, department_id
order by id;
~~~~
