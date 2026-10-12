# 🚌 Bus Booking Automation Project

This project automates end-to-end workflows of the **Goibibo Bus Booking application** using **Selenium + Pytest**.  
Modules covered:
- Bus Search
- Bus Selection
- Seat Selection
- Passenger Details
- Payment

---

## 📂 Project Structure

BusAutomation/
│
├── tests/                # Automated test cases
│   └── test_bus_booking_flow.py
│
├── pages/                # Page Object Model classes
│   ├── bus_search_page.py
│   ├── bus_selection_page.py
│   ├── seat_selection_page.py
│   ├── passenger_page.py
│   └── payment_page.py
│
├── locators/             # Element locators (one per module)
│   ├── bus_search_locators.py
│   ├── bus_selection_locators.py
│   ├── seat_selection_locators.py
│   ├── passenger_locators.py
│   └── payment_locators.py
│
├── data/                 # Test data
│   ├── testdata.json
│   └── testdata.csv
│
├── reports/              # Execution reports
│   ├── html_reports/
│   └── screenshots/
│
├── requirements.txt      # Python dependencies
├── conftest.py           # Pytest configuration
└── README.md             # Project documentation


---

## 📊 Test Closure Summary Report

| **Module**             | **Planned** | **Executed** | **Passed** | **Failed** | **Pass %** |
|-------------------------|-------------|--------------|------------|------------|------------|
| Open Goibibo Bus Page   | 10          | 10           | 10         | 0          | 100% |
| Bus Search              | 10          | 10           | 10         | 0          | 100% |
| Bus Listing             | 10          | 10           | 10         | 0          | 100% |
| Bus Filters             | 10          | 10           | 10         | 0          | 100% |
| Bus Details             | 10          | 10           | 10         | 0          | 100% |
| Seat Selection          | 10          | 10           | 9          | 1          | 90% |
| Boarding & Dropping     | 10          | 10           | 10         | 0          | 100% |
| Passenger Details       | 10          | 10           | 10         | 0          | 100% |
| Promo Code              | 10          | 10           | 10         | 0          | 100% |
| Payment                 | 10          | 10           | 9          | 1          | 90% |
| Booking Confirmation    | 10          | 10           | 9          | 1          | 90% |
| Booking History         | 10          | 10           | 10         | 0          | 100% |

---

### 📈 Execution Overview
- **Total Test Cases Written:** 120  
- **Total Test Cases Executed:** 120  
- **Total Test Cases Passed:** 117  
- **Total Test Cases Failed:** 3  
- **Pass Percentage:** 97.5% ✅  

---

🛠️ Tools & Technologies Used
Selenium with Python → Browser automation

Pytest → Test execution framework

Page Object Model (POM) → Maintainable test design

Jira → Bug tracking & test management

Git & GitHub → Version control & collaboration

SQL → Backend data validation

Manual Testing → Functional, regression, UI validation

API Testing (Postman) → REST API validation

## 🚀 How to Run Tests
pytest -v
1. Install dependencies:
   ```bash
   pip install -r requirements.txt

👨‍💻 Author
QA Engineer: Gopichand Pawar

Focus: End-to-end automation, defect tracking, and reporting for Bus Booking project.