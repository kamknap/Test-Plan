#Test Plan for E-commerce Website

**Table of Contents:**

1. Introduction
1. Scope of Testing
1. Test Subject
1. Acceptance Criteria
1. Rejection Criteria
1. Entry Criteria
1. Exit Criteria
1. List of Functionalities to be Tested
1. Test Environment
1. Error Categories
1. Test Location
1. Test Schedule
1. Test Reports
1. List of Tools
1. Incident Management
1. Roles and Responsibilities
-----
1. **Introduction:**

The purpose of this test plan is to thoroughly test the functionality of the e-commerce website based on the provided requirements. The website address is "test.testowanie-oprogramowania.pl." All defects encountered will be fixed and passed to testers for verification.

-----
2. **Scope of Testing:**

Testing levels covered in this test plan:

- Unit Testing
- Integration Testing
- System Testing
- Acceptance Testing
- Regression Testing

Test types covered in this test plan:

- Functional Testing – the software will be validated against the provided specifications.
- Integration Testing – testing communication between APIs, e.g., the "przelewy24" module.
- Automated Testing – implementation of automated tests for key system functionalities according to the provided test cases.
- Performance Testing – assessing the system’s response time and ability to handle high traffic and multiple users.
- Compatibility Testing – verifying the software works across different browsers and devices. 

Test types excluded from this test plan:

- Security Testing – lack of expertise in pentesting within the team.
-----
3. **Test Subject:**

The subject of testing is the e-commerce website accessible at "test.testowanie-oprogramowania.pl" along with all its functionalities.

-----
4. **Acceptance Criteria:**
   1. **Performance Testing:**
      1. The server response time must not exceed 500 ms.
      1. The software must withstand a load of 1000 concurrent users.
   1. **Functional Testing:**
      1. Acceptance criteria must align with the current implementation of the e-commerce website.
   1. **Automated Testing:**
      1. All test cases have been automated.
      1. Tests have been integrated with the CI/CD tool – Jenkins.
-----
5. **Rejection Criteria:**
   1. **Performance Testing:**
      1. Server response time exceeds 500 ms.
   1. **Functional Testing:**
      1. Implemented functionalities do not meet the requirements.
-----
6. **Entry Criteria:**
- The test environment must be set up.
- The test environment must closely resemble the production environment.
- Access to a device with the iOS system.
-----
7. **Exit Criteria:**
- All test cases have been executed.
- All test types and levels covered in this test plan have been completed.
- All defects have been fixed.
-----
8. **List of Functionalities to be Tested:**
- Product Search – Test Case 001.
- Order Placement Process – Test Case 002.
- Integration with the "przelewy24" system – Test Case 003.
- Product Creation – Test Case 004.
- Admin Panel – Test Case 005.
-----
9. **Test Environment:**

Tests for the e-commerce website will be conducted on a dedicated server "test.testowanie-oprogramowania.pl." The test environment will closely match the production environment.

**Specification:**

- Processor: 2 GHz
- RAM: 4GB
- Disk: 240 GB
- OS: Linux Debian 17

Tests will be conducted using the following devices:

1. **PC:**
   1. Processor: Intel I3 3.6 GHz
   1. RAM: 16 GB
1. **Mobile Device with iOS (iPhone 13):**
   1. Processor: Apple A15 Bionic
   1. RAM: 4 GB
   1. iOS version 16
-----
10. **Error Categories (optional):**

Different priorities for defects are distinguished in the test plan:

- Crash
- Blocker
- Critical Error
- Medium Error
- Trivial Error
-----
11. **Test Location:**

Tests will be performed at the software development company's office by a tester.

-----
12. **Test Schedule:**
    1. **Static Testing:**
       1. Verification of the prepared documentation.
       1. Verification of user stories (how each functionality should be implemented). **Time:** 10h
    1. **Functional Testing:**
       1. Verification of implemented functionalities according to the prepared requirements.
       1. Defect reporting.
       1. Execution of test cases. **Time:** 30h
    1. **Performance Testing:**
       1. Verification of server response time.
       1. Verification of server load under user load. **Time:** 14h
    1. **Automated Testing:**
       1. Preparing the file structure.
       1. Implementing automated tests based on provided test cases.
       1. Integrating tests with Jenkins.
       1. Integrating tests with Grafana. **Time:** 40h
-----
13. **Test Reports:**
- Reports on detected defects.
- Designed test cases.
- Automated test scripts.
- Performance test metrics.
-----
14. **List of Tools:**
    1. **Defect Reporting Tools:**
       1. Jira
    1. **Test Case Creation Tools:**
       1. XRay
    1. **Automation Tools:**
       1. Cypress
       1. Jenkins
       1. Grafana
    1. **Performance Testing Tools:**
       1. JMeter
    1. **Screenshot and Video Capture Tools:**
       1. PicPick
       1. ShareX
-----
15. **Incident Management:**

Once a defect is detected, it will be reported in the defect management system (Jira). Each defect will have a priority defined in the test plan and an assigned person responsible for fixing it. Once the developer fixes the defect, it will be passed to the tester for verification. If the defect is correctly fixed, the issue will be closed and moved to the "Done" column. If the defect is incorrectly fixed, the issue will be sent back to the developer for further correction.

-----
16. **Roles and Responsibilities:**
- **Test Manager:** Supervising and organizing the entire testing team’s work.
- **Test Analyst:** Analyzing the test basis. Preparing test assets required for testing. Supporting the Test Manager.
- **Tester:** Executes tasks assigned by the Test Manager, performs testing, and reports defects.
- **System Technical Administrator:** Prepares the test environment and oversees it during the testing process

