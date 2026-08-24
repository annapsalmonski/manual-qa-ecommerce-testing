# Manual QA Testing — E-commerce

## 📌 Project Overview

This project consists of manually testing selected functionalities of an e-commerce web application to verify that they behave as expected and to identify and document potential defects.

## 🎯 Testing Scope

The following areas of the application were tested:

- **Login:** validation of credentials and input fields.
- **Product Catalog:** product display and sorting functionality.
- **Shopping Cart:** adding, removing and managing products.
- **Checkout:** data entry and validation, order summary, order completion, PDF generation and post-purchase navigation.

## 🧪 Testing Approach

The project was primarily based on manual functional testing, supported by ISTQB principles and knowledge of positive, negative and exploratory testing.

Test cases were designed based on the available application behaviour and requirements. Risk-based thinking was also considered when identifying and prioritising potential defects.

### Techniques and approaches used

- Functional Testing
- Positive Testing
- Negative Testing
- Exploratory Testing
- Error Guessing / Experience-based Testing
- Risk-based Testing

## 📚 ISTQB Learning

Additional ISTQB test design techniques, including Equivalence Partitioning, Boundary Value Analysis, Decision Tables and State Transition Testing, were studied as part of the learning process.

These techniques were not necessarily applicable to every functionality due to the absence of specific requirements or boundaries.

## 🐞 Defect Management

Potential defects identified during test execution were documented in individual Bug Reports, including the steps to reproduce the issue, expected result, actual result, severity, priority and supporting evidence.

Two issues were documented during the testing process:

- **BUG-001 — Checkout can be completed with an empty cart:** the application allows the user to finalize an order when no products are present in the cart.
- **BUG-002 — Postal Code accepts alphabetic characters:** the application allows alphabetic characters in the Postal Code field. Since no specific requirement defining the expected Postal Code format was available, the behaviour was documented for further clarification rather than automatically classified as a confirmed defect.

## 📊 Test Results

| Result | Test Cases | Percentage |
|---|---:|---:|
| ✅ PASS | 28 | 93.33% |
| ❌ FAIL | 2 | 6.67% |
| **Total** | **30** | **100%** |

**28 out of 30 test cases passed successfully. Two test cases resulted in FAIL and were documented for further analysis.**

## 🛠️ Tools

- **Sauce Labs** — Application used to perform manual functional testing.
- **Microsoft Excel** — Creation and management of test cases and execution results.
- **Microsoft Word** — Creation of Bug Reports and Test Summary Report.
- **GitHub** — Repository management, documentation storage and version control through commits.

## 📁 Project Structure

```text
manual-qa-ecommerce-testing/
│
├── Bug-Reports/
│   ├── BUG-001-Bug-Report.docx
│   └── BUG-002-Bug-Report.docx
│
├── Test-Cases/
│   └── TEST-CASES-MANUAL-QA.xlsx
│
├── Test-Summary/
│   └── Test-Summary-Report-Sauce-Labs-FINAL.docx
