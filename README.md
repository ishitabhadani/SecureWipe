# 🛡️ SecureWipe

A lightweight collection of Linux shell scripts designed to **securely wipe storage devices** by overwriting data to prevent recovery.

> ⚠️ **WARNING:** This tool is destructive. Once executed, data cannot be recovered.

---

## 📌 Overview

SecureWipe provides multiple scripts to securely erase data from storage devices on Linux systems. Each script targets a specific device (e.g., `/dev/sdX`) and performs overwrite operations to ensure data is irrecoverable.

### Features

- Simple and minimal setup  
- Designed for Linux environments  
- Script-based approach for flexibility  
- Intended for secure disk sanitization  

---

## ⚠️ Important Warning

- Running these scripts **will permanently destroy all data** on the selected drive.  
- Root (`sudo`) access is required.  
- Ensure you are targeting the **correct device** before execution.  
- If a partition exists, the script will overwrite data within that partition space.  

---

## 🚀 Getting Started
1. Clone the Repository
git clone https://github.com/ishitabhadani/SecureWipe.git
cd SecureWipe
2. Make Scripts Executable
find . -name "securesd*" -exec chmod +x {} \;
3. Run the Script
sudo ./securesdX

Replace X with the target drive letter (e.g., a, b, c).
