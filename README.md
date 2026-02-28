# OWASP Top 10 – Vulnerable vs Secure Demo Web App
# 📌 Overview

This project is an educational demonstration of selected vulnerabilities from the OWASP Top 10 and their secure implementations.
It contains intentionally vulnerable examples alongside corrected secure versions to help understand:
How common web vulnerabilities occur
Why they are dangerous
How to fix them using secure coding practices

# ⚠️ Disclaimer
This project is built strictly for educational and learning purposes.
It must not be used for malicious activity or deployed as a real vulnerable production system.

# 🎯 Objectives

Demonstrate real-world web security flaws
Show secure coding alternative
Help students and beginners understand application security fundamentals
Build practical cybersecurity portfolio experience

# 🗂 Project Structure
owasp-demo/
│
├── index.html
├── xss.html
├── weak-password.html
├── validation.html
│
├── secure/
│   ├── xss-secure.html
│   ├── password-secure.html
│   ├── validation-secure.html
│
├── style.css
└── script.js

# 🔥 Vulnerability Demonstrations

# 1️⃣ Cross-Site Scripting (XSS)
# Vulnerable Version
# • Uses innerHTML
# • Directly renders user input
# • Allows script injection

Example attack payload:

# <script>alert('XSS')</script>
Secure Version
Uses innerText instead of innerHTML
Prevents script execution
Demonstrates output encoding
