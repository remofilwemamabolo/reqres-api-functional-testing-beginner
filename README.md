# ReqRes API Functional Testing Project

## Overview
A functional testing project built to demonstrate core QA skills using the ReqRes REST API.
This project covers the full Software Testing Life Cycle (STLC) from test planning through
to execution, defect reporting and test summary.

**The REST API ResReq is fake API for test case 10 it registers with an existing email.
Reqres does not flag this as an existing email since its a fake API. In real API it should return status 409 conflict**

## Skills Demonstrated
- STLC and SDLC understanding
- Test planning and requirement analysis
- Test case design (positive and negative testing)
- API testing using Postman
- Unit, Integration, System and UAT test levels
- Data validation and assertions
- Defect identification and reporting

## Tools Used
- Postman
- ReqRes API (reqres.in)
- Google Sheets
- GitHub

## Project Structure
- test-plan/ — Mini test plan document
- test-cases/ — Full test case spreadsheet with results
- postman/ — Exported Postman collection with all requests
- assertions/ — Postman assertions reference document
- test-summary/ — Final test summary report

## Test Results Summary
| Total Test Cases | Passed | Failed | Defects Found |
|---|---|---|---|
| 15 | 14 | 1 | 1 |

## Defects Found
**TC05 — API accepts empty body on POST /users**
- Expected: 400 Bad Request
- Actual: 201 Created
- Severity: Medium
- Status: Open

## How to Run the Tests
1. Download the Postman collection from the postman/ folder
2. Import it into Postman
3. Add your ReqRes API key to the Headers tab as x-api-key
4. Run each request and check the results against the test cases spreadsheet
