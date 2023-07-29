# SQL Challenge: Employee Tracker 🏢📊
Developers often have to create user-friendly interfaces that allow non-developers to easily interact with information stored in databases. These interfaces are called Content Management Systems (CMS). Our mission this week is to build a command-line application from scratch to manage a company's employee database, leveraging Node.js, Inquirer, and MySQL.


## 🚀 Getting Started
To connect to your MySQL database and perform queries, use the MySQL2 package. Interact with the user via the command line using the Inquirer package.

Please install Inquirer using the following command: `npm i inquirer@8.2.4`.

You will be committing a file containing your database credentials. Be sure to use a MySQL password that is not shared with any other personal accounts, as it will be visible on GitHub. Future lessons will teach how to secure this password, or you can start exploring npm packages that might help.

Asynchronous queries can be beneficial. MySQL2 provides a `.promise()` function on Connections to convert an existing non-Promise connection to use Promises. To learn more and make your queries asynchronous, refer to the [npm documentation on MySQL2](https://www.npmjs.com/package/mysql2).

Initial Steps
✅ Have MySQL installed.
✅ Have Node.js installed.
✅ Install npm inside the project and all the required dependencies (mysql2, inquirer, dotenv).
✅ Run source develop/db/schema.sql; in the MySQL shell.
Once you have completed all of these steps, you can type the following command inside the terminal:
npm start


## 📝 User Story
As a business owner, I want to be able to view and manage the departments, roles, and employees in my company, so that I can organize and plan my business more efficiently.

## ✅ Acceptance Criteria
* WHEN I start the application
* THEN I am presented with options to: view all departments, view all roles, view all employees, add a department, add a role, add an employee, and update an employee role
* WHEN I choose to view all departments
* THEN I am presented with a formatted table showing department names and department ids
* WHEN I choose to view all roles
* THEN I am presented with the job title, role id, the department that role belongs to, and the salary for that role
* WHEN I choose to view all employees
* THEN I am presented with a formatted table showing employee data, including employee ids, first names, last names, job titles, departments, salaries, and managers that the employees report to
* WHEN I choose to add a department
* THEN I am prompted to enter the name of the department and that department is added to the database
* WHEN I choose to add a role
* THEN I am prompted to enter the name, salary, and department for the role and that role is added to the database
* WHEN I choose to add an employee
* THEN I am prompted to enter the employee’s first name, last name, role, and manager, and that employee is added to the database
* WHEN I choose to update an employee role
* THEN I am prompted to select an employee to update and their new role and this information is updated in the database

## 📊 Database Schema
The schema should contain the following three tables:
* `department`
* `role`
* `employee`

Check the project instructions for specific details about the structure of these tables.

## 📹 Demo
https://drive.google.com/file/d/173uM-FxcOTLDj6BXAk3CBxItPbZhEH0R/view

## 📜 License
This project is licensed under the terms of the MIT license.

## 🙋‍♀️ Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## 👩‍💻 Author
Your Name
