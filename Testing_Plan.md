# Tixify — Testing Plan and Evidence Log

Only mark a test Pass after it has actually been run. Save evidence and redact secrets.

| ID | Test | Expected result | Actual result/evidence |
|---|---|---|---|
| T-01 | Start backend with local config | Starts without fatal errors | [Record] |
| T-02 | Initialize clean MySQL database | Schema loads as documented | [Record] |
| T-03 | Valid registration | Expected response and persistence | [Record] |
| T-04 | Invalid login/input | Appropriate rejection/error | [Record] |
| T-05 | Movie search/details | Results match stored data | [Record] |
| T-06 | City/genre filters | Matching results returned | [Record] |
| T-07 | Theatre/show retrieval | Correct show options returned | [Record] |
| T-08 | Seat layout | States match backend data | [Record] |
| T-09 | Valid booking | Booking stored and confirmation returned | [Record] |
| T-10 | Invalid booking references | Clear validation/error response | [Record] |
| T-11 | Same seat booked twice | No unintended duplicate | [Record] |
| T-12 | Concurrent booking attempts, if supported | Behavior matches defined locking rules | [Record] |
| T-13 | Price/tax summary | Matches documented calculation | [Record] |
| T-14 | Booking history | Only permitted records returned | [Record] |
| T-15 | UI workflow | Pages/assets/requests work as intended | [Record] |
| T-16 | Postman collection | Requests and responses reviewed | [Record] |

## Execution log
Actual date: [Fill] | Tester: [Name] | Environment: [Versions] | Tests: [IDs] | Results/defects: [Actual observations]

Evidence checklist: startup log; sanitized Postman responses; actual UI screenshots; database schema evidence; defect list and retest evidence.
