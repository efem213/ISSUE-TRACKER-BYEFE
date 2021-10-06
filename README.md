# FreeCodeCamp
#### Information Security & Quality Assurance Projects - ISSUE TRACKER
---

All tests passed. Both client and server working as expected.

#### Try it out!

If you want to try the converter, open [this link on Heroku](https://issue-tracker-efe.herokuapp.com/).

#### Test the app

To test the app, just run ```npm test``` (after ```npm i```, of course).

##### User Stories

1. Complete the necessary routes in /routes/api.js
2. Create all of the functional tests in tests/2_functional-tests.js
3. Copy the sample.env file to .env and set the variables appropriately
4.To run the tests uncomment NODE_ENV=test in your .env file
5.To run the tests in the console, use the command npm run test. To open the Replit console, press Ctrl+Shift+P (Cmd if on a Mac) and type "open shell"

# Write the following tests in tests/2_functional-tests.js:

1.Create an issue with every field: POST request to /api/issues/{project}
2.Create an issue with only required fields: POST request to /api/issues/{project}  
3.Create an issue with missing required fields: POST request to /api/issues/{project}
4.View issues on a project: GET request to /api/issues/{project}
5.View issues on a project with one filter: GET request to /api/issues/{project}
6.View issues on a project with multiple filters: GET request to /api/issues/{project}
7.Update one field on an issue: PUT request to /api/issues/{project}
8.Update multiple fields on an issue: PUT request to /api/issues/{project}
9.Update an issue with missing _id: PUT request to /api/issues/{project}
10.Update an issue with no fields to update: PUT request to /api/issues/{project}
11.Update an issue with an invalid _id: PUT request to /api/issues/{project}
12.Delete an issue: DELETE request to /api/issues/{project}
13.Delete an issue with an invalid _id: DELETE request to /api/issues/{project}
14.Delete an issue with missing _id: DELETE request to /api/issues/{project}




---

[EFE AKPULLUKCU](https://twitter.com/SoftwareLoading)