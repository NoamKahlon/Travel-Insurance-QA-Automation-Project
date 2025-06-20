# 📌 Project Title: Insurance Automation Testing

## 📝 Description
Automated UI testing project for verifying car insurance and travel insurance flows on [https://www.bth.co.il](https://www.bth.co.il), built with Selenium WebDriver, TestNG, and Allure Reports.

The project includes test flows for:
- Checking if a vehicle has valid insurance (valid/invalid license number)
- Filling out multi-step travel insurance forms
- Validating success and error messages
- Screenshot capture on failures

---

## 🧰 Tech Stack
- **Java 17**
- **Maven**
- **Selenium WebDriver** (4.33.0)
- **TestNG** (7.11.0)
- **Allure Reports** (2.13.9)
- **IDE:** IntelliJ IDEA

### ✅ Supported Browsers
- Google Chrome
- Mozilla Firefox
- Microsoft Edge

---

## 📁 Project Structure
```
Project0.2/
├── src/
│   ├── main/
│   │   └── java/
│   │       ├── pages/           # Page Object classes
│   │       ├── flows/           # Reusable flow logic
│   │       └── utils/           # Logger, data, helper methods
│   └── test/
│       └── java/
│           └── tests/           # TestNG test classes
├── pom.xml                      # Maven project file
└── README.md
```

---

## ▶️ How to Run

### 📦 Prerequisites
- Java 17+
- Maven installed (`mvn -v`)
- Chrome / Firefox / Edge browser installed
- Allure CLI installed (optional for viewing report)
- Jenkins installed (optional for CI/CD)


### 🧪 Run Tests and Genrate Allure Report
```bash
mvn clean test ; mvn allure:report
```

1. Go to target/site/allure-maven-plugin/


2. Right-click on index.html


3. Select Open In Browser


## 📸 Features
- Screenshot capture on test failure
- Step-by-step Allure logs
- Validation of message content and color
- Modular design using Page Object Model + Flows

---

## 👤 Author
**Noam Kahlon**
Student submission for automation framework project

---

## 📌 Notes
- Tested on latest versions of Chrome, Firefox, and Edge
- Tests run both locally and are Allure-compatible
