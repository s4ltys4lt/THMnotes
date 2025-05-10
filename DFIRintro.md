#  TryHackMe: DFIR - An Introduction

This repository contains my notes and learning summaries from the [TryHackMe: DFIR - An Introduction](https://tryhackme.com/room/dfirintro) room. This course introduces the basics of **Digital Forensics and Incident Response (DFIR)** — a critical component of blue teaming in cybersecurity.

---

##  Overview

- **Platform**: TryHackMe
- **Room**: DFIR - An Introduction
- **Focus Areas**: Forensics, Incident Response, Blue Team, Evidence Collection

---

##  Topics Covered

### 🔹 What is DFIR?
DFIR stands for **Digital Forensics and Incident Response**. It's the practice of identifying, investigating, and mitigating cybersecurity incidents.

### 🔹 The DFIR Process
1. **Preparation** – Establish policies, procedures, and a response team.
2. **Identification** – Detect and analyze indicators of compromise.
3. **Containment** – Limit the scope and impact of the attack.
4. **Eradication** – Remove threats and fix vulnerabilities.
5. **Recovery** – Restore systems and monitor for further activity.
6. **Lessons Learned** – Review the incident and improve procedures.

### 🔹 Order of Volatility
| Order | Data Type                       | Description                          |
|-------|----------------------------------|--------------------------------------|
| 1     | CPU registers, cache            | Most volatile, lost instantly        |
| 2     | RAM                              | Can be extracted with volatility     |
| 3     | Network connections              | Includes ARP tables, routing tables  |
| 4     | Disk                             | Persistent storage                   |
| 5     | Backups, archival media         | Least volatile                       |

### 🔹 Evidence Collection & Imaging
- Use tools like `FTK Imager`, `dd`, or `Autopsy` to create forensically sound disk images.
- Always maintain **chain of custody**.

### 🔹 Hashing
- Used to verify integrity of evidence.
- Common hashes: `MD5`, `SHA-1`, `SHA-256`.

---

##  Tools Introduced

| Tool         | Use Case                                |
|--------------|------------------------------------------|
| FTK Imager   | Disk imaging and preview                 |
| Autopsy      | GUI-based forensic analysis              |
| Volatility   | Memory forensics                         |
| Strings      | Extract readable ASCII/Unicode text      |
| HashCalc     | Generate hashes for file integrity       |

---

##  Key Takeaways

- The DFIR process is as much about **procedure** as it is about tools.
- Evidence must be handled carefully to remain legally admissible.
- Practicing memory and disk forensics is essential for real-world SOC and blue team roles.

---

##  Tags
`#TryHackMe` `#DFIR` `#IncidentResponse` `#DigitalForensics` `#CyberSecurity` `#BlueTeam`

