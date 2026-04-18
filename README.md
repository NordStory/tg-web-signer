# Telegram Auto Signature

A browser extension that automatically appends a custom signature to every message in Telegram Web (Version A). 

This tool is designed for shared team accounts where multiple members operate under a single profile (e.g., support teams, DevOps groups) and need to identify who is sending each message.

## 🚀 Key Features

- **Automated Workflow**: Adds your signature instantly as you type.
- **Smart Insertion**: Uses `MutationObserver` to detect the input field without interfering with the message content.
- **Cursor Stability**: Automatically restores cursor position after adding the signature to ensure a seamless typing experience.
- **Customizable**: Change your signature on the fly via the extension popup.

## 🛠 Use Cases

* **Team Collaboration**: Essential for shared accounts (Support, Sales, DevOps) to track message authorship.
* **Personal Branding**: Automatically add your name or title in corporate environments.
* **Contextual Clarity**: Helps avoid confusion in fast-paced group discussions.

## 📦 Installation

Since this is a developer version, follow these steps to install:

1.  **Download** the repository as a ZIP or clone it to your local machine.
2.  Open **Google Chrome** or **Microsoft Edge**.
3.  Go to `Settings` → `Extensions` → `Manage Extensions` (or enter `chrome://extensions/` in the address bar).
4.  Enable **Developer Mode** (toggle in the top-right corner).
5.  Click **"Load unpacked"** and select the folder containing the extension files.
6.  The extension is now active and will run automatically on Telegram Web.

## 📖 How to Use

> **Note**: This extension currently supports **Telegram Web Version A** only.

1.  Navigate to **[https://web.telegram.org/a](https://web.telegram.org/a)**.
2.  **Set your signature**: Click the extension icon in your browser toolbar, type your desired signature in the popup, and hit "Save".
3.  **Start typing**: As you interact with the message input field, your signature will be appended automatically.
4.  Send your message!

## ⚙️ Technical Details

- **Engine**: JavaScript (Vanilla).
- **DOM Monitoring**: Utilizes `MutationObserver` for high performance and low resource consumption.
- **State Management**: Uses `chrome.storage` to persist your signature across sessions.

## ⚠️ Known Limitations

- Compatible only with **Version A** of Telegram Web.
- Changes in Telegram's internal DOM structure may require extension updates.

## 📄 License

This project is licensed under the **MIT License**. Feel free to use, modify, and distribute!
