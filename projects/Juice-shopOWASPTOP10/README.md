# OWASP Juice Shop – Penetration Testing Project

This repository contains a full penetration testing assessment performed on the **OWASP Juice Shop** application.  
The project was conducted as part of a practical cybersecurity training program and follows professional methodologies aligned with **OWASP WSTG** and **PTES** standards.

---

##  Project Overview

The objective of this project was to identify, exploit, and document security vulnerabilities within the Juice Shop application using a structured penetration testing approach.  
The assessment covered:

- Frontend behavior  
- Backend API interactions  
- Authentication & authorization mechanisms  
- Input handling and validation  
- Business logic and design flaws  

All findings were documented in a detailed PDF report included in this repository.

---

##  Testing Environment

- **Operating System:** Kali Linux 2024  
- **Platform:** Docker  
- **Application URL:** `http://localhost:8080`
  
- **Tools Used:**  
  - Burp Suite  
  - Browser DevTools  
  - JavaScript Beautifier  
  - CrackStation  
  - Docker  

---

##  Methodology

The penetration test followed internationally recognized standards:

### **1. Reconnaissance**
- Application structure analysis  
- Endpoint discovery  

### **2. Scanning & Discovery**
- Identifying exposed services  
- Mapping the attack surface  

### **3. Vulnerability Analysis**
- Testing OWASP Top 10 categories  
- Evaluating authentication & authorization  

### **4. Exploitation**
- Validating exploitability  
- Attempting to bypass security controls  

### **5. Reporting**
- Documenting findings  
- Assessing severity & impact  
- Providing remediation recommendations  

---

##  Key Vulnerabilities Identified

The assessment revealed multiple vulnerabilities across critical security areas, including:

- Weak default credentials  
- Security misconfigurations  
- Broken access control (Forced Browsing / IDOR)  
- Privilege escalation via role tampering  
- SQL Injection – Authentication bypass  
- CAPTCHA bypass  
- Authentication failures (no rate limiting)  
- IDOR in Basket API  
- Cross‑Site Scripting (XSS)  
- Cryptographic failures  
- Insecure design flaws  

A full explanation of each vulnerability, including exploitation steps and recommendations, is available in the PDF report.

---

##  Vulnerability Summary Table

| Vulnerability | Category | Severity |
|--------------|----------|----------|
| Weak Default Credentials | Authentication | High |
| Security Misconfiguration | Configuration | Medium |
| Forced Browsing / IDOR | Access Control | High |
| Role Tampering | Privilege Escalation | Critical |
| SQL Injection | Injection | Critical |
| CAPTCHA Bypass | Authentication | Medium |
| No Rate Limiting | Authentication | High |
| Basket IDOR | Access Control | High |
| XSS | Injection | High |
| Cryptographic Failures | Cryptography | High |
| Insecure Design | Design | Medium |

---

##  Report

The full penetration testing report is available in this repository as a PDF file:

**`OWASP Juice Shop Penetration Testing Report.pdf`**

It includes:

- Detailed findings  
- Screenshots  
- Technical analysis  
- Exploitation steps  
- Severity assessment  
- Recommendations  

---

##  Conclusion

The assessment demonstrated that the Juice Shop application contains multiple vulnerabilities across authentication, authorization, input validation, and cryptographic controls.

**Overall security posture: Requires significant improvement.**

This project highlights the importance of secure coding practices, proper access control, and continuous security testing.

---

##  Author

**Judy Muhammad Darwish**  
Cybersecurity & Penetration Testing Trainee  
