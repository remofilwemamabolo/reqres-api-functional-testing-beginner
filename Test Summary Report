# Test Summary Report

## Project Details
| Field | Details |
|---|---|
| Project | ReqRes API Functional Testing |
| Tester | Remofilwe Mamabolo |
| Date | April 2026 |
| Environment | ReqRes REST API (reqres.in) |
| Tools Used | Postman, Google Sheets |

## Test Execution Summary
| Total Test Cases | Passed | Failed | Blocked |
|---|---|---|---|
| 15 | 14 | 1 | 0 |

## Test Coverage
| Test Level | Number of Tests |
|---|---|
| Unit | 9 |
| Integration | 3 |
| System | 1 |
| UAT | 1 |
| Data Validation | 1 |

## Defects Found
### DEF-001
- **Test Case:** TC05
- **Endpoint:** POST /api/users
- **Summary:** API accepts empty request body and returns 201 Created
- **Expected:** 400 Bad Request with validation error message
- **Actual:** 201 Created with empty user object returned
- **Severity:** Medium
- **Priority:** High
- **Status:** Open
- **Notes:** This indicates the API has no input validation on the users endpoint

## Test Observations
- API now requires an x-api-key header — without it returns 401 Unauthorized
- DELETE /users/2 correctly returns 204 No Content with no response body
- All data validation assertions passed confirming correct field types returned
- Login and register endpoints correctly reject missing password with 400 Bad Request
- End to end system test completed successfully across create, update and delete

## Overall Recommendation
**CONDITIONAL PASS** — 14 out of 15 test cases passed. One defect was found relating
to missing input validation on the POST /users endpoint. This should be reviewed and
fixed by the development team before production release.
