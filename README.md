# 💸 Dmoney Transaction Flow - API Testing with Postman & Newman

This project demonstrates automated API testing for a demo fintech system (**Dmoney**) where users like **Agents**, **Customers**, and **Merchants** can interact with each other through financial transactions. The system is managed by an **Admin**, who has access to user creation and fund management.

---

## 🔍 Summary

- Complete API test coverage for Dmoney transaction flows
- Automated test execution with **Newman**
- HTML test reporting using **htmlextra**
- Well-structured test cases with positive and negative scenarios
- Includes bug/improvement report for API responses

---

## ⚙️ Technical Stack

- ✅ Node.js
- ✅ Postman
- ✅ Newman (CLI for Postman)
- ✅ HTML Extra Reporter for clean UI reports

---

## 🚀 How to Run This Project

- clone this repo git clone https://github.com/swarnaDas01/DMONEY-NEWMAN-API-TESTING
   - cd DMONEY-NEWMAN-API-TESTING
- npm i
- create .env file and copy from env.template and set your own PMAT key
   - POSTMAN_API_KEY=your_postman_api_key_here
- Hit this command to run: npm start

## ✨ Features Covered

- Admin creates Agent, Customers, and Merchant
- Deposit from SYSTEM account to Agent
- Agent deposits to Customer
- Agent balance check
- Money transfer from Customer to Customer
- Withdrawal from Customer to Agent
- Balance & transaction statement by trnxId
- Payment from Customer to Merchant
- Merchant balance check
- All actions have negative test cases (invalid data, missing auth, etc.)

## 📄 Documentation and Reports

All relevant files and documentation:

🔗 **Postman API Documentation**:  
https://documenter.getpostman.com/view/47811893/2sB3HhrMfY

📄 **Test Case Google Sheet**:  
https://docs.google.com/spreadsheets/d/1DV7BcxjFegB_ATJEjbfMrmFjAhToGtdWzRaXH4ADr6M/edit?usp=sharing

📊 **Newman HTML Report (htmlextra)**:  
<img width="907" height="893" alt="image" src="https://github.com/user-attachments/assets/0a37a4b5-bc64-4eb3-a5da-96819c286198" />

🐞 **Bug & Improvement Report**:  
[https://your-bug-sheet-link](https://your-bug-sheet-link)


---

## 🔐 Credentials Used

| Role   | Email                      | Password |
|--------|----------------------------|----------|
| Admin  | admin@roadtocareer.net     | 1234     |
| SYSTEM | SYSTEM                     | N/A      |

🔑 **Header Key:**  
`X-AUTH-SECRET-KEY: ROADTOSDET`

- **Base URL**:  
  `https://dmoney.roadtocareer.net`

---

## 🌐 Portal

[Dmoney Portal](http://dmoneyportal.roadtocareer.net)




