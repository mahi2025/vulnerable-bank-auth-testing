# Vulnerable Bank Authentication Testing Project

This repository contains hands-on authentication testing notes and artifacts while exploring the =Vulnerable Bank Application= during my cybersecurity bootcamp. I’m using real-world methods to understand and practice how attacks happen — and how to defend against them.



##  Table of Contents

1. [Project Overview](#project-overview)
2. [Tools Used](#tools-used)
3. [Testing Structure](#testing-structure)
4. [Completed Tests](#completed-tests)
5. [Screenshots](#screenshots)
6. [Resources](#resources)
7. [Progress Tracker](#progress-tracker)

---

##  Project Overview

This project focuses on testing the **authentication mechanisms** of the Vulnerable Bank web application, including:

- SQL Injection in Login Forms
- Weak PIN Reset Brute-force
- JWT Token Manipulation
- Username Enumeration
- Token Storage Vulnerabilities

---

##  Tools Used

- Kali Linux
- Burp Suite Community Edition
- VS Code (for note-taking & repo)
- Git & GitHub
- Python (for scripts & automation)

---

##  Testing Structure

Each test is documented in its own folder with the following structure:

```
/tests/
├── 01_SQL_Injection/
│   ├── notes.md
│   └── screenshot.png
├── 02_PIN_BruteForce/
├── 03_JWT_Manipulation/
...
```

Each folder contains:

-  Notes with steps, findings, and remediations
-  Screenshots for documentation
-  Observations and exploit success/failure results

---

## ✅ Completed Tests



##  Screenshots

Screenshots are stored in the `/screenshots/` folder and referenced from notes.

Example:

```md
![Successful SQLi Login](../../screenshots/sql_login_bypass.png)
```

---

##  Resources

- [OWASP Testing Guide](https://owasp.org/www-project-web-security-testing-guide/)
- [PayloadAllTheThings](https://github.com/swisskyrepo/PayloadsAllTheThings)
- [PortSwigger SQLi Cheatsheet](https://portswigger.net/web-security/sql-injection/cheat-sheet)


Feel free to explore the notes and use the payloads in your own labs. This is a learning project for ethical hacking only. 

