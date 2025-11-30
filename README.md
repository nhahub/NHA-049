# E-Commerce Testing Project (Manual + Automation + API + Jira)
This repository contains a complete software testing project for an E-Commerce Website
based on the official SRS document.
The work includes **Manual Testing, Automation Testing (Selenium – Java), API Testing
(Postman),
and Jira task management**.
---
## 1. Introduction
This project aims to validate all requirements of the **Automation Exercise E-Commerce
Website**
according to the SRS provided.
The testing process covers:
- Functional Testing
- UI/UX Testing
- Regression Testing
- API Testing
- Automation Using Selenium + Java 
- Documentation (Test Cases, User stories  , Bug Reports, Jira Boards)
All scenarios were derived strictly from the SRS and mapped to requirements.
---
## 2. Manual Testing
We prepared a full manual testing suite including:
### ✔ Test Artifacts
- Test Plan
- Test Scenarios
- Test Cases (Positive + Negative)
- Traceability Matrix
- Bug Reports
- Execution Report
### ✔ Coverage Based on SRS
Manual testing covered all SRS modules:
- **FR-AUTH** → Signup, Login, Logout, Delete Account
- **FR-PROD** → Products, Search, Filters, Brands, Product Details
- **FR-CART** → Add to cart, Remove, View cart, Total price
- **FR-CHK** → Checkout flow & Payment simulation
- **FR-ADMIN** → Product mangement , order mangement etc.
- **NFR** → Usability, Performance expectations, Responsiveness
A full Excel sheet is included in the repository.
---
## 3. Automation Testing (Selenium + Java)
We automated top **Regression Test Cases** including:
1. **Valid Login**
2. **Invalid Login (Error Message Assertion)**
3. **Add Product to Cart**
4. **Product Search**
5. **Checkout Flow (As far as automation allows)**
### ✔ Tech Stack
- Java
- Selenium WebDriver
- Maven
- Constants Class
- Locators Management
### ✔ Project Structure
/src
/main/java
/pages
/tests
/utils
/constants
Each test corresponds to a requirement in the SRS.
---
## 4. API Testing (Postman)
We tested the publicly available API endpoints such as:
- Login
- Register User
- Create Product
- Get All Products
- Contact Us
- Delete User
### ✔ Deliverables
- API Test Report
Assertions included:
- Status codes
- Response body
- JSON validation
- Error messages
---
## 5. Jira Task Management
We used **Jira** to manage the entire workflow:
### ✔ Jira Items Created
- User Stories (Based on SRS)
- Software Requirments
- Sprint board
- Bug Tickets
- Test Execution tracking
Example User Story:
US-PROD-01 – As a user, I want to view all products so that I can browse the store.
Each story was linked to test cases in the Manual Testing sheet.
---
## 6. Requirement Traceability (SRS → User stories → Test Cases )
We mapped each SRS requirement like this:
| SRS Requirement | User Stories | Test Cases |
|-----------------|------------------|------------|
| REQ_AUTH_002 | US_002  | TC_004 |
| REQ_AUTH_004 | US_004 | TC_008 |
| REQ_PROD_012 | US_012 | TC_023 |
| REQ_CART_019 | US_019 | TC_030 , TC_032 , TC_035 |
| REQ_ADMIN_033 | US_033 | TC_045 , TC_046 |
This ensures full coverage and professional documentation.
---
## 7. Project Files Included
- **Test Plan**
- **SRS Document**
- **Manual Test Cases Excel**
- **Selenium Automation Project (Java)**
- **Jira Snapshots (Stories – Requirements - Bugs – Sprint Board)**
- **API Test cases sheet**
- **Project Presentation**
- **README.md**
---
## 8. Conclusion
The project demonstrates full knowledge of:
- Test Design
- Manual Testing
- API Testing
- Automation Framework
- Jira Workflow
- Requirement Traceability
And all delivered work is fully aligned with the SRS
