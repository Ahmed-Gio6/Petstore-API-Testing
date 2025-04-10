


---

# 🐾 Petstore API Testing Project

Welcome to our *complete API testing project* for the [Swagger Petstore](https://petstore.swagger.io/#/) built using *Postman*. This project showcases real-world API testing practices including:

- Detailed test case design
- Bug tracking and reporting
- Professional documentation
- Collaborative teamwork

---

## 🧑‍💻 Team Members

- *Ahmed Saad* – QA Tester, Automation Enthusiast  
- *Lojain Omar* – Test Analyst, Report Specialist

---

## 📁 Project Structure

petstore-api-testing/ │ ├── Postman/        # Postman collection & environment ├── Reports/        # Test cases and bug reports (Excel) ├── Attachments/    # Screenshots & supporting files └── README.md       # Project documentation

---

## 🔧 Tools & Technologies

- *Postman* – For sending requests and running test collections
- *Swagger UI* – Target API platform ([link](https://petstore.swagger.io/#/))
- *Microsoft Excel* – Documentation for test cases and bugs
- *GitHub* – For version control and project hosting

---

## ✅ What We Did

### 1. *Test Planning & Design*  
   - Analyzed all endpoints provided by the Swagger Petstore API  
   - Designed test cases for each major operation: POST, GET, PUT, DELETE  
   - Added validations for edge cases and negative scenarios

### 2. *Postman Collection*  
   - Created a structured collection with folders per endpoint  
   - Added variables through environment for reusability  
   - Used *tests scripts* to assert response status codes, body content, and headers

### 3. *Test Execution*  
   - Manually executed test cases  
   - Used *Collection Runner* for automation  
   - Logged results and captured screenshots for failed cases

### 4. *Bug Reporting*  
   - Detected inconsistencies or issues in API behavior  
   - Documented bugs with proper description, steps to reproduce, expected vs actual results, and severity

---

## 🧪 Sample Tested Scenarios

- POST /pet – Create a new pet with full payload  
- GET /pet/{petId} – Retrieve pet details by ID  
- PUT /pet – Update pet information  
- DELETE /pet/{petId} – Delete a pet  
- Invalid ID formats, missing fields, invalid input data

---

## 📊 Reports

All documentation is available in the Reports/ folder:

- *TestCasesReport.xlsx* – Covers:
  - Test Case ID
  - Endpoint
  - Input data
  - Expected result
  - Actual result
  - Status (Pass/Fail)

- *BugsReport.xlsx* – Contains:
  - Bug ID
  - Summary
  - Steps to reproduce
  - Expected vs actual behavior
  - Severity & Priority

---

## 🖼 Attachments

Located in Attachments/:
- Screenshots for failed test cases
- Evidence for reported bugs

---

## 🚀 How to Run This Project

1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/petstore-api-testing.git

2. Open Postman and import:

Petstore.postman_collection.json

Petstore.environment.json



3. Run the collection manually or using the Collection Runner




---

👨‍🏫 About Us

We're two software engineering students passionate about QA and real-world testing. This project was part of our learning journey to apply:

API analysis

Test case writing

Bug detection

Postman scripting


And document everything in a professional way.


---

📝 License

This project is created for educational and demonstrative purposes.


---

🙌 Thanks for Visiting!

Feel free to explore, fork, or give us a ⭐ if you like our work!

---
