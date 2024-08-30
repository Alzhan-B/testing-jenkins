# Testing Jenkins

This project is about creating automation test scripts in Cypress and JavaScript for testing Jenkins website. 

## How to start working in our project?

1. Clone repository to your machine.

2. Navigate to project root folder.

3. Run command `npm install` or `npm ci` to install dependencies.

4. Create env file with creaentials:
    1) Copy and paste the file `cypress.env.json.example` to project root folder. 
    2) Сhange the file name to `cypress.env.json`. 

5. Choose a script to execute your tests:

   * `npm run cy-open` - opens Cypress to manually choose which test to run
   * `npm run cy-run` - runs all tests with UI (visible monitoring)
   * `npm run cy-run-ci` - runs all the tests without UI
   