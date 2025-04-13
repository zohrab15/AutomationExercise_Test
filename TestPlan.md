# 📝 Test Plan Document

**Project Name:** Automation Exercise Website Testing  
**Test Type:** Manual & Automation  
**Author:** Zöhrab Mirzayev  
**Created Date:** 13 April 2025  
**Version:** 1.0  

---

## 1. 🎯 Objective

The main objective of this test plan is to define the testing strategy, deliverables, test scope, test schedule, and responsibilities for testing [https://automationexercise.com](https://automationexercise.com). The goal is to ensure quality and correctness of the website's key functionalities.

---

## 2. 📌 Scope of Testing

### ✅ In-Scope
- Home Page & Navigation  
- User Registration & Login  
- Product Listing & Filtering  
- Add to Cart & Checkout  
- Contact Form  
- API Testing (with Postman)  
- User Profile Functionality  
- Automation Scripts using Selenium + Java

### 🚫 Out-of-Scope
- Mobile App or Responsive Design  
- Actual Payment Processing  
- Third-party integrations (ads, external links)

---

## 3. 🧪 Test Types

| Test Type             | Description                                      |
|------------------------|--------------------------------------------------|
| Functional Testing     | Test user interactions and UI behavior           |
| Regression Testing     | Ensure existing features work after updates      |
| UI Testing             | Validate UI components and layouts               |
| API Testing            | Test REST endpoints via Postman                  |
| Automation Testing     | Selenium-based test automation for key flows     |
| Negative Testing       | Input validation and edge case handling          |

---

## 4. 🧰 Tools & Technologies

| Tool              | Usage                              |
|-------------------|-------------------------------------|
| IntelliJ IDEA     | Java Development                    |
| Maven             | Project Build and Dependency Mgmt   |
| Selenium WebDriver| Web UI Test Automation              |
| TestNG            | Test Framework & Execution          |
| Postman           | API Testing                         |
| Git + GitHub      | Version Control & Portfolio Hosting |
| Allure/Extent     | Reporting                           |

---

## 5. 🔁 Test Phases & Timeline

| Phase                  | Timeline         |
|------------------------|------------------|
| Requirement Analysis   | 13 - 15 April     |
| Manual Test Design     | 15 - 17 April     |
| Manual Test Execution  | 18 - 20 April     |
| Automation Setup       | 20 - 21 April     |
| Automation Scripting   | 22 - 28 April     |
| API Testing (Postman)  | 24 - 26 April     |
| Report & Documentation | 27 - 30 April     |

> Timeline is flexible as this is a learning project.

---

## 6. 👤 Roles & Responsibilities

| Role           | Responsibility                       |
|----------------|----------------------------------------|
| Zöhrab Mirzayev| All phases: design, testing, automation, documentation |

---

## 7. 📂 Deliverables

- `TestPlan.md`  
- `TestStrategy.md`  
- `manual-testcases.xlsx`  
- Automation code (Java + Selenium)  
- `postman/collection.json`  
- Automation reports (`/reports`)  
- Project documentation in README.md  
- GitHub project repo link

---

## 8. 🛑 Entry & Exit Criteria

### Entry Criteria
- Test environment is set up  
- Website is accessible  
- Requirements understood  
- Tools configured

### Exit Criteria
- All test cases executed  
- Defects (if any) reported  
- Automation scripts stable  
- Documentation completed

---

## 9. ⚠️ Risks & Mitigation

| Risk                                           | Mitigation                            |
|------------------------------------------------|----------------------------------------|
| Site downtime or instability                  | Run tests during off-peak hours        |
| No official API documentation                 | Analyze requests manually via browser tools |
| Automation script failures after UI change    | Use robust locators & POM pattern      |

---

## 10. 📈 Test Metrics

- Test Coverage (% of features tested)  
- Manual Test Case Pass/Fail Count  
- Automation Success Rate  
- Bug Count by Severity  
- API Test Status  
- Execution Time

---

## ✅ Approval

| Name             | Role           | Status   |
|------------------|----------------|----------|
| Zöhrab Mirzayev  | Test Engineer  | ✅ Approved |

---

*Prepared by Zöhrab Mirzayev – 2025*
