# Employee Management System

The Employee Management System is a Python-based program designed to manage employees within an organization. The system allows the user to add, remove, view, and manage employee details including their performance scores and salary calculation.

## Table of Contents
1. [Features](#Features)
2. [Getting Started](#Getting-Started)
3. [Usage](#Usage)
4. [Contribution](#Contribution)
5. [License](#License)

## Features
- **Adding Employee**: You can add single employees providing their details.
- **Bulk Adding Employees**: You can also add multiple employees at once.
- **Removing Employee**: You can remove any employee from the system.
- **Adding Performance Score**: You can add performance scores for each employee.
- **Calculating Salary**: The system calculates the salary based on an employee's base salary and performance scores.
- **Viewing Employee Details**: You can view the details of any specific employee or all employees if you have the correct password.

## Getting Started
To use the Employee Management System, you need Python installed on your machine. The program also uses the 'random' module to generate random IDs for employees, which comes built-in with Python.

### Prerequisites
- Python (3.x recommended)

### Installation
1. Clone the repository: `git clone https://github.com/username/reponame.git` (replace with the actual URL of your repository)
2. Navigate to the repository directory in your local system
3. Run `python main.py` to start the system

## Usage
When you run the system, a menu will be displayed asking you what action you would like to perform. You can choose to add employees, remove employees, add performance scores, calculate salary, view employee details, or exit the program.

For bulk employee addition, you can input employee details in the format `name,id,base_salary`. To exit this mode, simply type 'exit'.

To remove an employee, add performance score, calculate salary, or view details of a particular employee, you must input the employee's ID.

To view all employee details, you need to provide the password. The default password is 'password123'. 

## Contribution
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.
