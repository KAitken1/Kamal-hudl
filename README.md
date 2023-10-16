# Kamal-hudl
Selenium Java TestNG Eclispse IDE

Hudl Test Automation Project
Introduction
This project is part of the Hudl interview process. The goal is to assess your automation skills and your understanding of best practices for test automation.

Project Overview
In this project, you will create an automation framework and write tests for a specific functionality of the Hudl website. The task is to implement login functionality from scratch. You will build an automation framework and write test cases for this feature.

Project Requirements
You will create an automation framework for the login functionality.
You can choose any programming language and test framework you are comfortable with.
The tests should not only run on your machine. Provide clear instructions on how to set up and run your tests.
Your tests should include documentation on best practices of the chosen tooling and framework.
Create a well-written README document.
If you encounter any issues or limitations during the test, document them along with possible workarounds.
Your project should be uploaded to a public GitHub repository.
Getting Started
Clone this GitHub repository to your local machine.
bash
Copy code
git clone <repository-url>
Set up your automation environment:

Install the required tools, such as the chosen programming language, build tools, and the testing framework.
Configure any dependencies as needed.
Open your preferred integrated development environment (IDE) and import the project.

Review the code structure:

The project is organized into packages, including base, pageEvents, pageObjects, testcases, and utilities.
The base package contains a BaseTest class, which you can use as the base for your test classes.
The pageEvents package contains classes that interact with the page elements.
The pageObjects package contains interfaces that define page element locators.
The testcases package contains test classes for different scenarios.
The utilities package includes classes for element fetching and reading data from Excel files.
Test Scenarios
The project includes several test scenarios categorized into three test case classes: EdgeCase, NegativeLoginCase, and PositiveLoginCase.

EdgeCase
Test scenarios for handling various empty or missing input fields during login.
NegativeLoginCase
Test scenarios for invalid usernames and passwords.
PositiveLoginCase
Test scenarios for successful logins with valid credentials, including case-insensitive logins and leading spaces in usernames.
Running the Tests
To run the tests, use your preferred testing framework or IDE that supports TestNG. Ensure that you have set up the required environment correctly.

To run all the tests, execute the test classes: EdgeCase, NegativeLoginCase, and PositiveLoginCase.

Reporting
Your testing framework should provide test reports and results. Review these reports to verify the test results.

Known Issues and Limitations
Document any known issues or limitations you encountered during the project, along with potential workarounds.

Conclusion
This project aims to assess your test automation skills, your choice of tools, and your adherence to best practices. We look forward to reviewing your work and discussing the results.

Please make sure to submit your completed project by the specified deadline. If you have any questions or encounter any issues, do not hesitate to reach out for assistance.

Thank you for your efforts, and we are excited to see what you come up with!

Best regards,
Kamal

Please note that you should replace <repository-url> with the actual URL of your GitHub repository where you upload the project.
