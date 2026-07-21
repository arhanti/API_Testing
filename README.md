# 🛒 E-Commerce API Testing using Postman & Newman
A complete REST API Testing project demonstrating Authentication, CRUD Operations, API Chaining, JavaScript Assertions, Environment Variables and Newman Automation.

![Postman](https://img.shields.io/badge/Postman-FF6C37?logo=postman&logoColor=white)
![Newman](https://img.shields.io/badge/Newman-00A98F)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![REST API](https://img.shields.io/badge/REST-API-blue)
![JSON](https://img.shields.io/badge/JSON-black)
![API Testing](https://img.shields.io/badge/API-Testing-success)



## 📌 Project Overview

This project demonstrates end-to-end API testing of the DummyJSON E-Commerce REST APIs using Postman and Newman.

The collection validates:

- Authentication APIs
- Product APIs
- Cart APIs
- CRUD Operations
- Response Validation
- Status Code Validation
- API Chaining
- Environment Variables
- Collection Variables
- Newman Automation and Reporting


## 🛠 Tech Stack

| Tool | Purpose |
|-------|----------|
| Postman | API Testing |
| Newman | Automated Execution |
| JavaScript | Test Assertions |
| REST API | API Communication |
| JSON | Request & Response |
| GitHub | Version Control |


## 📂 Project Structure

```text
E-Commerce-API-Testing
│
├── README.md
├── Postman Collection
├── Newman Reports
├── Postman Documentation
├── Test Cases
└── Screenshots
```



## 📑 APIs Covered

### Authentication

- Login
- Get Current User Profile

### Products

- Get All Products' Details
- Get 1 Product Details
- Add a New Product
- Update Product
- Delete Product
- Limit and Skip Products
- Negative Scenario_Get 1 Product Details

### Carts

- Get All Carts' Details
- Get 1 Cart Details
- Add a New Cart
- Update Cart
- Delete Cart
- Add Product to Cart
- Negative Scenario_Update Cart


## ✅ Features Tested

✔ Authentication

✔ CRUD Operations

✔ API Chaining

✔ Environment Variables

✔ Collection Variables

✔ JSON Parsing

✔ Response Validation

✔ Negative Case Validation

✔ Status Code Validation

✔ Response Time Validation

✔ Header Validation

✔ Newman Execution

✔ HTML Reporting



# 🌍 Environment Variables

| Variable | Description |
|----------|-------------|
| base_URL | https://dummyjson.com |


# 📁 Collection Variables

| Variable | Description |
|----------|-------------|
| ecom_token | token_value |
| Product_IdNo | 1 |
| Cart_IdNo | 209 |
| addedProduct_id | 195 |
| cart_Id | 1 |







# 🔄 API Chaining

This project demonstrates API chaining by:

- Logging in and storing the access token.
- Reusing Product IDs.
- Reusing Cart IDs.
- Passing variables between requests.


## 📖 API Documentation

Published Postman Documentation:
https://documenter.getpostman.com/view/56306544/2sBY4PQLc5


## 📊 Newman Report

The collection can be executed using Newman.

```bash
newman run "E-Commerce API Testing.postman_collection.json" -e "ECom Environment.postman_environment.json" -r cli,htmlextra --reporter-htmlextra-export "E-Commerce API Testing.html"
```


## 📸 Project Screenshots
