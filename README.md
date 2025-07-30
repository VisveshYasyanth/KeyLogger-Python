# ⌨️ KeyLogger-Lite

A simple Python-based tool that records and logs keystrokes for **educational purposes**. Developed as part of my internship to understand basic event listening and logging in Python.

---

## 🎯 Features

> 🖥️ Cross-Platform • ⌨️ Keystroke Logging • 🧠 Beginner-Friendly

* Records every key pressed in real-time
* Saves all keystrokes to a log file (`key_log.txt`)
* Lightweight and simple Python implementation
* Works on **Windows, macOS, and Linux**
* Educational and safe for personal testing

---

## 🛠 Tech Stack

* Python 3
* `pynput` (Keyboard Listener Library)

---

## 🧠 How It Works

### ⌨️ Key Logging:

* The program listens for every key press using `pynput`.
* Each key is appended to a file named `key_log.txt`.
* The program continues running until manually stopped (Ctrl + C).

---

## 🚀 How to Run

1. Ensure Python is installed:

   ```bash
   python --version
   ```

2. Install the required dependencies:

   ```bash
   pip install pynput
   ```

3. Run the program:

   ```bash
   python keylogger.py
   ```

4. All logged keystrokes will be saved in `key_log.txt`.

---

## 🛡️ Disclaimer

This tool is strictly for **educational and personal testing purposes only**.
Running it on devices without permission is **illegal** and may violate computer misuse laws.
