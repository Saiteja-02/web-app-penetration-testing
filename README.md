# Web Application Penetration Testing – Vulnerability Assessment

This project showcases a penetration test conducted on a simulated web application.  
The goal was to identify and exploit common web vulnerabilities, assess risks, and provide remediation strategies.

---

## 📌 Project Scenario
A penetration test was performed on the target host **semiregular.space**, simulating a real-world engagement.  
The objectives were to:
- Assess application security.
- Identify vulnerabilities exposing sensitive data and system integrity.
- Provide remediation aligned with security best practices.

---

## 🔎 Vulnerabilities Identified
1. **SQL Injection** – Exploited unsanitized input to extract database schema and sensitive data.  
2. **Directory Enumeration** – Discovered unsecured directories containing sensitive files.  
3. **User Enumeration & Password Reuse** – Demonstrated weak password binding across accounts.  
4. **Insecure Direct Object Reference (IDOR)** – Manipulated account IDs to access unauthorized user data.  
5. **Improper Access Control** – Retrieved hidden account details via parameter manipulation.  
6. **File Upload Vulnerability** – Uploaded malicious files disguised as images leading to possible code execution.

---

## 🛠️ Tools Used
- **Burp Suite** – Intercepting and modifying requests.  
- **Gobuster** – Directory enumeration.  
- **SQLMap** – Automated SQL Injection testing.  
- **Kali Linux** – Penetration testing environment.  

---

## 🧩 Frameworks Applied
- **OWASP Top 10 (2021):** Injection, Broken Access Control, Identification & Authentication Failures.  
- **Penetration Testing Execution Standard (PTES):** Structured test methodology.  
- **NIST Cybersecurity Framework (CSF):** Identify, Protect, Detect, Respond.  

---

## 🔑 Skills Demonstrated
- Web application penetration testing.  
- Vulnerability exploitation (SQL Injection, IDOR, File Upload).  
- Risk analysis using a risk matrix.  
- Crafting and executing payloads.  
- Using professional penetration testing tools (Burp Suite, SQLMap, Gobuster).  
- Writing clear remediation strategies and reporting.  

---

## 📂 Repository Structure
