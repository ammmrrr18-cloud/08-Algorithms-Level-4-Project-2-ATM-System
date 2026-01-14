# 🏧 Project 2: ATM System Simulation - Level 8

> **"Simulating real-world user experiences through precise logic and secure data management."** 🚀

📌 This is the **second project** within **[Level 08: Algorithms & Problem Solving Level 4](https://github.com/ammmrrr18-cloud/Programming-Foundations-Roadmap/tree/main/08%20-%20Algorithms%20%26%20Problem%20Solving%20Level%204)**. In this project, I have built a **Functional System** that simulates a real-life ATM machine, focusing on secure and seamless interaction between the client and their bank account.

---

## 🔄 What Does This Project Offer? (ATM Features)

I designed this system to provide all the essential operations a client needs when using an ATM:

### 1️⃣ Secure Login System (Client Authentication)
* **Access:** Login is performed using the `Account Number` and `Pin Code`.
* **Verification:** The system validates credentials against the `Clients.text` database before granting access.
* **Session Management:** Once logged in, the client's data is stored in a `CurrentClient` object to manage transactions exclusively for that account.

### 2️⃣ Comprehensive Withdrawal Options
* **Quick Withdraw:** A convenient menu offering fixed amounts (20, 50, 100, up to 1000) to save the client's time.
* **Normal Withdraw:** Allows the client to enter any custom amount. It includes smart validation logic that rejects any amount that is not a multiple of 5.
* **Balance Check:** The system automatically ensures the client has sufficient funds before executing any withdrawal.

### 3️⃣ Deposits & Balance Inquiry
* **Deposit:** A simple interface that enables clients to add funds to their accounts easily.
* **Check Balance:** A dedicated screen that displays the client's current available balance at any time.

---

## 🛠️ Technical Concepts Applied
This **Functional System** focuses on the following engineering principles:

* **Session Management:** Utilizing a global struct to track the authenticated client during the session.
* **Arrays & Vectors:** Used arrays to store quick withdrawal values and vectors for efficient file data management.
* **File Synchronization (Data Persistence):** Instant updates to the `Clients.text` file after every withdrawal or deposit to ensure data accuracy.
* **Robust Validation:** Preventing negative entries, amounts exceeding the balance, and ensuring compatibility with ATM denominations (multiples of 5).

---

## 🔗 Quick Links (Previous Phases)
* **Phase 1 (Foundation):** [Bank System V1](https://github.com/ammmrrr18-cloud/07-Algorithms-Level-3-Bank-Project)
* **Phase 2 (Extension 1):** [Bank Extension V2](https://github.com/ammmrrr18-cloud/Project-2---Bank-Extension---Level-7)
* **Phase 3 (Extension 2):** [Users & Permissions System](https://github.com/ammmrrr18-cloud/08-Algorithms-Level-4-Bank-Extension-2)

---

## 📁 Repository Structure
* **My-Solution:** Contains my full C++ source code for the ATM system.
* **Instructor-Solution:** The model solution by Dr. Mohammed Abu-Hadhoud for technical reference and comparison.

---
*📌 "Building a user experience that simulates reality is what transforms code from mere commands into a real software product."*
