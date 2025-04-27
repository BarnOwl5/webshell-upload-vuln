# 🛡️ Webshell Upload Vulnerability Lab

This project explores file upload vulnerabilities leading to webshell execution, analyzing their potential impacts and proposing mitigation strategies through real-world testing.

---

## 📋 Overview

- **Goal**: Identify risks associated with improper file upload handling and verify potential server compromises.
- **Scope**: Focus on webshell upload, server file extraction, MIME type handling, and mitigation via server configuration.

> ⚠️ **Note**  
> This project was conducted on a temporary GCP instance created solely for testing purposes.  
> The server and associated IP address have been deleted, and external access is no longer possible.

---

## 🛠️ Testing Environment

- **Cloud Platform**: Google Cloud Platform (GCP)
- **OS**: Ubuntu 24.04 (via WSL)
- **Web Server**: Apache2 + PHP 8.3
- **Browser**: Chrome

---

## 🔍 Key Highlights

- Uploaded webshells without proper validation.
- Executed remote system commands via uploaded scripts.
- Created and downloaded server file archives without authentication.
- Analyzed server behavior based on MIME type configurations.
- Hardened server security by disabling dangerous PHP functions.

---

## 📄 Full Report

> 📑 [View Full Report](./report/[BarnOwl5]Webshell_Upload_Vulnerability_Lab_Report.pdf)

The full report includes:
- Problem identification and motivation
- Testing methodology and findings
- Risk analysis (Potential Impacts)
- Server mitigation strategies (php.ini modifications)
- Conclusion and personal insights

---

## 🚀 Key Takeaways

- **Minor misconfigurations** can lead to **major security breaches**.
- **Disabling dangerous functions** at the server level effectively mitigates critical risks.
- Practical testing reveals vulnerabilities more clearly than theoretical study alone.

---

## 🧠 Personal Reflection

Through this project, I deepened my understanding of web server vulnerabilities and the importance of proactive security hardening.  
Hands-on testing reaffirmed that **even small oversights** in server configuration can lead to **significant risks**.

---

