


# **🌟 CODEALPHA 🌟**

## Online Shopping System - Internship Project

This repository contains the **Online Shopping System** project developed as part of the **CodeAlpha Internship Program**. The project includes both **static** and **dynamic** security analyses to identify and mitigate vulnerabilities, following best practices in secure coding.

---

## Project Overview

The project focuses on identifying vulnerabilities in the Online Shopping System using **static analysis** with Snyk CLI and **dynamic analysis** with ASST. The analyses revealed several critical vulnerabilities, which have been addressed as per OWASP guidelines.

---

## Tools Used

### Static Analysis
- **Tool:** Snyk CLI
- **Key Vulnerabilities Found:**
  - **Cross-Site Scripting (XSS)** (CWE-79)
  - **SQL Injection** (CWE-89)
  - **Sensitive Cookies without Secure Attributes** (CWE-614, CWE-1004)
  - **Weak Password Hashing** (CWE-916)

### Dynamic Analysis
- **Tool:** ASST (OWASP Free Tool)
- **Key Vulnerabilities Found:**
  - Injection Vulnerabilities (CWE-005)
  - Authentication Weaknesses (CWE-006)
  - Sensitive Data Exposure (CWE-007)
  - Security Misconfigurations (CWE-008)
  - Cross-Site Request Forgery (CWE-009)
  - Server-Side Request Forgery (CWE-010)

---

## Key Features
- Secure coding practices implemented based on analysis results.
- Vulnerability mitigations as per OWASP Top 10 recommendations.
- Integration with **Snyk CLI** and **ASST** for vulnerability detection.


---

## Prevention Techniques Implemented
- Input validation and output encoding for XSS prevention.
- Parameterized queries for SQL Injection mitigation.
- Strong password hashing with bcrypt.
- Secure cookie attributes (`Secure`, `HttpOnly`) enforced.

---


