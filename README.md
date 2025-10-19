# n8n Gmail Spam Cleaner

This repository contains an **n8n workflow** to automatically clean your Gmail Spam folder.

## ✨ Features
- Runs on a schedule (daily).
- Fetches all emails in the **Spam** folder.
- Deletes emails older than 7 (or 14) days.

## 🚀 Usage
1. Download the JSON file.
2. Import it into your [n8n](https://n8n.io) instance.
3. Update the Gmail OAuth2 credentials in the workflow.
4. Adjust the number of days in the **Filter old spams** node if needed.

## ⚠️ Warning
This workflow **permanently deletes** emails from the Spam folder after X days.  
Make sure to test before activating it in production.
