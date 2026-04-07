##🧪 EasyPay – Manual QA Testing (MFS Mobile App)

This project demonstrates a complete manual testing analysis of the EasyPay Mobile Financial Services (MFS) application.
It highlights my expertise in test design, requirement validation, and defect reporting using real-world financial scenarios.

#📌 Overview

EasyPay is a mobile financial application that provides:

Merchant & utility bill payments
Loan facility with interest conditions

This project focuses on validating business logic, financial calculations, and user flows through structured manual testing.

#🎯 Features Covered
##🔹 Feature 1: Payments & Cashback System
1% service fee (minimum 5 tk)
Cashback rules:
After 5000 tk monthly transactions → 20% cashback (limit 5000 tk)
After 10000 tk monthly transactions → up to 30% cashback
##🔹 Feature 2: Loan System
Loan eligibility if balance < 100 tk
Maximum loan: 20000 tk
No interest if repaid within 30 days
After 30 days → 1.8% daily compound interest
New loan allowed if 50% repayment is completed
##📂 Project Structure
qa-mobile-easypay/
├── acceptance-criteria.md
├── test-cases/
│   └── easypay-test-cases.xlsx
├── bug-reports.md
├── evidence/
│   ├── bug-01.png
│   ├── bug-02.png
│   └── screenshots/
└── README.md
📝 Test Documentation
✔ Acceptance Criteria

#Located in acceptance-criteria.md

Defines:

Payment fee calculation rules
Cashback eligibility conditions
Loan eligibility & repayment rules
Interest calculation logic
Edge conditions for financial thresholds
✔ Test Cases

#Documented in Excel

Covers:

Payment flow validation
Service charge calculations (min & %)
Cashback scenarios (boundary values: 5000, 10000)
Loan eligibility checks
Interest calculation scenarios
Partial repayment & re-loan eligibility

#Each test case includes:

Preconditions
Test steps
Expected results
Actual results
Status (Pass/Fail)
✔ Bug Reports

#Located in bug-reports.md

Includes:

Calculation errors (fees, cashback, interest)
Boundary value issues
Incorrect eligibility validations
UI/UX inconsistencies
Detailed reproduction steps
Severity & priority levels
✔ Evidence


#🔧 Tools & Technologies
Platform: Mobile Application (MFS)
Documentation: Markdown & Excel
Testing Type: Manual Functional Testing
Version Control: GitHub
Approach: Business Logic & Financial Testing
#🎯 Testing Approach

This project follows a risk-based and logic-driven testing approach:

Functional testing
Boundary value analysis
Equivalence partitioning
Exploratory testing
Financial logic validation
Negative testing

#Critical flows tested:

Payment → Fee deduction → Cashback
Loan → Repayment → Interest calculation → Re-loan
#🐞 Key Issues Identified
Incorrect cashback calculation after threshold limits
Minimum service charge not applied correctly in edge cases
Loan eligibility triggered despite balance > 100 tk
Compound interest miscalculated after 30 days
Re-loan eligibility not validated properly after partial repayment
📚 Purpose of This Project

#This repository is part of my QA Portfolio, demonstrating:

Strong understanding of financial system testing
Ability to validate complex business rules
Writing professional test cases & bug reports
Analytical thinking and attention to detail
Real-world problem-solving in QA

#It also reflects my experience in:

Software Quality Assurance
Project coordination and reporting
Teaching technical concepts effectively
👤 Author

Tahreem Asif
Software Quality Assurance Engineer | Project Coordinator

🎓 BS Software Engineering – Iqra University Islamabad
🎓 MS Software Engineering (In Progress) – Air University
💼 Experience: SQA & Project Management
📚 Teaching Experience: 5+ years
