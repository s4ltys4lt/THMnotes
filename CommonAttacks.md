# Common Attacks – TryHackMe Walkthrough

🗓️ **Date Completed:** [Insert Date]  
🏷️ **Room Link:** [TryHackMe - Common Attacks](https://tryhackme.com/room/commonattacks)

---

## 📘 Room Summary

The **Common Attacks** room provides an overview of some of the most common and dangerous attack techniques used in cybersecurity. The room walks through multiple attack methods such as **SQL Injection (SQLi)**, **Cross-Site Scripting (XSS)**, **Command Injection**, **Buffer Overflow**, and **Denial of Service (DoS)**. It provides hands-on practice with each attack type to give users a better understanding of how they work and how to defend against them.

---

## 🛠️ Tools / Attacks Covered

- **SQL Injection (SQLi)**
- **Cross-Site Scripting (XSS)**
- **Command Injection**
- **Buffer Overflow**
- **Denial of Service (DoS)**

---

## 🔍 Key Concepts Learned

#### 🔹 SQL Injection (SQLi)
- Learned how attackers can inject malicious SQL queries into input fields to manipulate databases.
- Techniques like `UNION SELECT` were used to extract sensitive data.

Example:
```sql
' OR 1=1 -- 
