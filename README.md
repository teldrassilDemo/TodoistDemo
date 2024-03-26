
TODOIST-TEST
-----------
todoist-test is a framework to automate acceptance test cases of the todoist app.


FEATURES TESTED
---------------

Acceptance tests.

- Login
- Projects

These features are applied to UI.

REQUIREMENTS
-----------------------------------

The required configuration for this framework is the following:

    - Visual studio code
    - Install Cucumber JS allure
    - Download https://www.npmjs.com/package/allure-cucumberjs
    - Download https://github.com/allure-framework/allure-js
    - Download https://github.com/allure-framework/allure-js/blob/master/packages/allure-cucumberjs/README.md
    - Clone/download the project from GitHub repository: [https://github.com/teldrassilDemo/TodoistDemo

CONFIGURATIONS
-----------------------------------
Once those requirements are done, follow these steps:

- Open the project downloaded with the Visual studio code.
- Open the config.app.ts file 

Set the required parameters:

    email: '', //todoist user email
    password: '', //todoist user password
    url: 'https://app.todoist.com/',
    apiUrl: 'https://api.todoist.com/rest/v2/',
    apiToken: '', //todoist api token

  

After executing those steps the frame should be executed.

To execute by command line you can use the following:
       npx cucumber-js
   
