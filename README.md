# AVA NPM NODE Application Tester

## Prerequisites:
- A Node Application
- Test Cases to test the Node Application

## Explanation of package.json
- AVA is a test runner for Node.js with a concise API, detailed error output, embrace of new language features and process isolation that lets you develop with confidence. 

- In package.json, we define the dependencies which are needed for our node application but before that we need to initiate ava using the command `<npm init ava>`.

- After initiating the ava, we need to find out the dependencies needed for our node application and we need to introduce them to our package.json.

- In test.json, we have to define the tests that our node application should pass. So in that you have to define those tests.

## How to use this template?
- Firstly, you have to clone this repo on your local system and paste the files present in it to the root directory of your node project.

- Secondly, In package.json, you have to define the dependencies which are needed for your node application but before that you need to initiate ava using the command `<npm init ava>`.

- Then, In test.json, you have to define the tests that our node application should pass. So in that you have to define those tests.

- After that, you just have to run `<npm install>` to install the dependencies and after that `<npm run test>` to run the test defined in test.js.

- In the last when you are done testing, just run `<npm build>` to build your application and you are done.