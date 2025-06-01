# 🧪 JMeter API Testing Project

This repository contains performance and functional test plans for **RESTful and SOAP-based APIs** using **Apache JMeter**.

---

## 📁 Project Structure

```
.
├── REST_API_Test.jmx     # RESTful API test plan using GET, POST, PUT, DELETE
├── SOAP_API_Test.jmx     # SOAP XML Request test plan
└── README.md             # Project overview and setup instructions
```

---

## 🔧 Tools Used

- [Apache JMeter](https://jmeter.apache.org/) (version 5.6.3)
- Java 8+ (required for JMeter)
- Tested on: Windows 10

---

## ✅ REST API Testing with JMeter

**File**: `REST_API_Test.jmx`  
**Base URL**: `https://reqres.in`

### ✔️ Endpoints Covered:
- `GET /api/users/2` – Get user details
- `POST /api/users` – Create user
- `PUT /api/users/2` – Update user
- `DELETE /api/users/2` – Delete user

### 📊 Reports Used:
- View Results Tree
- Summary Report
- Aggregate Report

---

## ✅ SOAP API Testing with JMeter

**File**: `SOAP_API_Test.jmx`

### ✔️ What It Does:
- Sends a raw SOAP XML request to a sample SOAP web service
- Validates HTTP response and response time
- Uses HTTP Header Manager to set `Content-Type: text/xml`

---

## 📸 Screenshots

| REST Test Plan Example |
|------------------------|
| ![JMeter Rest API](https://github.com/user-attachments/assets/d1153197-72a9-4759-b7a6-dd49b1041d87) |

| SOAP Test Plan Example |
|------------------------|
| ![SOAP_API Request](https://github.com/user-attachments/assets/977b6190-d937-4c89-8452-e69ce74d228e)|

---

## 🧠 How to Run the Tests

1. Install [JMeter 5.6.3+](https://jmeter.apache.org/download_jmeter.cgi)
2. Launch JMeter:
   ```bash
   ./bin/jmeter.bat  # Windows
   ```
3. Open `REST_API_Test.jmx` or `SOAP_API_Test.jmx`
4. Click ▶️ to run the test
5. View results using "View Results Tree" or "Summary Report"

---

## 📌 Author

**Prashant Gautam**  
🔗 [LinkedIn](https://www.linkedin.com/in/gautam-prashant/)

---

