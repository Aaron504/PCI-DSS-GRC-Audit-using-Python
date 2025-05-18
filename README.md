# PCI DSS GRC Audit using Python
<p align="center">

![Screenshot 2025-05-17 235014](https://github.com/user-attachments/assets/007903ac-7ced-4602-aae5-163f4e8f13d3)


<h1>PCI DSS Compliance Audit using Python (Azure GRC Lab)</h1>

This project simulates a real-world GRC (Governance, Risk, and Compliance) audit against selected PCI DSS (Payment Card Industry Data Security Standard) requirements using a custom Python script. The audit was conducted inside a Windows VM hosted on Microsoft Azure, mimicking a production enterprise environment.

The Python script automates security checks for several key PCI DSS controls, including firewall configuration, antivirus installation, user account validation, logging practices, and the presence of vulnerability scanners. The results are compiled into a professional Excel report for compliance tracking and audit documentation. This hands-on project demonstrates core GRC skills, including compliance validation, scripting automation, and PCI DSS control mapping.



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop Protocol
- Python 3
- Command Prompt

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 11 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- PHASE 1: Set Up Your Audit Environment
- PHASE 2: Select PCI DSS Requirements to Audit
- PHASE 3: Create Audit Script in Python
- PHASE 4: Run the Script and Analyze the Results

<h2>Deployment and Configuration Steps</h2>

PHASE 1: Set Up Your Audit Environment

We’ll use:

- os and subprocess for system checks
- openpyxl for generating Excel-based audit reports

![Screenshot 2025-05-17 231537](https://github.com/user-attachments/assets/2ef4903c-8a34-4658-a0f8-ad9bf0fcdf86)

PHASE 2: Select PCI DSS Requirements to Audit

For the sake of this project, Let’s focus on these key areas:

![Screenshot 2025-05-17 231934](https://github.com/user-attachments/assets/3fb61874-3d49-4dda-9030-74aea16e03ce)

PHASE 3: Create Audit Script in Python

![Screenshot 2025-05-17 232526](https://github.com/user-attachments/assets/66a1975b-f1ab-4022-9952-e8b852c09fc7)
![Screenshot 2025-05-17 232617](https://github.com/user-attachments/assets/edc875a5-44a0-44f2-8fe2-ef6ba26a5396)
![Screenshot 2025-05-17 232733](https://github.com/user-attachments/assets/28921cab-65e9-474b-a7b0-f21a1d1696aa)

PHASE 4: Run the Script

![Screenshot 2025-05-17 233302](https://github.com/user-attachments/assets/81ecffbc-1f1f-4375-9b78-f7867a267425)

Breaking down the results:

![Screenshot 2025-05-17 233808](https://github.com/user-attachments/assets/c583cd6b-014b-4e25-adaf-f00365041d80)

What This Means:
✅ You’re already compliant in 3 of 5 areas checked.

❌ Antivirus check failed because newer Windows versions no longer support wmic.

❌ Vulnerability scanner isn’t installed (which is expected if you didn’t install Nessus).








