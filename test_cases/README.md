# 📖 Manual Testing Guide

This document provides a structured approach to **manual testing** for an e-commerce platform. It outlines **test scenarios, test cases, execution steps, expected outcomes, and defect tracking** to ensure functionality and system reliability.

---

## 🧭 Testing Scope

The manual testing process focuses on the following key modules:

### 🔐 User Authentication & Account Management
- Sign-Up / Registration
- Sign-In / Login
- Subscription Management
- Contact Us Form

### 🛒 Product & Cart Operations
- Product Listing & Search
- Shopping Cart: Add, Remove, Update Items

### 💳 Checkout & Payment
- Address Validation & Checkout Process
- Payment Gateway Integration
- Invoice Generation & Order Summary

### 🐞 Bug Reporting & Issue Tracking
- Logging defects with severity and priority
- Linking bugs to related test cases

---

## 🧪 Testing Approach

| Activity        | Description |
|----------------|-------------|
| ✅ **Test Case Design** | Structured with steps, data, and expected results |
| ▶️ **Execution**        | Manual execution of test steps on the application |
| 🐛 **Bug Logging**      | Documenting issues with clear context and impact |

---

## 📁 File Structure

Each module has its own dedicated sheet within the test document:

📄 Manual_Testing.xlsx
│
├── SignUp → Account creation scenarios
├── SignIn → Login, session management
├── Product List → Search, filters, and display
├── Contact Us → Form validation and submission
├── Subscription → Opt-in/out processes
├── Shopping Cart → Cart functionality
├── Checkout Process → Address & order flow
├── Payment Processing → Payment validation scenarios
├── Invoice Generation → Invoice display & data accuracy
└── Bug Report → All defect logs

---

## 🐞 Bug Report Section

Each defect is documented using the following structure:

| Field             | Description |
|------------------|-------------|
| **Defect #**         | Unique ID for tracking |
| **Status**           | Open, In Progress, Resolved, Closed |
| **Raised By**        | Tester name |
| **Test on Version**  | Application version |
| **Test Case ID**     | Linked test case |
| **Expected Result**  | Anticipated system behavior |
| **Actual Result**    | What actually happened |
| **Severity**         | Critical / High / Medium / Low |
| **Priority**         | Urgent / High / Medium / Low |

---

## 📌 Notes

- Test cases are designed to be **reusable**, **clear**, and **traceable**.
- Each test scenario aligns with the **functional requirements** of the application.
- Bugs are prioritized based on **user impact** and **business urgency**.

---

## 📈 Outcome

This manual testing guide ensures:

- Thorough validation of critical system functionalities
- Documentation of gaps and issues
- Support for quality assurance in future automation or releases

> For more insights, see the attached `Manual_Testing.xlsx` file.
