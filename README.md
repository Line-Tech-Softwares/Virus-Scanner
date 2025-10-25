# 🛡️ Line Tech Antivirus

**Version:** 1.00  
**Developer:** Line Tech Softwares  
**License:** © Line Tech Softwares. All rights reserved.  
**Website:** [https://linetechsoftwares.co.za](https://linetechsoftwares.co.za)

---

## 📖 Overview

**Line Tech Antivirus** is a lightweight, offline-friendly security application developed by **Line Tech Softwares**.  
It scans, detects, and prevents potential threats without requiring any online APIs.  
The app also includes an **Integrity Checker**, a **Log Manager**, and an **Offline Update System** to ensure your system stays secure and consistent.

---

## 🚀 Features

### 🧠 Smart Local Scanning
- Detects unusual file patterns using custom local rules.  
- Displays real-time scan progress and results.  
- Runs efficiently using multithreaded scanning.

### 🧩 File Integrity Checker
- Computes **SHA-256 hashes** of important files (Desktop, Documents, Downloads, Projects, Pictures).  
- Detects:
  - Modified files  
  - Missing files  
  - New/unknown files  
- Generates detailed logs automatically (saved in `/logs/`).

### 🧾 Log System
- Each scan generates a timestamped report (e.g., `scan_2025-10-25_18-32-11.txt`).  
- Logs are stored locally for privacy and easy tracking.

### 🔄 Offline Update Checker
- Compares your local app version to the latest version hosted online.  
- Alerts you when a new version is available.  


### ⚙️ Optional Auto-Updater (ZIP-Based)
- Downloads the latest version archive from the Line Tech website.  
- Extracts it safely to an `update_temp` folder for manual installation.  
- Keeps the system secure and easy to maintain.

---

## 💻 Installation

1. Download the latest version of **Line Tech Virus Scanner** from the official site:  
   👉 [https://linetechsoftwares.co.za/projects](https://linetechsoftwares.co.za/projects)
2. Extract the ZIP file to your desired location.  
3. Run the application double clicking the icon.
