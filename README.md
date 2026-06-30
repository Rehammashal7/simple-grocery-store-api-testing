# Simple Grocery Store API — QA Test Suite

API testing project for the **Simple Grocery Store API** (`https://simple-grocery-store-api.click`), covering test design, execution via Postman, and defect reporting.

## 📁 Contents

| File | Description |
|---|---|
| `simple_grocery_store_postman_collection.json` | Postman collection with requests + test scripts |
| `Simple_Grocery_Store_API_Test_Cases.xlsx` | 31 test cases (positive/negative) with steps, data, expected/actual results |
| `Bug_Report_Simple_Grocery_Store_API.docx` | Bug report for defects found during testing |

## 🧪 Coverage

Status, API Authentication, Products, Cart, and Orders — each with positive and negative scenarios.

**Result:** 29 Passed / 2 Failed



## 🚀 Getting Started

1. Import `simple_grocery_store_postman_collection.json` into Postman.
2. Create an environment with `Base_Url = https://simple-grocery-store-api.click`.
3. Run via Collection Runner (top-to-bottom — requests depend on variables like `Token`, `CartId`, `itemId`, `orderId` set by earlier steps).



