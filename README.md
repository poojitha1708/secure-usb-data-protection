# Secure USB Solutions for Enhanced Data Protection

## 🧾 Project Overview  
This project implements a robust solution for securing USB-based data storage and transfer, aimed at protecting sensitive information from unauthorized access, tampering, and leakage. The core focus is on encryption, access control, and anomaly detection for USB devices.

## 🔍 Key Features  
- *USB Encryption*: Automatically encrypt data written to USB storage using strong cryptographic algorithms (e.g., AES-256).  
- *Access Control*: Restrict USB usage to authorized devices/users only; log all access events.  
- *Anomaly/Threat Detection*: Monitor for abnormal USB behavior (e.g., device insertion patterns, unexpected file types), alerting on suspicious activity.  
- *Secure Logging & Audit Trail*: Maintain tamper-resistant logs of USB usage for audit and forensic purposes.
- 
## 🎯 Tech Stack  
- Python 3.x  
- Libraries: OpenCV (for USB detection if using physical webcam/hardware detection), PyUSB (for interfacing with USB devices), Cryptography (for encryption), Pandas/SQLite (for logging)  
- Deployment: Local workstation / Edge device
