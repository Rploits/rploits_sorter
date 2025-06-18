# 🧪 Rploits Sorter v1.0

**Author:** Rossumploits (aka Rploits)  
**Purpose:** Identify email provider, MX records, and domain info from email lists.  
**Version:** CLI-based executable for Windows (.exe only)  
**License:** For educational and internal research use only.

---

## 🔧 Features

- Detects major email providers (e.g., Gmail, Outlook, Zoho, GoDaddy, etc.)
- Uses MX + SPF + DMARC lookups
- Identifies country of mail servers (USA, Canada prioritized)
- Outputs results to a neatly formatted `.txt` file
- Automatically names output files to prevent overwrites
- Runs **without needing to install Python or dependencies**

---

## 🖥️ How to Use

### ✅ Step 1: Download
1. Click on `rploits_sorter.exe` in the repo.
2. Press the **Download** button.

### ✅ Step 2: Prepare Your Email List
- Create a simple `.txt` file with **one email address per line**.
- Example:
sales@company.com
info@anotherdomain.org
hello@gmail.com


### ✅ Step 3: Run the Tool
1. Double-click `rploits_sorter.exe`.
2. It will prompt:
📥 Enter path to your .txt email list:
3. Paste your email list file path (e.g., `emails.txt`) and press Enter.
4. A `.txt` results file will be created in the same folder.
5. You’ll be asked if you want to run another scan.

---

## 🗃️ Output Example

Email Domain Provider MX Records
john.doe@gmail.com gmail.com Google alt1.gmail-smtp-in.l.google.com.
ceo@customcorp.ca customcorp.ca Microsoft mail.protection.outlook.com.

---

## 🛠 Notes

- No installation needed.
- Windows 10+ required.
- If the window closes immediately, run via **Command Prompt** (`cmd.exe`).

---

## 🔐 Source Code Access

The source code is private. Only `.exe` is shared for ease of use.

---

## 💬 Contact

Want to collaborate or report a bug?

📧 Telegram: `@rossumploits`  
🔗 GitHub: [https://github.com/Rploits](https://github.com/Rploits)

---

## ⚠️ Disclaimer

This tool is for **educational and authorized use only**. Do not use for illegal or unethical activities.
