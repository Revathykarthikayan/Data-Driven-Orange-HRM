BASE URL: https://opensource-demo.orangehrmlive.com/web/index.php/auth/login 

Introduction:
  This project automates testing of the OrangeHRM web application. It focuses on five test cases:

Login Functionality:

   1. Positive Test Case: Validates successful login with correct credentials (using data from a CSV file).
   2. Negative Test Case: Verifies error message display for invalid credentials (using data from a CSV file).
    
Employee Management:

  1.Enrolling a new employee.
  2.Editing an existing employee's details.
  3.Deleting an existing employee.
  
Test Objective:

    The Login functionality utilizes a Data-Driven Test Framework
    for flexible execution with various input data sets.
    
    Employee Management employs the Page Object Model design pattern
    for better code organization and maintainability.

The framework captures screenshots of failed test cases, such as the negative login test, and includes them in the generated HTML report for your reference.

Key Features:

Data-Driven Testing: Enables efficient execution with different data sets.

Page Object Model: Promotes modular and maintainable code.

Screenshot Capture: Documents test failures for analysis and debugging.

Detailed HTML Reports: Provides comprehensive test results and insights.

