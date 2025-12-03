# Manual & API Testing Project – Login, Sign Up & API Validation

This repository contains a complete QA project covering **Manual Testing**, **API Testing**, and **Bug Reporting** for core user functionalities such as **Login**, **Sign Up**, and related API endpoints.

The purpose of the project is to demonstrate structured QA workflow, test design, detailed test documentation, defect reporting, and API validation using Postman.

---

## 📌 Included in the Repository
- **Manual Test Cases** for Login & Sign Up (Excel / Google Sheets)
- **API Testing Collection** (Postman JSON)
- **Bug Reports** (Word / PDF)
- **Screenshots of Defects**
- **Test Scenarios & Expected Results**
- **Positive, Negative & Edge Case Coverage**

---

## 🧪 1. Manual Testing

### 🔐 Login Functionality
Covered scenarios:
- Valid login (positive path)
- Invalid email format  
- Invalid password  
- Empty required fields  
- Case sensitivity tests  
- Error message validation  
- UI & layout verification  
- Redirect after successful login

### 📝 Sign Up Functionality
Covered scenarios:
- Valid account creation  
- Invalid email format  
- Weak password  
- Password mismatch  
- Missing mandatory fields  
- Incorrect input formats  
- Character limits  
- Error message behaviour  
- UI/UX validation  

---

## 🌐 2. API Testing (Postman)

Postman testing includes:
- **GET / POST / PUT / DELETE** requests  
- Functional API tests  
- Response validation (status codes, headers, JSON body)  
- Positive & negative API flows  
- Authentication testing  
- Error-handling verification  
- Test scripts using JavaScript (basic assertions)
- Environment variables for dynamic testing  
- Full Postman collection exported as JSON

---

## 🐞 3. Bug Reports

Bug reports include:
- Clear title and description  
- Steps to reproduce  
- Expected vs. actual result  
- Severity & priority  
- Screenshots attached  
- Environment information  
- Reproducibility  
- Status tracking  

Examples:  
- Incorrect error message on invalid login  
- Validation not triggered on Sign Up fields  
- API returns wrong status code  
- Missing required fields handling  

---

## 📁 Project Structure
```
/TestCases
   Login_TestCases.xlsx
   Signup_TestCases.xlsx

/BugReports
   Login_Bugs.pdf
   Signup_Bugs.pdf

/API
   Postman_Collection.json
   Environment.json

/Screenshots
   login_error.png
   signup_validation.png
```

---

## ▶️ How to Use This Project

### For Manual Tests:
1. Open the TestCases folder  
2. Review or execute test cases step by step  
3. Compare expected vs actual results  
4. Log new findings in BugReports  

### For API Tests:
1. Import the Postman collection  
2. Select environment  
3. Run individual requests or the entire collection  
4. Review assertions and response data  

---

## 🧩 Tools Used
- **Postman** – API Testing  
- **Google Sheets / Excel** – Test Cases  
- **Word / PDF** – Bug Reports  
- **Chrome DevTools** – UI inspection  
- **Jira** (optional) – Bug tracking  

---

## 👩‍💻 Author
**Antonia Ivanova**  
Junior QA / Manual & API Testing  
 


---

If you have any questions or want to validate the test documentation, feel free to reach out!
