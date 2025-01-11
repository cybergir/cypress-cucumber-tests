# Cypress-Cucumber Test Project

## Overview
This project is a test automation suite built using Cypress and Cucumber for a simple login page. 
It includes feature tests for key functionalities such as user login, product search, and checkout processes. 
The goal of this project is to demonstrate the integration of Behavior-Driven Development (BDD) principles with automated testing.

## Features
- User Login: Tests for successful and unsuccessful login scenarios.
- Product Search: Tests the search functionality to ensure relevant results are displayed.
- Checkout Process: Validates the checkout process, including order confirmation.

## Prerequisites
Before you begin, ensure you have the following installed on your machine:
- [Node.js](https://nodejs.org/) (v12 or higher)
- [npm](https://www.npmjs.com/) (comes with Node.js)

## Getting Started

### 1. Clone the Repository
Clone this repository to your local machine using: git clone https://github.com/cybergir/cypress-cucumber-tests.git


### 2. Navigate to the Project Directory


### 3. Install Dependencies
Install the required packages using npm:



### 4. Configure Cypress with Cucumber
Make sure you have set up the Cypress-Cucumber preprocessor as described in the project setup.

### 5. Running Tests
To open the Cypress Test Runner, use:

Select the feature files you want to run from the Test Runner interface.

### 6. Running Tests in Headless Mode (Optional)
You can also run tests in headless mode using:



## Project Structure
cypress/
├── integration/
│ ├── features/
│ │ ├── login.feature
│ │ ├── search.feature
│ │ └── checkout.feature
│ └── step_definitions/
│ ├── login.js
│ ├── search.js
│ └── checkout.js
└── fixtures/


## Contributing
Contributions are welcome! 
If you have suggestions for improvements or new features, please create an issue or submit a pull request.

## Acknowledgments
- [Cypress Documentation](https://docs.cypress.io/)
- [Cucumber Documentation](https://cucumber.io/docs/guides/overview/)
- [BrowserStack Guide on Cypress-Cucumber](https://www.browserstack.com/guide/how-to-run-cypress-cucumber-test)
