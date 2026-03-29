# 🚀 JMeter API Testing Project

## 📌 Overview
This project demonstrates API testing using Apache JMeter.  
It includes multiple test scenarios such as user registration, authentication, and task management APIs.

The test plan simulates real user behavior and validates API responses, status codes, and data integrity.

---

## 🛠️ Tools & Technologies
- Apache JMeter
- HTTP/REST APIs
- JSON
- Assertions (Response, Status Code, Body)
- Test Data Handling
- Correlation (Token Extraction)

---

## 📂 Project Structure

- **Thread Group**: Simulates virtual users
- **Register Page**: Tests user registration flow
- **Register API**:
  - HTTP Header Manager
  - Status Code Assertion
  - Body Assertion
  - Random Data Generation
  - Access Token Extraction
- **Get Tasks API**:
  - Retrieves user tasks
- **Add Todo API**:
  - Adds new tasks
  - Validates responses using assertions
- **Module Controller**:
  - Organizes and reuses test modules
- **View Results Tree**:
  - Displays request/response results for debugging

---

## 🧪 Test Scenarios Covered

- User registration (positive & negative cases)
- API authentication and token extraction
- Creating, retrieving, and managing tasks
- Response validation (status codes and response body)
- Data integrity verification
- End-to-end API workflow testing

---

## ⚙️ How to Run the Project

1. Install Apache JMeter
2. Open the project file:
3. Configure Thread Group if needed:
- Number of Threads (users)
- Ramp-up period
4. Click the **Start (▶)** button to execute the test
5. View results in:
- View Results Tree
- Reports / Listeners

---

## 📊 Key Features

- Automated API testing using JMeter
- Token extraction and reuse
- Data-driven testing
- Response validation using assertions
- Modular test design using controllers

---

## 🎯 Purpose

The goal of this project is to:
- Practice API testing using JMeter
- Simulate real-world user workflows
- Validate backend APIs
- Demonstrate test automation skills

---

## 👩‍💻 Author

Fatima Ibrahim  
QA / Software Testing Enthusiast
