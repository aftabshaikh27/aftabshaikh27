<h1 align="center">👋 Hi, I'm Aftab Shaikh</h1>

<h3 align="center">
  🧪 QA Engineer &nbsp;|&nbsp; 🎭 Playwright Automation &nbsp;|&nbsp; 🟨 JavaScript
</h3>

<p align="center">
  <b>Breaking software before users do. 🚀</b>
</p>

<p align="center">
  <a href="https://github.com/aftabshaikh27">
    <img src="https://img.shields.io/badge/GitHub-aftabshaikh27-181717?style=for-the-badge&logo=github">
  </a>
  <img src="https://img.shields.io/badge/Manual%20Testing-Expertise-2E86C1?style=for-the-badge">
  <img src="https://img.shields.io/badge/Playwright-Automation-2E2E2E?style=for-the-badge&logo=playwright">
  <img src="https://img.shields.io/badge/JavaScript-Automation-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black">
</p>

---

<h2>🧑‍💻 About Me</h2>

<p>
I'm passionate about <b>Software Testing, Quality Assurance and Test Automation</b>.
My primary focus is on building reliable and maintainable automation frameworks using
<b>JavaScript + Playwright</b>, backed by strong <b>Manual Testing fundamentals</b>.
</p>

<ul>
  <li>🔍 Strong focus on <b>Manual Software Testing</b></li>
  <li>🎭 Specializing in <b>Playwright Automation</b></li>
  <li>🟨 Writing automation scripts using <b>JavaScript</b></li>
  <li>🧪 Functional, Regression, Smoke & UI Testing</li>
  <li>🐞 Defect Identification & Reporting</li>
  <li>🏗️ Building scalable & maintainable automation frameworks</li>
  <li>🚀 Continuously improving QA & Automation skills</li>
</ul>

---

<h2>🧪 Manual Testing</h2>

<table>
<tr>
<td>🔍 Test Case Design</td>
<td>🧪 Functional Testing</td>
</tr>
<tr>
<td>🔄 Regression Testing</td>
<td>💨 Smoke Testing</td>
</tr>
<tr>
<td>🖥️ UI Testing</td>
<td>🐞 Defect Reporting</td>
</tr>
<tr>
<td>🔎 Exploratory Testing</td>
<td>📋 Test Execution</td>
</tr>
</table>

---

<h2>🎭 Playwright Automation</h2>

<p>
<b>My main automation focus is Playwright with JavaScript.</b>
</p>

<table>
<tr>
<td>🎭 Playwright</td>
<td>🟨 JavaScript</td>
<td>🌐 Cross Browser Testing</td>
</tr>
<tr>
<td>📄 Page Object Model</td>
<td>🧩 Fixtures</td>
<td>✅ Assertions</td>
</tr>
<tr>
<td>🔐 Authentication</td>
<td>📸 Screenshots & Videos</td>
<td>📊 HTML Reports</td>
</tr>
<tr>
<td>🔄 Parallel Execution</td>
<td>🪝 Hooks</td>
<td>🧪 E2E Testing</td>
</tr>
</table>

---

<h2>🛠️ Tech Stack</h2>

<p align="center">

<img src="https://skillicons.dev/icons?i=javascript,nodejs,playwright,git,github,vscode" />

</p>

---

<h2>📂 Automation Framework</h2>

<p>
Currently building professional <b>Playwright + JavaScript</b> automation projects
with clean and scalable architecture.
</p>

<pre>
Playwright-Practice/
│
├── tests/
│   ├── login/
│   ├── dashboard/
│   └── checkout/
│
├── pages/
│   ├── LoginPage.js
│   ├── DashboardPage.js
│   └── CheckoutPage.js
│
├── fixtures/
├── utils/
├── test-data/
│
├── playwright.config.js
├── package.json
└── README.md
</pre>

---

<h2>📚 Currently Learning</h2>

<pre>
JavaScript
   ↓
Playwright
   ↓
Page Object Model
   ↓
Fixtures & Hooks
   ↓
Advanced Automation
   ↓
API Testing
   ↓
CI/CD
   ↓
Quality Engineering 🚀
</pre>

---

<h2>💻 JavaScript + Playwright</h2>

```javascript
import { test, expect } from '@playwright/test';

test('User Login Test', async ({ page }) => {

    await page.goto('https://example.com');

    await page.getByLabel('Username').fill('testuser');

    await page.getByLabel('Password').fill('password');

    await page.getByRole('button', {
        name: 'Login'
    }).click();

    await expect(page).toHaveTitle(/Dashboard/);

});
