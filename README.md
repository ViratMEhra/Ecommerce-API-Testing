#  E-commerce API Testing Project

This project showcases my ability to perform **API and conversational testing** using **Postman**, as part of my application for a **Testing Intern** role.  
It simulates how a QA Engineer validates an e-commerce API system and ensures the chatbot or order service behaves correctly.



## 🧩 Project Components

### 🧪 Postman Test Collection
The **`api_test_collection.json`** file contains automated test scripts for:
- Fetching orders, items, and payments  
- Creating and updating orders  
- Schema validation  
- Negative testing for invalid endpoints  

These tests cover:
- Response codes (200, 201, 204, 404)
- Performance (response time)
- Data validation and integrity
- Error handling



### 🧰 Mock API
File: **`mock_api.json`**  
Represents a simulated E-commerce API backend containing:
- Orders and order attributes  
- Items purchased  
- Total amount calculations  
- Payment information  

This mock data allows testing without a live backend.

---

### 🧾 Sample Test Cases
| Test Type | Endpoint | Purpose | Expected Result |
|------------|-----------|----------|----------------|
| GET | `/orders` | Retrieve all orders | Status 200 |
| GET | `/orders/:id` | Retrieve one order | Status 200 or 404 |
| POST | `/createOrder` | Create new order | Status 201 |
| PUT | `/updateStatus/:id` | Update order | Status 200 |
| DELETE | `/cancelOrder/:id` | Delete order | Status 204 |
| GET | `/payments` | Validate payments | Valid UPI/COD |
| NEGATIVE | `/wrongURL` | Invalid request | Status 404 |






### 🧠 Skills Demonstrated
- REST API validation using **Postman**
- JSON response testing and schema validation
- Use of assertions, loops, and conditions
- Mock API creation for independent testing
- Documentation & reporting (as a QA Intern)



### 🚀 How to Run
1. Open Postman  
2. Import `api_test_collection.json`  
3. Set base URL (e.g., `https://mockapi.io/projects/<id>`)  
4. Click **Run Collection**  
5. Review test results in the Postman console


### 👨‍💻 Author
**Virat Mehra**  
*Testing Intern — API & Conversational QA Enthusiast*  

