# Software Quality Assurance (QA) & UI/UX Testing Portfolio

**Tester:** Muhammad Rizali Hafizhi  
**Location:** Indonesia  
**Contact:** [hafizhi46@gmail.com](mailto:hafizhi46@gmail.com) | [LinkedIn](https://www.linkedin.com/in/muhammad-rizali-hafizhi-a87aa7208/) | [GitHub](https://github.com/rizali46)

---

## 📌 Overview
Welcome to my Software QA & Manual Testing Portfolio. This repository showcases real-world **Test Case Execution Suites** and **Jira-Style Bug Reports** focused on responsive web applications, cross-browser compatibility, UI/UX layout verification, and front-end state management.

With a foundational background in **Computer Science** and hands-on development experience in **JavaScript, TypeScript, React, HTML/CSS, and C#**, I approach QA testing with a developer's mindset—going beyond surface-level symptom reporting to inspect the DOM, analyze CSS layout constraints, and isolate JavaScript event-handling bugs using **Chrome DevTools**.

---

## 🛠️ Testing Skills & Tools
* **Testing Methodologies:** Manual Functional Testing, UI/UX & Visual Regression Testing, Responsive Viewport Testing, Cross-Browser Compatibility, Edge-Case Verification
* **Bug Tracking & Management:** Jira, Trello, Structured Test Case Documentation
* **Inspection & Debugging Tools:** Chrome DevTools (DOM Inspection, CSS Box Model/Flexbox/Grid Analysis, Mobile Device Emulation), Git, VS Code
* **Technical Stack:** JavaScript (ES6+), TypeScript, React, Node.js, HTML5, CSS3, C#, Java

---

## 📂 Portfolio Projects Included in This Repository

### 1. [Polymesh Web Portal / Dashboard UI Audit](./Muhammad_Rizali_Hafizhi_QA_Portfolio_Polymesh.docx)
An end-to-end responsive UI and functional audit of the **Polymesh Mainnet Portal** on mobile viewports.

* **Test Suite Coverage:** 5 structured test cases (`TC-UI-01` through `TC-FUNC-05`) covering navigation drawers, data tables, wallet key/DID truncation, and transaction action modals.
* **Key Defects Documented:**
  * **`BUG-101` (Minor / Medium) – Mobile Sidebar Viewport Clipping:** Identified a responsive layout defect where the left-hand navigation drawer terminates mid-screen above the balance section, clipping the *Authorizations* navigation link due to missing `100vh`/`100dvh` height and overflow scroll rules.
  * **`BUG-102` (Minor / Medium) – Activity Card Responsive Overflow:** Documented a mobile table rendering failure in the *Historical Activity* component where field labels (`ID`, `Date / Time`, `Module`, `Call`, `Status`) stack vertically in empty blocks while data values and the right card border overflow outside the mobile viewport.
  * **`BUG-103` (Major / High) – Secondary Submenu Auto-Dismissal (State Bug):** Isolated an interactive UI state management bug where clicking the secondary ecosystem links menu (*SubScan*, *Governance*, *Developer App*, *Asset Explorer*, *Newsletter*) causes the drawer to flash and auto-close in under 1 second due to click event propagation (`onClickOutside` / event bubbling).

---

### 2. [ZetaHub Cross-Chain "Send" Interface Audit](./Muhammad_Rizali_Hafizhi_QA_Portfolio_ZetaHub.docx)
A focused mobile UI/UX and component positioning audit of the **ZetaHub** cross-chain asset transfer interface.

* **Test Suite Coverage:** 3 structured test cases (`TC-UI-01` through `TC-UI-03`) evaluating dropdown anchor behavior, viewport collision handling, and mobile header accessibility.
* **Key Defects Documented:**
  * **`BUG-101` (Minor / Medium) – Unconstrained Asset Dropdown Viewport Overflow:** Documented a popover positioning defect where the token selection list (`ZETA`, `ETH.ETH`, `BNB.BSC`, etc.) expands across the entire vertical screen—overlapping the top navigation header and clipping bottom items (`ULTI.ETH`)—contrasted side-by-side against the properly anchored *From* network dropdown. Included CSS root-cause remediation notes (`max-height` and `overflow-y: auto`).

---

## 📋 How Each Bug Report is Structured
Every bug ticket in this portfolio follows industry-standard Jira conventions to help developers reproduce and resolve issues quickly:
1. **Bug ID, Title & Component Module**
2. **Severity & Priority Classification**
3. **Exact Test Environment & Preconditions**
4. **Numbered Steps to Reproduce**
5. **Expected Result vs. Actual Result**
6. **Technical / Chrome DevTools Root-Cause Notes** (CSS/DOM/JS analysis)
7. **Annotated Visual Evidence** (Actual vs. Expected screenshots)

---

## 🚀 How to View the Reports
You can view or download the full reports directly from this repository:
* 📄 **[Polymesh Dashboard QA Audit (DOCX / PDF)](./Muhammad_Rizali_Hafizhi_QA_Portfolio_Polymesh.docx)**
* 📄 **[ZetaHub Send Interface QA Audit (DOCX / PDF)](./Muhammad_Rizali_Hafizhi_QA_Portfolio_ZetaHub.docx)**
