# 🎣 Phishing Awareness Simulation - Gophish Lab | Internee.pk Final Project

![Kali Linux](https://img.shields.io/badge/Kali-Linux-557C94?style=flat&logo=kalilinux)
![Gophish](https://img.shields.io/badge/Tool-Gophish-blue)
![Status](https://img.shields.io/badge/Status-Final%20Project-success)

## 📌 Overview
This project is my final project as a **Cyber Security Intern at Internee.pk**. 
It demonstrates a controlled **Phishing Awareness Campaign** using the **Gophish Framework** on **Kali Linux** to understand how social engineering attacks work and why security awareness training is critical.

> **Video Demo:** https://www.linkedin.com/posts/amman-noor-205648321_internee-cybersecurity-finalproject-ugcPost-7509258402875822080-YVAK/?utm_source=share&utm_medium=member_desktop&rcm=ACoAAFFuUyUBqJw1619gECLom2atIGkHD_TAhTg

## ⚠️ Disclaimer
This project was performed in a **100% isolated lab environment (127.0.0.1)** for **educational purposes only**. No real users were targeted. The campaign was run against my own test email.

## 🎯 Objectives
- Understand the lifecycle of a phishing attack
- Configure Gophish framework from scratch
- Simulate a real-world awareness campaign
- Analyze user behavior (Sent -> Opened -> Clicked)

## 🛠️ Tools & Technologies Used
- **OS:** Kali Linux (on VirtualBox)
- **Framework:** Gophish v0.12.1
- **SMTP:** Custom Sending Profile (Test Gmail)
- **Recorder:** Kazam / SimpleScreenRecorder

## ⚙️ Project Workflow

### 1. Gophish Setup
wget https://github.com/gophish/gophish/releases/download/v0.12.1/gophish-v0.12.1-linux-64bit.zip
unzip gophish-v0.12.1-linux-64bit.zip
chmod +x gophish
./gophishAccess panel at: https://127.0.0.1:3333
2. Configuration Steps
Users & Groups: Created TEST USER groupEmail Template: Created Internee Security Awareness Test templateLanding Page: Designed credential awareness pageSending Profile: Configured Internee Test SMTP3. Campaign Launch
Launched campaign Internee Security Awareness Test 2 and tracked results.
📊 ResultsMetricStatusEmail Sent1Email Opened1Clicked Link1Submitted DataSimulatedThis proves how easily a user can be tricked, highlighting the need for awareness.
🎓 Key Learnings
How phishing templates and landing pages are craftedHow SMTP and tracking works in GophishThe importance of Human Firewall in organizationsDocumentation and reporting of a security assessment
