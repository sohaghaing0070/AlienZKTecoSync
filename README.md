# Alien Soft ZKTeco Attendance Hub Enterprise v2.5

[![Version](https://img.shields.io/badge/Version-v2.5.0_PRO-00c853?style=for-the-badge&logo=windows)](https://github.com/sohaghaing0070/AlienZKTecoSync)
[![Platform](https://img.shields.io/badge/Platform-Windows_10_%7C_11_%7C_Server-0078d7?style=for-the-badge&logo=windows)](https://github.com/sohaghaing0070/AlienZKTecoSync)
[![Offline](https://img.shields.io/badge/Installation-100%25_Offline-ff6d00?style=for-the-badge)](https://github.com/sohaghaing0070/AlienZKTecoSync)
[![Database](https://img.shields.io/badge/Database-Oracle_%7C_MySQL_%7C_SQLite-009688?style=for-the-badge)](https://github.com/sohaghaing0070/AlienZKTecoSync)

**Alien Soft ZKTeco Attendance Hub Enterprise** is a high-performance Windows desktop application and background sync service engineered for real-time biometric attendance synchronization between ZKTeco devices and Enterprise Databases (Oracle, MySQL, SQLite, Webhooks, ADMS/Push).

---

## 📥 Download Official Releases

| Package Type | File Name | Description |
| :--- | :--- | :--- |
| **Setup Installer (Recommended)** | [`AlienZKTecoSync_v2.5_Setup.exe`](https://github.com/sohaghaing0070/AlienZKTecoSync/releases/download/v2.5.0/AlienZKTecoSync_v2.5_Setup.exe) | One-click offline installer wizard with desktop & start menu shortcuts |
| **Portable Version** | [`AlienZKTecoSync_v2.5_Portable.zip`](https://github.com/sohaghaing0070/AlienZKTecoSync/releases/download/v2.5.0/AlienZKTecoSync_v2.5_Portable.zip) | Standalone portable archive — extract & run without installation |

---

## 🌟 Key Highlights & Core Capabilities

### 1. ⏱️ Intelligent Multi-Protocol ZKTeco Synchronization
* **Direct Standalone Sync:** High-speed direct TCP/IP and UDP communication protocol connecting to ZKTeco standalone terminals (K40, UFace, iClock, IN01, SilkFP, and more).
* **Live Capture Stream:** Real-time event listening mode captures punch-in/out records instantly as employees scan their fingers, RFID cards, or face.
* **Auto-Polling & Failover Engine:** Robust background thread polls devices at configurable intervals (1s to 3600s) with automatic exponential backoff, socket reconnection, and error recovery.

### 2. 🌐 Built-in ADMS & Cloud Push Receiver
* **Integrated HTTP Push Server:** Acts as an ADMS/iClock Cloud server receiving push attendance logs from remote ZKTeco devices located across multiple branches or behind NAT/firewalls.
* **Bi-directional Handshake:** Standard ZKTeco ADMS protocol compatibility supporting `cdata`, `registry`, and query commands.

### 3. 🗄️ Enterprise Multi-Database Engine
* **Oracle Database Integration:** Native `python-oracledb` engine supporting Oracle 11g, 12c, 18c, 19c, 21c, and 23ai in both Thin (zero client) and Thick (Instant Client) modes.
* **MySQL / MariaDB Support:** Ultra-fast bulk insert and duplicate prevention engine for MySQL enterprise databases.
* **Embedded SQLite Storage:** Local standalone storage for offline operation, caching, and local record preservation.
* **Auto Table Creation & Column Detection:** Dynamically detects target database schemas, creates missing attendance tables, and maps punch fields automatically.

### 4. 📡 Real-Time Webhooks & REST API Dispatcher
* **ERP & HRMS Integration:** Real-time JSON payload dispatching to SAP, Odoo, Oracle ERP, ERPNext, Laravel, Node.js, and custom REST API endpoints.
* **Persistent Webhook Queue:** Failed webhook deliveries are safely queued in SQLite and retried automatically with customizable retry counts and delays.

### 5. 👥 Full Biometric Employee Management
* **Device User Management:** Upload, download, edit, and delete employee profiles directly from the desktop dashboard.
* **Fingerprint & Face Template Management:** Full backup and migration of biometric fingerprint templates (V10.0/V9.0) and facial recognition data between terminals.
* **Time Synchronization:** Automatically synchronizes terminal hardware clocks with the Windows host or network NTP server.

### 6. 🗂️ Automated Database Backup & Retention Manager
* **Zero-Downtime Hot Backups:** Automatically schedules daily, weekly, or monthly database backups without interrupting live sync operations.
* **Rotation & Retention Policy:** Automatically purges backups older than a user-defined threshold to save disk space.

### 7. 💻 Modern Desktop GUI & Background Tray Monitor
* **Enterprise Modern Theme:** Responsive UI with real-time status LED indicators, live punch activity stream, and throughput graphs.
* **System Tray Minimized Mode:** Runs discreetly in the Windows Notification Tray with background menu controls (`Open`, `Pause`, `Sync Now`, `Exit`).
* **Silent Windows Boot Auto-Start:** Automatically launches on Windows startup as a background service without opening unwanted console windows.

### 8. 🛡️ 100% Offline & Zero Dependency Architecture
* **Native Single-File Binary:** Self-contained executable with embedded Python runtime, C-extensions, and GUI frameworks.
* **Zero Pre-requisites:** No Python, pip, VC++ redistributables, or internet connection required on client workstations.

---

## 🚀 Installation & Usage

### Method 1: Using the Installer (`.exe`)
1. Download [`AlienZKTecoSync_v2.5_Setup.exe`](https://github.com/sohaghaing0070/AlienZKTecoSync/releases/download/v2.5.0/AlienZKTecoSync_v2.5_Setup.exe).
2. Double-click the file to launch the **Alien Soft Setup Wizard**.
3. Choose your installation folder (default: `C:\AlienSoft_ZKTecoSync`) and click **Install**.
4. Launch the application from your Desktop shortcut or Start Menu.

### Method 2: Using the Portable Package (`.zip`)
1. Download and extract [`AlienZKTecoSync_v2.5_Portable.zip`](https://github.com/sohaghaing0070/AlienZKTecoSync/releases/download/v2.5.0/AlienZKTecoSync_v2.5_Portable.zip).
2. Run `Launch_AlienZKTecoSync.bat` or `AlienZKTecoSync.exe`.

---

## 👨‍💻 Developer & Enterprise Support

* **Developer / Proprietor:** Md Sumon Islam Sohag
* **Company:** Alien Software Development (Dhaka, Bangladesh)
* **WhatsApp:** [+8801710978997](https://wa.me/8801710978997)
* **Website:** [https://aliensoftwaredevelopment.com](https://aliensoftwaredevelopment.com)
* **Official Repository:** [https://github.com/sohaghaing0070/AlienZKTecoSync](https://github.com/sohaghaing0070/AlienZKTecoSync)

---

© 2026 Alien Software Development. All Rights Reserved.
