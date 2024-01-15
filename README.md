
The company's database is designed to manage information about employees and departments. The database consists of two main tables: `departments` and `employees`.

1. **Departments Table:**
   - **Columns:**
     - `department_id` (INT): A unique identifier for each department.
     - `department_name` (VARCHAR): The name of the department.
   - **Description:** This table stores details about different departments within the company. The `department_id` serves as the primary key, ensuring each department has a unique identifier. The `department_name` column holds the name of each department.

2. **Employees Table:**
   - **Columns:**
     - `employee_id` (INT): A unique identifier for each employee.
     - `first_name` (VARCHAR): The first name of the employee.
     - `last_name` (VARCHAR): The last name of the employee.
     - `email` (VARCHAR): The unique email address of the employee.
     - `department_id` (INT): A foreign key linking to the `department_id` in the `departments` table.
   - **Description:** This table stores information about employees. The `employee_id` is a unique identifier for each employee. The `first_name` and `last_name` columns store the employee's name, and the `email` column ensures each employee has a unique email address. The `department_id` is a foreign key linking each employee to their respective department.

The relationship between the two tables is established through the `department_id` foreign key in the `employees` table, connecting each employee to a specific department in the `departments` table. This database structure facilitates the organization and retrieval of information about both employees and their corresponding departments.
