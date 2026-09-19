# Biman Bangladesh Airlines — Manual Testing Project

Manual QA testing documentation for [biman-airlines.com](https://www.biman-airlines.com), the official website of Biman Bangladesh Airlines. This repository contains the complete test plan, test scenarios, test cases, execution results, bug reports, and test metrics produced during manual functional, UI, and negative testing of the website.

🔗 **Live Project Sheet:** [Google Sheets Link](https://docs.google.com/spreadsheets/d/1jJZqLt3ipo-WXHW2fV3rx84VN8a5GzEhs5wWid9oEag/edit?usp=sharing)

## 📑 Sheets Overview

| Sheet | Description |
|---|---|
| **Test Plan** | High-level test plan overview and link to the full plan |
| **Mind Map** | Visual breakdown of test coverage areas |
| **Test Scenarios** | 10 test scenarios (TS-01 to TS-10) across major modules |
| **Biman Bangladesh Airlines Test** | 61 detailed test cases (TC-1 to TC-61) with steps, test data, expected/actual results, and status |
| **Bug Report** | Individually logged bugs with reproduction steps, environment, priority, severity, and screenshots |
| **Test Case Summery Report** | Summary of pass/fail/blocked/no-run counts |
| **Test Metrics** | QA execution metrics (pass %, fail %, execution coverage, etc.) |

## 🧠 Mind Map

<img width="809" height="906" alt="Flight_Booking_Manual_Test_Cases_Mind_Map" src="https://github.com/user-attachments/assets/0adc6a23-b7c8-464f-9eb2-8167a573aa77" />

---

## 🧩 Areas Covered

| # | Area | Test Cases | Focus Areas |
|---|------|:----------:|-------------|
| 1 | Homepage | 17 | Page load, layout, logo, navigation menu, Manage My Trip, Flight Status, Flight Schedule, Web Check-in, travel updates, popular destinations, footer, broken links/images, responsiveness, browser compatibility |
| 2 | Flight Booking & Search | 37 | One Way / Round Trip / Multi-City, origin & destination, dates, passenger counts and limits, cabin class, promo code, flight results, fares, timings, duplicate search clicks |
| 3 | FAQ & Office Search | 6 | FAQ page, FAQ search (valid/empty/no match), office search (valid/invalid location) |
| 4 | General | 1 | Mobile responsiveness of important website functions |
| | **Total** | **61** | |

---

## 📈 Key Metrics

| Metric | Result |
|---|---|
| Test Cases Executed | 100% |
| Test Cases Passed | 96.72% |
| Test Cases Failed | 3.27% |
| Test Cases Blocked | 0% |

---

## ▶️ How to Execute

1. Open the test case sheet and pick an area.
2. Review the preconditions and prepare the required test data.
3. Perform each test case on the website.
4. Compare the actual behavior with the expected result.
5. Mark the status as **Pass**, **Fail**.
6. For failures, log a defect with steps to reproduce, screenshots, and environment details.

---

## 🐞 Defect Reporting Template

```
Bug ID:
Title:
Area / Feature:
Severity / Priority:
Environment (Browser / Device / OS):
Preconditions:
Steps to Reproduce:
  1.
  2.
  3.
Expected Result:
Actual Result:
Attachments (Screenshot / Video):
Status:
```

---

## 🔗 User Flow Covered

```
Homepage → Flight Booking Form → Flight Search → Flight Selection → Fare & Flight Details
        ↘ FAQ / Office Search
```

---

## 📊 Test Summary (fill after execution)

| Area | Total | Passed | Failed | Blocked | Not Executed |
|------|:-----:|:------:|:------:|:-------:|:------------:|
| Homepage | 17 | | | | |
| Flight Booking & Search | 37 | | | | |
| FAQ & Office Search | 6 | | | | |
| General | 1 | | | | |
| **Total** | **61** | | | | |


## 🛠️ Test Case Format

Each test case includes:
- **Module** & **Type of Testing**
- **Feature** being tested
- **Test Case** description
- **Reproducing Steps**
- **Test Data**
- **Expected Result** vs **Actual Result**
- **Bug Screenshot/Recording** link (where applicable)
- **Final Status** (Passed / Failed)

## 👤 QA Details

- **Test Executed By:** Mahmuda Binte Sayeed
- **Test Case Developed By:** Mahmuda Binte Sayeed
- **Test Case Reviewed By:** Sabiul Islam Rashed
