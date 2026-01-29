**Database Exploitation Using SQL Injection Techniques — SQL injection**

🧾 Project Description
This project demonstrates a practical analysis of SQL Injection (SQLi), a critical web application vulnerability that allows attackers to manipulate backend database queries. The project was carried out in a controlled lab environment using a vulnerable website and Kali Linux. SQLMap was used to detect injectable parameters, enumerate databases, extract tables and columns, and demonstrate the impact of SQL injection attacks.

🛠 Tools & Technologies

Kali Linux

SQLMap

Vulnerable Web Application

Web Browser

🎯 Objectives

To understand how SQL Injection vulnerabilities occur

To detect vulnerable input fields in web applications

To exploit SQL Injection using SQLMap

To analyze the security risks caused by SQL Injection

🔍 Methodology

Identified a vulnerable URL parameter by injecting a single quote (') to trigger an SQL error.

Used SQLMap to test the target and confirm SQL Injection vulnerability.

Enumerated available databases using --dbs.

Extracted tables and columns from the target database.

Dumped sensitive data from selected tables.

Documented all findings and security impacts.

⚠ Impact of SQL Injection

Unauthorized access to sensitive data

Ability to modify or delete database records

Risk of authentication bypass

Potential full compromise of the web application

🔐 Prevention Techniques

Use parameterized queries (prepared statements)

Validate and sanitize all user inputs

Use stored procedures

Hide database error messages from users

📁 Project Outcome

This project provided hands-on experience in identifying and exploiting SQL Injection vulnerabilities and understanding their real-world impact on web application security. It strengthened my knowledge of penetration testing and secure coding practices.
