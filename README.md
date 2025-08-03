# Automated API Testing of DailyFinance using Rest Assured

This project is a complete API automation suite built using **Rest Assured** and follows **Page Object Model (POM)** architecture. The test suite automates user and item management operations on the [DailyFinance](https://dailyfinance.roadtocareer.net/) platform. Postman was used to inspect and organize API endpoints before automation.

---

## ✅ Features Covered

| Category     | Test Scenarios                                                                 |
|--------------|---------------------------------------------------------------------------------|
| **User APIs** | - Register a new user  <br> - Login as Admin <br> - Get user list <br> - Search user by ID <br> - Edit user info <br> - Login as User |
| **Item APIs** | - Get item list <br> - Add new item <br> - Edit item name <br> - Delete item |


---


### 🛑 Negative Test Cases Included

- Register with existing email  
- Login with wrong credentials  
- Search user by invalid ID  
- Edit user with missing fields   
- Delete non-existent item  

---

## 🔗 Project Links

- 🔍 **Postman Collection Documentation**: [View on Postman](https://documenter.getpostman.com/view/45682289/2sB3BAMsb7)  
- 🧪 **Test Cases (Negative + Positive)**: [Google Doc / Excel Sheet Link](https://docs.google.com/spreadsheets/d/1x8YFv-7gxLX-PuW7ftzB19p3wmXfS9Ux/edit?usp=sharing&ouid=105412337074703854140&rtpof=true&sd=true)

---

## 🧰 Tools & Tech Stack

- **JDK 17+**
- **Rest Assured**
- **TestNG**
- **Gradle**
- **Allure Report**
- **Postman**
- **POM (Page Object Model)** for structure

---

## 📸 Allure Report Screenshots

### 🔍 Overview
<img width="1221" height="592" alt="Image" src="https://github.com/user-attachments/assets/e9bd4608-d58f-4bf7-bc1b-3dfab0d02877" />

### 🎯 Behaviors
<img width="1240" height="575" alt="Image" src="https://github.com/user-attachments/assets/7dc270ef-2c36-4d46-9507-6676ce5ca1ae" />

---

## ▶️ How to Run This Project
### 🛠 Requirements
- Java 8+
- Gradle
- Git
- Allure CLI
- Internet access

---

### 🧪 Steps to Run

```bash
# 1. Clone the repository
git clone https://github.com/your-username/daily-finance-api-automation.git
cd daily-finance-api-automation

# 2. Build the project and run tests with specific suite
gradle clean test -PsuiteName="suite.xml"

# 3. Generate Allure report
allure generate allure-results --clean -o allure-report

# 4. Serve Allure report in browser
allure serve allure-results
```
