# API Testing Project: User Data Service

## Project Introduction
This is an API testing project based on JSONPlaceholder, covering the following functions:
- Get user information (GET)
- Add user information (POST)
- Verify error response (GET)

## Tools to use
- Postman: This is for creating and managing API tests.
- Newman: This is for running Postman collections and generating reports.

## File structure
- `User_Data_API_Tests.json`: Postman collection file.
- `newman/`: Newman test report.

## Test report file
The project contains two formats of test reports:
- HTML format: `newman/report.html`, suitable for viewing in a browser.
- JSON format: `newman/report.json`, suitable for data processing or further integration.

## Run steps
1. Use Postman to import the collection file.
2. Run the following command to execute the test:
```bash
newman run User_Data_API_Tests.json -r html
