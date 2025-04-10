

# 🐾 Petstore API Testing Project

Welcome to our *API testing project* for the [Swagger Petstore API](https://petstore.swagger.io/#/), designed using *Postman*. This project demonstrates professional API testing practices including:

- Comprehensive test case design  
- Structured bug tracking  
- Collaborative workflow  
- Clear and accessible documentation

---

## 👥 Team Members

- *Ahmed Saad* – QA Engineer | Automation Enthusiast  
- *Lojain Omar* – Test Analyst | Reporting Specialist  

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
- Screenshots of failed test executions  
- Visual evidence for reported bugs  

---

## 🚀 How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/petstore-api-testing.git

2. Open Postman and import the following:

Petstore.postman_collection.json

Petstore.environment.json



3. Run tests:

Manually via Postman

Or using the Collection Runner for batch execution





---

👨‍💻 About Us

We are two software engineering students passionate about Quality Assurance. This project was part of our hands-on learning to apply:

API exploration and analysis

Test design and execution

Postman scripting and validation

Bug tracking and documentation



---

📝 License

This project is intended for educational and demonstration purposes only.


---

🙌 Thank You!

We appreciate your interest! Feel free to:

Explore the repo

Fork it

Or star it if you found it useful


لو حابب أضيف رابط GitHub حقيقي بدل your-username أو تضيف قسم "Future Work" أو "Challenges Faced" قولي.
