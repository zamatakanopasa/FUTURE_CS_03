# 🔐 API Security Risk Analysis – Task 3

## 📌 Internship

Cyber Security Internship – Future Interns

## 📊 Project Overview

This project presents a professional API Security Risk Analysis conducted on a public API (JSONPlaceholder). The goal was to identify common security risks and recommend mitigation strategies, simulating a real-world SaaS security assessment.

---

## 🧪 API Tested

**API:** JSONPlaceholder
**Base URL:** https://jsonplaceholder.typicode.com

### Endpoints:

* `/users`
* `/posts`

---

## 🛠 Tools Used

* Postman (API Testing & Inspection)
* Web Browser (Chrome)

---

## 🔍 Methodology

* Performed read-only testing on public endpoints
* Inspected API responses and headers using Postman
* Analyzed authentication and access control mechanisms
* Identified common API security vulnerabilities

---

## 🚨 Key Security Findings

### 🔴 High Risk

* No Authentication → API accessible without login

### 🟠 Medium Risk

* Excessive Data Exposure (emails, phone numbers, addresses)
* No Rate Limiting → Unlimited API requests

### 🟡 Low Risk

* Lack of Access Control
* Predictable Data Structure (sequential IDs)

---

## 🛡 Recommendations

* Implement authentication (JWT, API keys)
* Restrict sensitive data exposure
* Apply rate limiting (e.g., 100 requests/minute)
* Use role-based access control (RBAC)
* Use non-sequential identifiers (UUIDs)

---

## 📸 Screenshots

Postman request and response screenshots are included in this repository.

---

## 📄 Report

The complete API Security Risk Analysis Report is available in this repository as a PDF.

---

## ✅ Conclusion

The analysis highlights critical API security gaps that could lead to data breaches and system abuse in real-world applications. Implementing proper authentication, data protection, and rate limiting mechanisms is essential to ensure secure API design.

---

## 👨‍💻 Author

**Tinashe Nyakumbi**
