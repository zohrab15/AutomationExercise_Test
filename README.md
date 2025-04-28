
# 🔍 Automation Exercise – Complete Test Project

Welcome to the **Automation Exercise Website Test Suite**, a comprehensive QA project built by **Zöhrab Mirzayev** to showcase both **manual** and **automated** testing skills using modern tools and methodologies.

---

## 📌 Project Summary

This project aims to test all major features of [https://automationexercise.com](https://automationexercise.com) through a combination of **manual**, **Selenium-based automation**, and **API** testing. It is part of a learning journey and serves as a **portfolio project**.

---

## 📂 Project Structure

```
AutomationExercise_Test/
├── README.md
├── TestStrategy.md
├── TestPlan.md
├── manual-TestCases/
│   ├── README.md
│   ├── user-registration.xlsx
│   ├── user-login.xlsx
│   ├── contact-us.xlsx
│   ├── cart.xlsx
│   ├── checkout.xlsx
│   ├── product-page.xlsx
│   ├── newsletter.xlsx
│   └── exploratory-notes.md
├── automation/
│   ├── src/
│   │   ├── pages/
│   │   ├── tests/
│   │   └── utils/
│   ├── pom.xml
│   └── testng.xml
├── postman/
│   ├── collection.json
│   └── newman-reports/
├── screenshots/
├── reports/
└── logs/
```

---

## 🛠️ Tools & Technologies Used

| Category          | Tools                         |
|-------------------|-------------------------------|
| Automation        | Selenium, Java, TestNG        |
| Build Management  | Maven                         |
| IDE               | IntelliJ IDEA                 |
| API Testing       | Postman + Newman              |
| Reporting         | ExtentReports / Allure        |
| Version Control   | Git + GitHub                  |
| OS/Browsers       | Windows, Chrome, Firefox      |

---

## 🧪 Test Types Covered

- ✔ Functional Testing  
- ✔ UI Testing  
- ✔ Manual Test Cases  
- ✔ Regression Testing  
- ✔ Negative Testing  
- ✔ API Testing (GET, POST)  
- ✔ Automation with POM (Page Object Model)

---

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/zohrab15/AutomationExercise_Test.git
```

### 2. Import Project into IntelliJ IDEA  
- Open IntelliJ IDEA  
- Click on "Open" and select the root folder of this project  
- IntelliJ will detect the Maven project automatically  
- Wait for dependencies to download (check bottom-right corner)

### 3. Run TestNG Tests  
- Open `testng.xml`  
- Right-click → Run 'testng.xml'

### 4. View Reports  
- Navigate to `/reports` directory  
- Open the latest report in browser (HTML format)

---

## 📊 Reports & Results

- **Manual Test Cases** – see `manual-TestCases/`  
- **Automation Reports** – available in `reports/`  
- **Postman Collection** – located in `postman/`  
- **Newman API Results** – `newman-reports/`

---

## 📅 Project Timeline

| Phase                  | Dates             |
|------------------------|------------------|
| Planning               | 13 – 15 April    |
| Manual Testing         | 16 – 20 April    |
| Automation Setup       | 20 – 21 April    |
| Automation Scripting   | 22 – 28 April    |
| API Testing            | 24 – 26 April    |
| Reporting & Final Docs | 27 – 30 April    |

---

## 🧠 Lessons Learned

- Designed test strategy and test plan documents  
- Gained hands-on experience with Selenium automation  
- Learned API testing with Postman & Newman  
- Practiced professional documentation  
- Built reusable Page Object Models

---

## 👤 Author

**Zöhrab Mirzayev**  
📧 Email: cehri2015@gmail.com  
🌍 Location: Azerbaijan  
🎯 Focus: QA Engineering, Test Automation, Project Planning

---

## 💡 Future Enhancements

- ⏱️ Add performance testing with JMeter  
- 🔐 Security testing modules  
- 🌐 Multi-browser execution (Selenium Grid)  
- 📱 Responsive & mobile testing

> _“Testing is not just finding bugs, it’s about preventing them and building confidence.”_  
> — *Zöhrab Mirzayev*
