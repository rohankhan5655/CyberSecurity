# 🧠 TryHackMe - Wreath Network (Multi-Host Compromise)

This repository contains my full exploitation report for the **Wreath Network** room on [TryHackMe](https://tryhackme.com/room/wreath).  
The room simulates a **multi-host internal network** where you must gain access to all systems and ultimately compromise the personal machine of a user named **Thomas**.

---

## 🏗️ Network Layout

The Wreath network includes **three machines**:

| Host Type        | OS        | Description                        |
|------------------|-----------|------------------------------------|
| Web Server       | Linux     | Exposed to attacker; initial foothold |
| Git Server       | Windows   | Internal host used by Thomas       |
| Thomas's Machine | Windows   | Final target with sensitive data   |

---

## 🎯 Objective

The goal was to compromise all machines step-by-step and ultimately gain access to **Thomas’s personal Windows machine** using enumeration, lateral movement, and privilege escalation.

---

## 📄 PDF Write-up

I have created a **complete PDF write-up** that documents every step, including:

- 🔍 External & Internal Enumeration
- 🕳️ Exploitation of Linux and Windows services
- 🔁 Lateral Movement across the network
- 🧑‍💼 Privilege Escalation on Thomas’s PC
- 📦 Data Collection
---

## 👤 Author

- **Name:** Muhamad Rohan Khan  
- **TryHackMe:** [MuhammadRohanKhan](https://tryhackme.com/p/MuhammadRohanKhan)  
- **GitHub:** [@rohankhan5655](https://github.com/rohankhan5655)  

---

## ⚠️ Disclaimer

This report is for **educational purposes only**. All actions were performed in a legal lab environment provided by TryHackMe.

---

