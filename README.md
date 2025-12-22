# 🛒 E-commerce API Testing Project (Postman)

## 📌 Project Overview

This project focuses on **end-to-end API testing of a real-world e-commerce system** using **Postman**.
The goal was to understand how backend APIs work in actual products and to validate critical business flows such as **authentication, cart, orders, payments, returns, and notifications**.

Instead of testing isolated APIs, I designed this project to reflect how a **real production system behaves**, where data is interconnected and flows from login → cart → order → delivery.


## 🎯 Objectives

* Validate **core e-commerce functionalities** using API testing
* Practice **realistic backend data structures**
* Write **robust Postman test scripts** covering positive, negative, and edge cases
* Use **Postman environments** for reusability and scalability
* Version-control the testing setup using **GitHub**

## 🧩 APIs Covered

The project includes testing for the following modules:

* 🔐 Authentication (Login, Token handling)
* 👤 User Profile
* 🛍 Products & Categories
* 🛒 Cart Management
* 📦 Orders & Order Status
* 💳 Payments (UPI, Cash on Delivery)
* 🔁 Returns & Refunds
* ⭐ Reviews
* 🔔 Notifications

Each API is linked using IDs (user_id, product_id, order_id) to simulate **real backend relationships**.


## 🧪 Testing Approach

I used **Postman test scripts (JavaScript)** to validate:

* Status codes & response times
* Data integrity (IDs, totals, payment status)
* Business logic (Delivered orders must be paid, COD orders remain pending)
* Calculations (cart total, grand total, refunds)
* Schema structure & required fields
* Authorization and security checks

This approach ensures both **functional correctness** and **data reliability**.

## 🌍 Postman Environment

A dedicated Postman environment is used to manage:

* Base URL
* Access & refresh tokens
* User, product, cart, and order IDs

This makes the test suite **dynamic, reusable, and easy to scale** across different environments (local, staging, QA).

## 🛠 Tools & Technologies Used

* **Postman** – API testing & automation
* **JavaScript** – Test scripting
* **Postman Environments** – Variable management
* **Mock APIs / json-server** – Backend simulation
* **GitHub** – Version control & project sharing

## ▶️ How to Run This Project

1. Import the **Postman Collection**
2. Import the **Postman Environment JSON**
3. Select the environment in Postman
4. Run the login API first to generate tokens
5. Execute other APIs individually or using Collection Runner

## 📈 What I Learned

* How real e-commerce APIs are structured
* How authentication tokens are handled across APIs
* Writing meaningful Postman tests beyond basic status checks
* Designing reusable environments for scalable testing
* Thinking like a QA engineer from a **business + technical perspective**

## 💬 Why This Project Matters

This project demonstrates my ability to:

* Understand backend systems without UI dependency
* Write structured, maintainable API tests
* Validate complex workflows using data-driven testing
* Prepare test assets that are **production and interview ready**

## 👤 Author

**Virat Mehra**
QA / Software Testing Enthusiast
Focused on Manual Testing, API Testing, and Automation Basics
