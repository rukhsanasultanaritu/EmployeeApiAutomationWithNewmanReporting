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
<img width="1731" height="1610" alt="image" src="https://github.com/user-attachments/assets/e8390093-8375-4b42-a750-6ee39ab9ef6e" />

<img width="1731" height="1032" alt="image" src="https://github.com/user-attachments/assets/6f063f90-eea0-4293-823a-9f46aa9de170" />


### Project Links

[GitHub Repository](https://github.com/rukhsanasultanaritu/EmployeeApiAutomationWithNewmanReporting.git)

## Author
Rukhsana Sultana Ritu | CSE Graduate | Aspiring Software QA Engineer
