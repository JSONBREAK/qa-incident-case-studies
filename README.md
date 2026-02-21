# 🚀 SauceDemo QA Testing Project (Professional Simulation)

## 📋 Project Overview

This project simulates the role of a QA Engineer testing an E-commerce web application, **SauceDemo**, by following a structured and professional Software Testing Life Cycle (STLC).

The objective is to replicate a real-world QA workflow — from requirement analysis to final test reporting — using a live demo application as the system under test.

**Target Website:** https://www.saucedemo.com/  
**Application Owner:** Sauce Labs  

---

## 🎯 Project Objectives

- Apply software testing theory to a real-world web application  
- Perform reverse engineering to derive User Stories and Acceptance Criteria from observed system behavior  
- Design comprehensive Test Cases covering:
  - Positive scenarios  
  - Negative scenarios  
  - Edge cases  
- Practice structured and reproducible Defect Reporting  
- Produce professional QA documentation aligned with industry standards  

---

## 🛠 Testing Process (STLC)

The project follows a structured Software Testing Life Cycle (STLC) divided into the following phases:

### 1️⃣ Requirement Analysis & Documentation

- Analyze system behavior and define functional requirements  
- Create a Requirement Traceability Matrix (RTM)  
- Write User Stories and Acceptance Criteria  

---

### 2️⃣ Test Planning & Design

- Develop Test Scenarios (high-level coverage)  
- Design detailed Test Cases including:
  - Test Steps  
  - Test Data  
  - Expected Results  

---

### 3️⃣ Test Execution & Defect Tracking

- Execute test cases manually on the browser  
- Log identified defects in structured Defect Reports  
- Assign Severity and Priority levels  

---

### 4️⃣ Test Reporting

- Produce a Test Summary Report  
- Evaluate overall system quality  
- Provide testing insights and coverage analysis  

---

## 📂 Repository Structure
```
├── specifications/ # User Stories, Acceptance Criteria, RTM
├── test-cases/ # Test Case documents (Excel / PDF / Markdown)
├── bug-reports/ # Defect reports with evidence (screenshots/logs)
├── reports/ # Test Summary Report
└── README.md
```

---

## 🧠 Testing Scope (Phase 1)

### Authentication Module (Login)

Covered:

- [x] Valid Login (Standard User)  
- [x] Invalid Credentials Handling  
- [x] Locked-Out User Validation  
- [x] UI/UX Validation (Field placeholders, error indicators)  

### Upcoming Phases

- Inventory Management  
- Add-to-Cart Functionality  
- Checkout Process  

---

## 💻 Tech Stack & Tools

**Test Documentation:**  
- Markdown  
- Google Sheets  

**Environment:**  
- OS: Windows 11  
- Browser: Google Chrome  
- Test URL: https://www.saucedemo.com/  

**Bug Tracking:**  
- GitHub Issues (or structured document template)

---

## ⚠ Assumptions & Limitations

- The application under test is a public demo system  
- Backend access is not available  
- Test data is limited to provided demo accounts  
- Performance, API, and Security testing are out of scope  

---

## 📢 How to Navigate This Repository

To review the latest testing artifacts:

- Refer to `test-cases/` for detailed test case documentation  
- Check `bug-reports/` for identified defects  
- View `reports/` for the Test Summary Report  

This repository represents a structured manual QA simulation designed to demonstrate practical testing capability in a real-world scenario.

---

## 🔄 Future Roadmap

### Phase 2 – Automation Testing (Upcoming)

The next phase of this project will extend manual test cases into automated test scripts.

The objective is to convert validated manual scenarios into reliable, maintainable, and deterministic automation suites.

Planned implementation focus:

- Automating high-priority and regression-critical test cases
- Building a structured automation architecture (clear separation of test logic and utilities)
- Enforcing test isolation and immutable test data practices
- Implementing stable asynchronous handling to prevent false positives
- Designing automation that remains reliable under parallel execution

Automation will be implemented only after manual validation is completed to ensure accurate scenario coverage and stable test design.
