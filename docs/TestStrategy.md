
# 🧩 Test Strategy Document

## 📄 Project Title: Automation Exercise Website – QA Portfolio Project  
**Author**: Zöhrab Mirzayev  
**Created On**: April 13, 2025  
**Version**: 1.0

---

## 🎯 Objective

The objective of this project is to validate the functionality, usability, performance, and security of [https://automationexercise.com](https://automationexercise.com) using both manual and automated testing approaches.

---

## 🧪 Test Scope

### ✅ In Scope

- Functional UI Testing (Manual & Automation)
- API Testing (Manual & Automation using Postman)
- Regression Testing
- Smoke and Sanity Testing
- Cross-Browser Testing (Chrome, Firefox)
- Documentation and Reporting

### ❌ Out of Scope

- Load Testing
- Mobile Responsiveness Testing (initial phase)
- Multi-language Testing

---

## 🧱 Test Levels

1. **Unit Testing** – Not included (black-box approach)
2. **Integration Testing** – API endpoints and user flows
3. **System Testing** – Entire website functionality
4. **Acceptance Testing** – Final stage validation against requirements

---

## 🔍 Test Types

| Type               | Method           | Tool/Approach          |
|--------------------|------------------|-------------------------|
| Functional         | Manual & Auto    | TestNG, Selenium        |
| UI Testing         | Manual & Auto    | Selenium, Browser DevTools |
| API Testing        | Manual & Auto    | Postman, Newman         |
| Regression Testing | Automation       | TestNG Suites           |
| Negative Testing   | Manual & Auto    | TestNG, Postman         |
| Smoke Testing      | Manual           | Checklist                |

---

## 🛠️ Test Tools & Frameworks

- **Automation**: Java, Selenium WebDriver, TestNG, Maven  
- **API Testing**: Postman, Newman  
- **IDE**: IntelliJ IDEA  
- **Version Control**: Git + GitHub  
- **Reporting**: Allure / ExtentReports  
- **Documentation**: Markdown, Excel

---

## 📂 Test Deliverables

- Test Strategy Document (this file)  
- Test Plan Document  
- Manual Test Cases (Excel)  
- Automated Test Scripts (Java + TestNG)  
- API Collections (Postman)  
- Reports (HTML/PDF)  
- Logs & Screenshots

---

## 🧪 Entry & Exit Criteria

### 🔹 Entry Criteria

- Project repo initialized  
- Website is accessible  
- Test environment is set up  
- Tools configured successfully

### 🔸 Exit Criteria

- All planned test cases executed  
- All critical bugs are resolved  
- Reports and documentation delivered

---

## 🧠 Risks & Mitigation

| Risk                                  | Mitigation                              |
|---------------------------------------|------------------------------------------|
| Changing website structure            | Design resilient locators (XPath/CSS)    |
| Incomplete test coverage              | Continuous review and test case updates  |
| Learning curve for tools              | Practice through small tasks             |

---

## 👤 Test Team & Roles

| Role            | Responsibility                 |
|------------------|-------------------------------|
| Test Lead       | Strategy, Planning, Review     |
| Test Engineer   | Writing and executing tests    |
| Automation Lead | Scripting, CI/CD, Reporting    |
| API Tester      | Postman collection & testing   |
| Documentation   | Markdown/Excel reports         |

(Currently, all roles are handled by Zöhrab Mirzayev as a solo QA.)

---

## 🔄 Maintenance Plan

- Keep test data updated and reusable  
- Maintain modular POM framework  
- Refactor scripts during regression runs  
- Backup reports and results monthly

---

## 🧩 Notes

This document is part of a complete QA portfolio initiative. It will evolve with the project and includes best practices aligned with ISTQB Foundation Level principles.

---

> _“Failing to plan is planning to fail.” — Alan Lakein_  
