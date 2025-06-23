# Honeypot Server to Detect Attack Patterns

**Project by:** Aiswarya S 
**Date:** June 2025  
**Cybersecurity Internship Project**  

---

##  Project Overview

This project involves deploying an SSH honeypot server using Cowrie to detect and analyze real-world attack patterns.

Cowrie was installed on a Linux system and configured to simulate a vulnerable SSH service. The honeypot captured unauthorized connection attempts, brute-force login attempts, and attacker commands. Logs were analyzed to identify attack trends and behaviors.

---

## Tools & Technologies

- Kali Linux OS  
- Cowrie Honeypot v2.6.1  
- Python 3.13.2  
- Twisted 25.5.0  
- IP lookup tools: ipinfo.io, iplocation.net  
- Terminal utilities: cat, less, grep

---

## Steps Performed

1. Installed Linux OS and required packages  
2. Cloned Cowrie honeypot repository  
3. Set up Python virtual environment  
4. Configured Cowrie to listen on port 2222  
5. Ran honeypot for 48 hours  
6. Collected and analyzed logs  
7. Identified common attack patterns  
8. Compiled 2-page project report (attached in this repo)

---

##  Findings Summary

- Total unique attacker IPs: _X_  
- Top attacker countries: _Country1, Country2, Country3_  
- Common usernames: `root`, `admin`, `test`  
- Example attempted passwords: `123456`, `password`, `admin123`  
- Most frequent commands: `uname -a`, `ls`, `wget`

(Full details are in the attached PDF report.)

---

##  Project Report

The full 2-page project report is included in this repository → `Honeypot_Project_Report.pdf`

---

## Conclusion

This project successfully demonstrated the use of a honeypot server for capturing real-world attack patterns. Honeypots provide valuable insights that help improve cybersecurity defenses.

---


---
