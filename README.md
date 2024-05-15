# HRM Payroll System

The HRM Payroll System is a comprehensive software solution designed to streamline and automate human resource management and payroll processes within organizations. It provides efficient management of employee data, attendance, leaves, payroll processing, and reporting functionalities.

## Software Requirements Specification (SRS)

### 1. Introduction

The HRM Payroll System is a comprehensive software solution designed to streamline and automate the human resource management and payroll processes within organizations. It aims to provide efficient management of employee data, attendance, leaves, payroll processing, and reporting functionalities. The system is built using Laravel framework for backend development, MySQL for database management, and frontend technologies including JavaScript, jQuery, AJAX, and Bootstrap5.

### 2. Purpose

The purpose of the HRM Payroll System is to:

- Automate and streamline HR processes such as employee data management, attendance tracking, leave management, and payroll processing.
- Provide a centralized platform for HR personnel to efficiently manage employee-related tasks and activities.
- Ensure accuracy and compliance in payroll processing and reporting.
- Enhance transparency and accessibility of employee-related information for both HR personnel and employees.

### 3. Scope

The HRM Payroll System includes the following main features:

- Employee Management: Allows HR personnel to add, edit, and delete employee records, including personal information, employment details, and contact information.
- Attendance Tracking: Provides functionality to record and track employee attendance, including clock-in and clock-out times, overtime hours, and absences.
- Leave Management: Enables employees to request leaves, and allows HR personnel to review, approve, or reject leave requests. It also tracks available leave balances for each employee.
- Payroll Processing: Automates the calculation of employee salaries, deductions, and taxes based on predefined rules and parameters. Generates pay slips and allows HR personnel to review and approve payroll before final processing.
- Reporting: Generates various reports related to employee data, attendance, leaves, payroll, and other HR-related metrics.

### 4. Functional Requirements

#### 4.1 Employee Management
- Add Employee: HR personnel can add new employee records by providing personal details, employment information, and contact details.
- Edit Employee: Allows HR personnel to modify existing employee records, including personal and employment information.
- Delete Employee: Provides the functionality to delete employee records from the system.
- View Employee Details: HR personnel can view detailed information about each employee, including personal details, employment history, and contact information.

#### 4.2 Attendance Tracking
- Record Attendance: Allows employees to clock in and clock out using the system interface. Tracks working hours, overtime hours, and breaks.
- Manage Attendance Records: HR personnel can view and manage attendance records for each employee, including attendance summary and detailed logs.

#### 4.3 Leave Management
- Request Leave: Employees can submit leave requests through the system, specifying the type of leave, duration, and reason.
- Approve/Reject Leave Requests: HR personnel can review leave requests, approve or reject them based on company policies and leave balances.
- Track Leave Balances: The system automatically tracks available leave balances for each employee based on approved leave requests.

#### 4.4 Payroll Processing
- Configure Payroll Settings: HR personnel can configure payroll settings, including salary structures, allowances, deductions, and tax rates.
- Calculate Payroll: Automatically calculates employee salaries based on predefined rules, including attendance, leaves, overtime, allowances, and deductions.
- Review and Approve Payroll: HR personnel can review payroll calculations and make any necessary adjustments before final approval.
- Generate Pay Slips: Automatically generates pay slips for each employee, detailing salary components, deductions, and net pay.

#### 4.5 Reporting
- Generate Reports: Provides predefined and customizable reports related to employee data, attendance, leaves, payroll, and other HR metrics.
- Export Reports: Allows HR personnel to export reports in various formats such as PDF, Excel, or CSV for further analysis or sharing.

### 5. Non-Functional Requirements

#### 5.1 Performance
- The system should be able to handle a large volume of employee data and transactions efficiently without significant performance degradation.
- Response time for user interactions should be minimal, ensuring a seamless user experience.

#### 5.2 Security
- User authentication and authorization mechanisms should be implemented to ensure that only authorized personnel have access to sensitive HR data.
- Data encryption should be used to protect employee data stored in the system.

#### 5.3 Scalability
- The system should be designed to scale easily to accommodate the growth of the organization and increasing number of employees.

#### 5.4 Usability
- The user interface should be intuitive and user-friendly, requiring minimal training for HR personnel to use the system effectively.
- The system should support multiple languages and localization to cater to diverse user groups.

### 6. System Architecture

The HRM Payroll System follows a three-tier architecture:

- Presentation Layer: Implemented using HTML, CSS, JavaScript, jQuery, and Bootstrap5 for the frontend user interface.
- Application Layer: Developed using the Laravel framework for backend business logic, including routing, controllers, models, and services.
- Data Layer: Utilizes MySQL database for storing and managing employee data, attendance records, leave requests, payroll information, and other relevant data.

### 7. Glossary

- HRM: Human Resource Management
- SRS: Software Requirements Specification
- CRUD: Create, Read, Update, Delete
- AJAX: Asynchronous JavaScript and XML
