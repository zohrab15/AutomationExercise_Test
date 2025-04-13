# 🧪 Test Strategy Document

**Project:** Automation Exercise Website Testing  
**Test Type:** Manual & Automation Testing  
**Tester:** Zöhrab Mirzayev  
**Date:** 13 April 2025  

---

## 1. 🎯 Objective

The objective of this project is to test [https://automationexercise.com](https://automationexercise.com) thoroughly using both **manual** and **automated** testing approaches. The goal is to:
- Practice different types of testing,
- Build a portfolio-ready GitHub project,
- Document each stage professionally,
- Showcase testing skills and tools.

---

## 2. 📌 Scope of Testing

The following features will be tested:
- Homepage and general accessibility
- User registration and login
- Product search, filtering, and detail views
- Add to cart and checkout flow
- User profile and settings
- Contact form and feedback system
- Public API endpoints (if applicable)

---

## 3. 🔍 Testing Approach

- Start with **manual functional testing** to understand the system.
- Develop **automation scripts** using **Selenium + Java + TestNG**.
- Use **Page Object Model (POM)** for test structure.
- Use **Postman** for API testing (both manual and automated using Newman).
- Generate reports using **ExtentReports** or **Allure**.

---

## 4. 🚫 Out of Scope

- Real payment gateway transactions (only dummy/test cases)
- Mobile version testing (desktop web only)
- Third-party iframes or ads

---

## 5. 💻 Test Environment

- **Browsers:** Chrome (primary), Firefox, Edge  
- **Operating System:** Windows 11 / MacOS  
- **Test Data:** Dummy user profiles, product names, test card numbers

---

## 6. 🛠️ Tools and Technologies

| Tool           | Purpose                          |
|----------------|----------------------------------|
| Selenium       | UI automation testing            |
| Java + Maven   | Project & build management       |
| TestNG         | Test execution & grouping        |
| Postman        | API testing                      |
| Git + GitHub   | Version control & documentation  |
| ExtentReports / Allure | Test reporting           |

---

## 7. 🧪 Test Types to be Covered

- Functional Testing  
- UI Testing  
- Regression Testing  
- API Testing (Manual & Automated)  
- Negative Testing  
- *(Optional: Performance & Security Testing in future)*

---

## 8. ⚠️ Risks and Limitations

- As this is a demo site, some features may be unstable  
- No official API documentation is provided  
- UI changes may break automation scripts

---

## 9. ✅ Success Criteria

- At least 90% of core features are covered with test cases  
- Automation scripts run stably and are repeatable  
- API tests are documented and validated via Postman  
- Project is fully documented and available on GitHub

---

## 📁 Project Structure (Example)
automationexercise-testing/ │ ├── teststrategy.md ├── testplan.md ├── manual-testcases.xlsx ├── automation/ │ ├── src/ │ ├── pom.xml │ └── testng.xml ├── postman/ │ ├── collection.json │ └── newman-reports/ ├── screenshots/ ├── reports/ └── README.md

---

*Prepared by Zöhrab Mirzayev – 2025*

