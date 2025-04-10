

# 🐾 Petstore API Testing Project

Welcome to our *API testing project* for the [Swagger Petstore API](https://petstore.swagger.io/#/), designed using *Postman*. This project demonstrates professional API testing practices including:

- Comprehensive test case design  
- Structured bug tracking  
- Collaborative workflow  
- Clear and accessible documentation

---

## 🙋🏻‍♂ Team Members

- *Ahmed Saad* – Software Tester  
- *Lojain Amr* – Software Tester   

---

## 📂 Project Structure

petstore-api-testing/ │ ├── Postman/         # Postman collections & environments ├── Reports/         # Test cases and bug tracking (Excel) ├── Attachments/     # Screenshots and supporting files └── README.md        # Project documentation

---

## 🛠 Tools & Technologies

- *Postman* – API testing and automation  
- *Swagger UI* – API documentation & interface ([Petstore API](https://petstore.swagger.io/#/))  
- *Microsoft Excel* – Test case and bug report documentation  
- *GitHub* – Version control and project sharing

---

## ✅ Project Workflow

### 1. Test Planning & Design  
- Reviewed all endpoints provided by the Petstore API  
- Designed detailed test cases for CRUD operations (POST, GET, PUT, DELETE)  
- Included edge cases, boundary values, and negative scenarios

### 2. Postman Collection Setup  
- Created modular, folder-based collections  
- Utilized environments and variables for flexibility  
- Added *test scripts* to validate:
  - Status codes  
  - Response body and structure  
  - Headers and response time

### 3. Test Execution  
- Ran tests manually and using Postman's *Collection Runner*  
- Captured evidence (screenshots) for failed test cases  
- Tracked results with clear pass/fail indicators

### 4. Bug Reporting  
- Identified and logged API issues  
- Documented bugs with:
  - Clear summary  
  - Steps to reproduce  
  - Expected vs actual behavior  
  - Severity and priority labels

---

## 🔍 Sample Tested Scenarios

- POST /pet – Add a new pet with valid payload  
- GET /pet/{petId} – Retrieve pet by valid and invalid ID  
- PUT /pet – Update pet details  
- DELETE /pet/{petId} – Remove pet from system  
- Negative scenarios:
  - Invalid IDs
  - Missing required fields
  - Incorrect data types

---

## 📈 Reports

All reports are available in the Reports/ directory:

- *TestCasesReport.xlsx*  
  - Test ID  
  - Endpoint  
  - Input data  
  - Expected & actual results  
  - Test status (Pass/Fail)

- *BugsReport.xlsx*  
  - Bug ID  
  - Description  
  - Reproduction steps  
  - Expected vs actual behavior  
  - Severity & priority

---

## 🖼 Attachments

Stored in Attachments/:
- Screenshots & Video of failed test executions  
- Visual evidence for reported bugs  

---






