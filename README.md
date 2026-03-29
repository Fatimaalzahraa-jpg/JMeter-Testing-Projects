# 🚀 JMeter Performance Testing Project  

## 📌 Overview  
This project demonstrates **performance testing** using Apache JMeter.  
It focuses on evaluating API performance under different load conditions, measuring response times, throughput, and system stability.  

The test plan simulates multiple users accessing the system simultaneously to identify bottlenecks and ensure the system can handle real-world traffic efficiently.  

---

## 🛠️ Tools & Technologies  
- Apache JMeter  
- HTTP / REST APIs  
- JSON  
- Listeners (Summary Report, View Results Tree)  
- Assertions (Response, Status Code)  
- Correlation (Token Handling)  

---

## 📂 Project Structure  
- **Thread Group:** Simulates virtual users and load distribution  
- **Register API:** Handles user registration under load  
- **Authentication Flow:** Extracts and reuses tokens  
- **Get Tasks API:** Measures response time for retrieving data  
- **Add Todo API:** Tests system behavior when adding tasks under load  
- **HTTP Header Manager:** Manages request headers  
- **Assertions:** Validates responses during performance runs  
- **Listeners:**  
  - View Results Tree (for debugging)  
  - Summary Report (for performance metrics)  

---

## 🧪 Test Scenarios Covered  
- Load testing for user registration  
- Stress testing APIs under high user traffic  
- Performance testing for authentication and token usage  
- Measuring response time for task retrieval and creation  
- Throughput and latency analysis  
- End-to-end workflow performance validation  

---

## ⚙️ How to Run the Project  
1. Install Apache JMeter  
2. Open the project file  
3. Configure **Thread Group**:  
   - Number of Threads (users)  
   - Ramp-up period  
   - Loop count  
4. Click the **Start (▶)** button to execute the test  
5. View results in:  
   - Summary Report  
   - View Results Tree  

---

## 📊 Key Features  
- Performance & load testing using JMeter  
- Simulating concurrent users  
- Measuring response time, throughput, and error rate  
- Token-based authentication handling  
- Scalable and modular test design  

---

## 🎯 Purpose  
The goal of this project is to:  
- Practice performance testing using JMeter  
- Analyze system behavior under load  
- Identify performance bottlenecks  
- Ensure API scalability and reliability  
- Demonstrate performance testing skills  

---

## 👩‍💻 Author  
**Fatima Ibrahim**  
QA / Software Testing Enthusiast  
