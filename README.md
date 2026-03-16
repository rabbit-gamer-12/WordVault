# WordVault

WordVault is a Python-based secure dictionary and password manager.

It allows you to store, search, add, and edit different types of information such as:

- dictionary entries
- language translations
- book notes
- useful links
- passwords and codes

Sensitive information is encrypted using the **Fernet encryption system** from the `cryptography` library.

---

# Features

- 🔐 Encrypted password storage
- 🔑 Password-protected access
- 🚨 Failed login detection
- 📧 Email alerts for suspicious activity
- 📚 Editable dictionaries and book pages
- 🔓 Secure lock / unlock system
- 🌍 Language translation dictionary
- ⌨️ OS-specific keyboard shortcut dictionaries

---

# Requirements

- Python **3.10 or newer**
- Internet connection *(only required for email alerts)*
- Python package: `cryptography`

---

# Installation (Windows)

## 1. Install Python

Go to:

https://www.python.org/downloads/

Download Python for Windows.

IMPORTANT: During installation, check:
Add Python to PATH


---

## 2. Download the Program

If using GitHub:

1. Click the green **Code** button
2. Select **Download ZIP**
3. Extract the folder to your computer (Desktop is fine)

---

## 3. Open Windows PowerShell

Press:
Win + R


Type:
powershell


Press **Enter**.

---

## 4. Navigate to the Project Folder

Example:
cd Desktop\WordVault


---

## 5. Install Required Packages

Run:
python -m pip install -r requirements.txt


---
# Installation (macOS)

## 1. Install Python

macOS sometimes already includes Python, but it may be outdated.

Check your version by opening **Terminal** and running:
python3 --version


If Python is not installed or the version is older than 3.10, download the latest version from:

https://www.python.org/downloads/

Install the macOS version.

---

## 2. Download the Program

If using GitHub:

1. Click the green **Code** button
2. Select **Download ZIP**
3. Extract the folder to your computer (Desktop is fine)

---

## 3. Open Terminal

Press:
Command + Space


Search for:
Terminal


Then press **Enter**.

---

## 4. Navigate to the Project Folder

Example:
cd Desktop/WordVault


---

## 5. Install Required Packages

Run:
python3 -m pip install -r requirements.txt


---

# Running the Program (macOS)

Run the program with:
python3 main.py


(Replace `main.py` if the main file has a different name.)
# Running the Program

Run the program with:
python main.py


(Replace `main.py` if the main file has a different name.)

---

# Security Notes

⚠️ **Do NOT upload these files publicly:**
secret.key
codes_passwords.enc


These files contain encrypted or sensitive information.

If you upload this project to GitHub:

Add these to your `.gitignore` file:
secret.key
*.enc


You should only upload **empty example data files**.

---

# Cross Platform Support

The program supports:

- Windows
- macOS

Some keyboard shortcuts may vary depending on the operating system.

---

# Author

Created by

**Reilly Martin**
