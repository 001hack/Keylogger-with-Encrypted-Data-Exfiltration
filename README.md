# 🔐 Encrypted Keylogger PoC

**Internship Project** as a **Cybersecurity Intern at Elevate Labs** 👨‍💻
A **Proof-of-Concept Keylogger** that captures keystrokes, encrypts them securely, and simulates exfiltration. For **ethical and educational purposes only**!

---

## 🎯 Project Objective

This project demonstrates how keylogging attacks work by:

* Capturing **keyboard input** ⌨️
* **Encrypting sensitive data** 🔒
* Simulating **secure data exfiltration** 📡

---

## 🧰 Tools & Technologies

| Tool           | Purpose                    |
| -------------- | -------------------------- |
| Python 3.7.9   | Programming Language       |
| pynput         | Capture keystrokes         |
| cryptography   | Secure encryption (Fernet) |
| base64         | Encode data for storage    |

---

## 🚀 Features

* 📝 **Capture all keystrokes** with `pynput`
* 🔐 **Encrypt** keystrokes using `Fernet` encryption
* 🕓 **Timestamped logs** for better tracking
* 🌐 **Simulate exfiltration** by printing encrypted data to the console
* ⛔ **Kill switch**: Press `ESC` to stop the keylogger
* 🧑‍💻 Designed for **ethical** and **educational purposes** only!

---

## 📂 Project Structure


Encrypted-Keylogger-PoC

├── poc_keylogger.py         # Main script
├── decrypt_logs             # Auto-generated encryption key
├── requirements.txt         # Python dependencies
├── README.md                # Project overview
│
├── docs/
│   └── project_report.pdf   # Internship report

## ⚠️ Disclaimer

This project is intended for **ethical hacking**, **educational purposes**, and **cybersecurity awareness**. Do **NOT** use this for malicious activities.

---
