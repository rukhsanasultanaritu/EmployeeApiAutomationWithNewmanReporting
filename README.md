## API Automation Project With Newman Reporting

## About this project
This is employee api automation project.This project is faclated to create employee,update employee,get employee list and search employee with different parameter.
Here we have create automation and generate a newman report.

## Features
- Employee Creation API Testing
- Employee Update API Testing
- Get All Employees API Testing
- Employee Search with Different Parameters
- API Response Validation
- Automated Test Execution with Newman
- HTML Test Report Generation

## Pre-requisites
Make sure the following software is installed on your system:
- Node.js
- Postman
- Visual Studio Code

## Tools and Technologies
- Postman 
- Visual Studio Code 
- Node.js 
- Git and GitHub
## API Documentation 
[Employee API Documentation](https://documenter.getpostman.com/view/49956893/2sBYHNX3hV)

## How to run this project
### Clone Project

```bash
git clone https://github.com/rukhsanasultanaritu/EmployeeApiAutomationWithNewmanReporting.git
```
## Run the Commands
### Step 1: Initialize npm
```bash
npm init -y
```
### Step 2: Install Newman
```bash
npm i newman
```
### Step 3: Run the Postman Collection
```bash
npx newman run collection.json -e "environment.json"
```
### Step 4: Install HTML Extra Reporter
```bash
npm i newman-reporter-htmlextra
```
### Step 5: Generate the HTML Report
```bash
node .\report.js
```
## Newman HTML Report
The following screenshot shows the Newman HTML test execution report.
<img width="955" height="448" alt="image" src="https://github.com/user-attachments/assets/367d473b-1e1c-4a06-a043-decbb4e0a77d" />
<img width="952" height="448" alt="image" src="https://github.com/user-attachments/assets/7390b19a-7d85-4ae5-9c5c-f4fc3eda76a1" />

### Project Links

GitHub Repository:https://github.com/rukhsanasultanaritu/EmployeeApiAutomationWithNewmanReporting.git

## Author
Rukhsana Sultana Ritu | CSE Graduate | Aspiring Software QA Engineer
