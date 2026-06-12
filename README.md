# FakeStore API Test Suite 🛒

A complete API testing project built using **Postman** and **Newman** 
covering the FakeStore REST API with 100+ test cases.

---

## 🧪 Test Coverage

| Module | Requests | Test Cases |
|---|---|---|
| Auth | 3 | 10 |
| Products | 6 | 29 |
| Users | 4 | 20 |
| Carts | 4 | 19 |
| Negative Tests | 7 | 23 |
| **Total** | **24** | **101** |

---

## 🔧 Tools Used

- **Postman** — API testing and test scripting
- **Newman** — CLI test runner
- **newman-reporter-htmlextra** — HTML report generation
- **FakeStore API** — https://fakestoreapi.com

---

## 📋 Types of Testing Covered

- ✅ Functional Testing
- ✅ Negative Testing
- ✅ Boundary Testing
- ✅ Response Schema Validation
- ✅ Response Time Validation
- ✅ Status Code Validation
- ✅ Environment Variable Management

---

## 🚀 How to Run This Project

### Prerequisites
- Install [Node.js](https://nodejs.org)
- Install Newman:
  
  npm install -g newman
  
- Install HTML Reporter:
  
  npm install -g newman-reporter-htmlextra

### Run the tests

newman run FakeStore_API_TestSuite.json -e FakeStore_ENV.json -r htmlextra --reporter-htmlextra-export TestReport.html

---

## 📊 Test Results

![Collection Runner](https://github.com/KrSna02-09/Fakestore-API-Testing/blob/main/collection_runner_screenshot.png)

![Newman HTML Report](https://github.com/KrSna02-09/Fakestore-API-Testing/blob/main/reportFile.png)

