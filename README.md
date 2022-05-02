## Predicting whether an Employee will stay or leave
#### Team was tasked with preparing a ML Model which predicts probability whether an employee stays or leaves the company.
**HR department at a software company is looking to try a new initiative to retain employees by using data to predict whether an employee is likely to leave as the current practice of taking exit interviews do provide insights, but its too late to work on it. Also these insights can't be aggregated and interlaced across all employees who have left. Trying the new initiative once these employees are identified, HR can be more proactive in reaching out to them before it's too late.**

Data Description


**The Business Intelligence Analysts of the Company provided you three datasets that contain information about past employees and their status (still employed or already left).**

- **department_data**

    This dataset contains information about each department. The schema of the dataset is as follows:

    dept_id : Unique Department Code
    dept_name : Name of the Department
    dept_head : Name of the Head of the Department


- **employee_details_data**

    This dataset consists of Employee ID, their Age, Gender and Marital Status. The schema of this dataset is as follows:

     employee_id : Unique ID Number for each employee
     age : Age of the employee
     gender : Gender of the employee
     marital_status : Marital Status of the employee


- **employee_data**

    This dataset consists of each employee’s Administrative Information, Workload Information, Mutual Evaluation Information and Status.


- **Target variable

    status – Current employment status (Employed / Left)

- **Administrative information**

    department – Department to which the employees belong(ed) to
    salary – Salary level with respect to rest of their department
    tenure – Number of years at the company
    recently_promoted – Was the employee promoted in the last 3 years?
    employee_id – Unique ID Number for each employee


- **Workload information**

    n_projects – Number of projects employee has worked on
    avg_monthly_hrs – Average number of hours worked per month

- **Mutual evaluation information**

    satisfaction – Score for employee’s satisfaction with the company (higher is better)
    last_evaluation – Score for most recent evaluation of employee (higher is better)
    filed_complaint – Has the employee filed a formal complaint in the last 3 years?

You can check the notebook by [clicking here.](https://github.com/darsh2303/Predicting-whether-and-Employee-will-stay-or-leave-/blob/main/1002_GCD_CAPSTONE_PROJECT.ipynb)

