<div align="center">

# 👋 Hi, I'm Aftab Shaikh

## 🎭 QA Automation Engineer

### **Playwright • JavaScript • Selenium • Java • Manual Testing**

<br>

<img src="https://img.shields.io/badge/PRIMARY%20FOCUS-PLAYWRIGHT-45BA4B?style=for-the-badge&logo=playwright&logoColor=white" alt="Primary Focus Playwright">

<img src="https://img.shields.io/badge/PRIMARY%20LANGUAGE-JAVASCRIPT-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="Primary Language JavaScript">

<br><br>

<img src="https://img.shields.io/badge/AUTOMATION-TEST%20ENGINEERING-2563EB?style=for-the-badge" alt="Automation Test Engineering">

<img src="https://img.shields.io/badge/QUALITY-ENGINEERING-7C3AED?style=for-the-badge" alt="Quality Engineering">

</div>

---

# 🧑‍💻 About Me

I'm a **QA Automation-focused engineer** passionate about building reliable, maintainable and scalable software testing solutions.

My **primary focus is Playwright with JavaScript**, with a strong interest in modern End-to-End automation, framework architecture, reusable components and reliable test execution.

Alongside Playwright, I am building knowledge and practical experience in:

- 🎭 Playwright Automation
- 🟨 JavaScript
- 🌐 Selenium
- ☕ Java
- 🧪 Manual Testing
- 🔌 API Testing
- 🔧 Git & GitHub
- ⚙️ CI/CD

> **My goal:** Build automation that is clean, maintainable, reliable and useful for real-world QA engineering.

---

# 🚀 My Primary Automation Stack

<div align="center">

| Priority | Technology | Focus |
|:---:|---|---|
| 🥇 | 🎭 **Playwright** | Primary Automation Framework |
| 🥇 | 🟨 **JavaScript** | Primary Programming Language |
| 🥈 | 🌐 **Selenium** | Web Automation |
| 🥈 | ☕ **Java** | Selenium Automation |
| 🥉 | 🧪 **Manual Testing** | QA Foundation |
| 4️⃣ | 🔌 **API Testing** | Backend Validation |
| 5️⃣ | ⚙️ **Git / CI-CD** | Engineering Workflow |

</div>

---

# 🎭 Playwright

## ⭐ Primary Automation Technology

Playwright is my **main focus for modern web automation**.

### What I'm focusing on

```text
                         PLAYWRIGHT
                              │
             ┌────────────────┼────────────────┐
             │                │                │
             ▼                ▼                ▼
        UI AUTOMATION     E2E TESTING    CROSS BROWSER
             │                │                │
             └────────────────┼────────────────┘
                              │
                              ▼
                       FRAMEWORK DESIGN
                              │
               ┌──────────────┼──────────────┐
               │              │              │
               ▼              ▼              ▼
             POM          FIXTURES       UTILITIES
               │              │              │
               └──────────────┼──────────────┘
                              ▼
                      RELIABLE TESTS
```

### Playwright Skills

| Area | Skills |
|---|---|
| 🎭 Automation | End-to-End, UI Automation |
| 🌐 Browsers | Chromium, Firefox, WebKit |
| 🧩 Architecture | Page Object Model |
| 🧪 Testing | Assertions, Hooks, Fixtures |
| 🔐 Authentication | Login / Session Handling |
| 📊 Reporting | HTML Reports |
| 📸 Debugging | Screenshots, Videos, Traces |
| ⚡ Execution | Parallel Testing |
| 🔄 Data | Test Data Management |
| 🛠️ Utilities | Reusable Helpers |

---

# 🟨 JavaScript

## ⭐ Primary Programming Language

JavaScript is my **primary programming language for Playwright automation**.

### JavaScript Focus

```text
JavaScript
│
├── Variables & Data Types
├── Functions
├── Arrays
├── Objects
├── ES6+
├── Destructuring
├── Modules
├── Promises
├── Async / Await
├── Error Handling
└── Automation Logic
```

### Example Playwright Test

```javascript
import { test, expect } from '@playwright/test';

test.describe('Login Tests', () => {

    test('User should login successfully', async ({ page }) => {

        await page.goto('/login');

        await page
            .getByLabel('Username')
            .fill('testuser');

        await page
            .getByLabel('Password')
            .fill('password');

        await page
            .getByRole('button', { name: 'Login' })
            .click();

        await expect(page)
            .toHaveURL(/dashboard/);

    });

});
```

---

# 🏗️ Playwright Framework Architecture

I prefer a **clean and scalable framework structure** instead of putting everything inside test files.

```text
Playwright-Automation/
│
├── tests/
│   ├── smoke/
│   ├── regression/
│   ├── login/
│   └── dashboard/
│
├── pages/
│   ├── LoginPage.js
│   ├── DashboardPage.js
│   └── HomePage.js
│
├── fixtures/
│   └── testFixtures.js
│
├── utils/
│   ├── helpers.js
│   └── constants.js
│
├── test-data/
│   └── testData.js
│
├── reports/
│
├── playwright.config.js
├── package.json
├── .gitignore
└── README.md
```

### Framework Flow

```text
             TEST CASE
                 │
                 ▼
          PAGE OBJECT MODEL
                 │
                 ▼
             FIXTURES
                 │
                 ▼
          HELPER / UTILITY
                 │
                 ▼
            PLAYWRIGHT
                 │
                 ▼
           BROWSER ACTION
                 │
                 ▼
            ASSERTION
                 │
                 ▼
             REPORT
```

---

# 🌐 Selenium

## Selenium + Java

Selenium is my **secondary web automation stack** and an important part of my QA automation learning.

### Selenium Knowledge

```text
Selenium WebDriver
│
├── Browser Automation
├── Locators
├── XPath
├── CSS Selectors
├── Explicit Wait
├── Implicit Wait
├── Alerts
├── Frames
├── Windows & Tabs
├── Dropdowns
├── Page Object Model
└── Cross-Browser Testing
```

---

# ☕ Java

Java is used as the programming foundation for my Selenium automation track.

### Java Concepts

```text
Java
│
├── OOP
├── Classes & Objects
├── Methods
├── Inheritance
├── Encapsulation
├── Polymorphism
├── Abstraction
├── Collections
├── Exception Handling
├── Interfaces
└── Framework Design
```

---

# 🧪 Manual Testing

Strong manual testing fundamentals are essential for good automation.

### Testing Areas

| Testing Area | Focus |
|---|---|
| 🔍 Requirement Analysis | Understanding requirements |
| 📝 Test Case Design | Creating effective test cases |
| 🧪 Functional Testing | Validating functionality |
| 🔄 Regression Testing | Validating existing features |
| 💨 Smoke Testing | Critical functionality validation |
| 🔎 Sanity Testing | Quick change validation |
| 🧠 Exploratory Testing | Finding unexpected behavior |
| 🖥️ UI Testing | Validating UI workflows |
| 🐞 Defect Reporting | Clear & reproducible bugs |
| 📋 Test Execution | Test execution & analysis |

---

# 🔌 API Testing

API testing is part of my broader QA automation roadmap.

### API Knowledge

```text
                   API TESTING
                        │
          ┌─────────────┼─────────────┐
          │             │             │
          ▼             ▼             ▼
        GET           POST           PUT
          │             │             │
          └─────────────┼─────────────┘
                        │
                        ▼
                    PATCH / DELETE
                        │
                        ▼
                Request Validation
                        │
                        ▼
                Response Validation
                        │
                        ▼
                   JSON / Status
```

### Focus Areas

- HTTP Methods
- Status Codes
- Headers
- Query Parameters
- Path Parameters
- JSON
- Request Validation
- Response Validation
- Authentication
- Negative Testing
- Postman

---

# ⚙️ Git & CI/CD

Modern automation should be part of the development lifecycle.

### CI/CD Flow

```text
Developer
    │
    ▼
Git Commit
    │
    ▼
GitHub
    │
    ▼
CI Pipeline
    │
    ▼
Install Dependencies
    │
    ▼
Run Playwright Tests
    │
    ▼
Generate Report
    │
    ▼
Analyze Results
    │
    ▼
Quality Gate
```

---

# 🛠️ Technology Stack

## 🎭 Primary

<div align="center">

<img src="https://img.shields.io/badge/Playwright-2E2E2E?style=for-the-badge&logo=playwright&logoColor=45BA4B" alt="Playwright">

<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=000000" alt="JavaScript">

<img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=ffffff" alt="Node.js">

</div>

## 🌐 Automation

<div align="center">

<img src="https://img.shields.io/badge/Selenium-43B02A?style=for-the-badge&logo=selenium&logoColor=ffffff" alt="Selenium">

<img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=ffffff" alt="Java">

</div>

## 🧪 Testing

<div align="center">

<img src="https://img.shields.io/badge/Manual%20Testing-2563EB?style=for-the-badge" alt="Manual Testing">

<img src="https://img.shields.io/badge/Functional%20Testing-2563EB?style=for-the-badge" alt="Functional Testing">

<img src="https://img.shields.io/badge/Regression%20Testing-7C3AED?style=for-the-badge" alt="Regression Testing">

<img src="https://img.shields.io/badge/Smoke%20Testing-0891B2?style=for-the-badge" alt="Smoke Testing">

</div>

## 🔌 API

<div align="center">

<img src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=ffffff" alt="Postman">

<img src="https://img.shields.io/badge/REST%20API-2563EB?style=for-the-badge" alt="REST API">

<img src="https://img.shields.io/badge/JSON-111827?style=for-the-badge&logo=json&logoColor=ffffff" alt="JSON">

</div>

## 🔧 Development

<div align="center">

<img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=ffffff" alt="Git">

<img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=ffffff" alt="GitHub">

<img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=ffffff" alt="GitHub Actions">

<img src="https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=ffffff" alt="VS Code">

</div>

---

# 📂 Featured Projects

## 🎭 Playwright E2E Automation Framework

**Primary Project**

**Tech:** `Playwright` `JavaScript` `Node.js`

### Coverage

- End-to-End Testing
- Page Object Model
- Fixtures
- Assertions
- Test Data
- Authentication
- Cross-Browser Testing
- Screenshots
- Videos
- HTML Reports
- Parallel Execution
- Reusable Utilities

---

## 🌐 Selenium Automation Framework

**Secondary Project**

**Tech:** `Selenium` `Java`

### Coverage

- WebDriver
- Locators
- XPath
- CSS Selectors
- Wait Strategies
- Page Object Model
- Browser Automation
- Reusable Utilities

---

## 🔌 API Testing Project

**Tech:** `Postman` `REST API` `JSON`

### Coverage

- GET
- POST
- PUT
- PATCH
- DELETE
- Status Codes
- Request Validation
- Response Validation
- Authentication
- Negative Testing

---

# 🧭 QA Automation Roadmap

```text
                        ┌─────────────────────┐
                        │    QA ENGINEERING   │
                        └──────────┬──────────┘
                                   │
                                   ▼
                        ┌─────────────────────┐
                        │  MANUAL TESTING     │
                        └──────────┬──────────┘
                                   │
                                   ▼
                        ┌─────────────────────┐
                        │     JAVASCRIPT      │
                        └──────────┬──────────┘
                                   │
                                   ▼
                    ┌─────────────────────────────┐
                    │       PLAYWRIGHT 🎭         │
                    │       PRIMARY FOCUS         │
                    └──────────────┬──────────────┘
                                   │
                                   ▼
                    ┌─────────────────────────────┐
                    │    FRAMEWORK ENGINEERING    │
                    │   POM • FIXTURES • UTILS    │
                    └──────────────┬──────────────┘
                                   │
                                   ▼
                    ┌─────────────────────────────┐
                    │      SELENIUM + JAVA        │
                    │    ADDITIONAL AUTOMATION    │
                    └──────────────┬──────────────┘
                                   │
                                   ▼
                    ┌─────────────────────────────┐
                    │       API TESTING           │
                    └──────────────┬──────────────┘
                                   │
                                   ▼
                    ┌─────────────────────────────┐
                    │          CI / CD            │
                    └──────────────┬──────────────┘
                                   │
                                   ▼
                    ┌─────────────────────────────┐
                    │   QUALITY ENGINEERING 🚀    │
                    └─────────────────────────────┘
```

---

# 🎯 Current Learning Focus

<div align="center">

| 🎭 PLAYWRIGHT | 🟨 JAVASCRIPT | 🌐 SELENIUM |
|:---:|:---:|:---:|
| E2E | ES6+ | WebDriver |
| POM | Async/Await | Locators |
| Fixtures | Promises | XPath |
| Assertions | Modules | Waits |
| Reporting | OOP Concepts | POM |

</div>

---

# 🧠 QA Engineering Mindset

```text
       UNDERSTAND
           │
           ▼
      REQUIREMENTS
           │
           ▼
      IDENTIFY RISKS
           │
           ▼
       DESIGN TESTS
           │
           ▼
     MANUAL VALIDATION
           │
           ▼
     AUTOMATE REPEATABLE
          FLOWS
           │
           ▼
      RUN REGRESSION
           │
           ▼
      ANALYZE RESULTS
           │
           ▼
      REPORT DEFECTS
           │
           ▼
     IMPROVE CONTINUOUSLY
```

---

# 📚 Continuous Learning

```javascript
const qaJourney = {

    primaryAutomation: "Playwright",

    primaryLanguage: "JavaScript",

    automation: [
        "Playwright",
        "Selenium"
    ],

    testing: [
        "Manual Testing",
        "Functional Testing",
        "Regression Testing",
        "Smoke Testing",
        "Exploratory Testing"
    ],

    api: [
        "REST API",
        "Postman",
        "JSON"
    ],

    engineering: [
        "Page Object Model",
        "Fixtures",
        "Reusable Utilities",
        "Git",
        "GitHub",
        "CI/CD"
    ],

    mindset:
        "Learn → Practice → Automate → Improve"

};

console.log(
    "Building better software through quality 🚀"
);
```

---

# 📊 GitHub

<div align="center">

<img src="https://img.shields.io/badge/GitHub-aftabshaikh27-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub">

<br><br>

<a href="https://github.com/aftabshaikh27?tab=repositories">
  <img src="https://img.shields.io/badge/VIEW-MY%20REPOSITORIES-2563EB?style=for-the-badge&logo=github&logoColor=white" alt="View Repositories">
</a>

</div>

---

# 🚀 Career Direction

```text
                         QA ENGINEER
                              │
                              ▼
                       MANUAL TESTING
                              │
                              ▼
                       TEST AUTOMATION
                              │
                ┌─────────────┴─────────────┐
                │                           │
                ▼                           ▼
          PLAYWRIGHT 🎭               SELENIUM 🌐
                │                           │
           JAVASCRIPT                     JAVA
                │                           │
                └─────────────┬─────────────┘
                              │
                              ▼
                     FRAMEWORK DESIGN
                              │
                              ▼
                        API TESTING
                              │
                              ▼
                           CI / CD
                              │
                              ▼
                    QA AUTOMATION ENGINEER
                              │
                              ▼
                    QUALITY ENGINEERING
```

---

# 🤝 Let's Connect

<div align="center">

### Interested in QA Automation, Playwright, Software Testing and Quality Engineering?

<br>

<a href="https://github.com/aftabshaikh27">
<img src="https://img.shields.io/badge/GitHub-Follow%20My%20Work-181717?style=for-the-badge&logo=github&logoColor=white" alt="Follow on GitHub">
</a>

<br><br>

**🎭 Playwright • 🟨 JavaScript • 🌐 Selenium • ☕ Java • 🧪 QA**

<br>

*Build Quality. Automate Intelligently. Improve Continuously.*

</div>

---

<div align="center">

### ⭐ Thanks for visiting my profile!

</div>
