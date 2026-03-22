# Vulnerability Assessment Report

## 📌 Project Overview
This project focuses on performing a vulnerability assessment on a web application to identify security weaknesses and suggest remediation measures.

---

## 🎯 Objective
- To identify vulnerabilities in a web application  
- To analyze security risks  
- To provide recommendations for improving security  

---

## 🛠️ Tools Used
- Nmap – Port scanning and service detection  
- OWASP ZAP – Vulnerability scanning  
- Browser DevTools – Manual inspection  

---

## 🌐 Target Website
http://demo.testfire.net

---

## 🔍 Methodology
The assessment was performed using the following steps:

1. Scanning open ports using Nmap  
2. Identifying services and server details  
3. Performing vulnerability scan using OWASP ZAP  
4. Analyzing results and classifying risks  

---

## 📊 Findings

### 🔹 Open Ports
- Port 80 (HTTP) – Open  
- Port 443 (HTTPS) – Open  
- Port 8080 – Open  

### 🔹 Server Information
- Apache Tomcat/Coyote JSP engine  

### 🔹 Identified Vulnerabilities
- Cross Site Scripting (XSS)  
- SQL Injection  
- Missing Security Headers  
- Cookie Security Issues  

---

## ⚠️ Risk Levels
| Vulnerability | Risk |
|--------------|------|
| SQL Injection | High |
| XSS | High |
| Open Ports | Medium–High |
| Server Exposure | Medium |
| Missing Headers | Low–Medium |

---

## 🛡️ Recommendations
- Close unnecessary ports (8080)  
- Use HTTPS only  
- Hide server information  
- Implement input validation  
- Add security headers  

---

## ✅ Conclusion
The assessment identified multiple vulnerabilities that can affect the security of the application. Proper security measures should be implemented to reduce risks and protect the system.

---

## 📂 Repository Contents
- report.pdf  
- README.md  

---

## 👨‍💻 Author
B.HARISH  
Cyber Security Intern
