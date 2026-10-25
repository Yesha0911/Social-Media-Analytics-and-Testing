# Social Media Analytics Tool — QA Test Cases

## Project Information
- Project: Social Media Analytics Tool
- Testing Type: Manual Testing
- Tester: Self
- Application: Python-based CLI tool

## Test Cases

| Test Case ID | Feature | Test Scenario | Test Input | Expected Result | Actual Result | Status |
|---|---|---|---|---|---|---|
| TC-01 | Total Likes | Verify total likes calculation | Menu option 2 | Correct sum of Likes column | 80832 | Pass |
| TC-02 | Total Comments | Verify total comments calculation | Menu option 3 | Correct sum of Comments column | 9662 | Pass |
| TC-03 | Total Shares | Verify total shares calculation | Menu option 4 | Correct sum of Shares column | 4093 | Pass |
| TC-04 | Highest Likes | Verify highest-likes user | Menu option 5 | Correct user and highest likes | Riva, 2250 likes | Pass |
| TC-05 | Lowest Likes | Verify lowest-likes user | Menu option 6 | Correct user and lowest likes | Era, 90 likes | Pass |
| TC-06 | Average Likes | Verify average likes calculation | Menu option 7 | Correct average rounded to 2 decimals | 808.32 | Pass |
| TC-07 | User Search | Search for an existing user | Menu option 11 + Rahul | All matching user records displayed | 3 Rahul records displayed | Pass |
| TC-08 | User Search | Search for a non-existing user | Menu option 11 + XYZ123 | "User not found!" displayed | User not found! | Pass |
| TC-09 | Menu Validation | Enter an out-of-range number | Menu option 15 | Invalid choice message displayed | Invalid Choice! Please enter a number between 1 and 12 | Pass |
| TC-10 | Exit | Verify exit option | Menu option 12 | Tool exits gracefully | Tool exited successfully | Pass |