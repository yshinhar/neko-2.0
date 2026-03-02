# 🐱 neko

**neko** is a small, always-on-top desktop window assistant written in **Python**.
It’s a lightweight container for **standalone power tools** like automation launchers, clipboard history, calculator and quick utilities — all inside a single floating window.

The goal: **maximum usefulness, minimum space**.

---

## ✨ Core Features

### ⚙️ Automation (Main Feature)

Turn neko into a **one-click automation hub** for your desktop.

* Run scripts or system commands
* Bind actions to buttons or hotkeys
* Chain actions with delays
* Launch files, folders, and URLs
* Trigger repetitive setup tasks instantly

Perfect for:

* Opening workspaces
* Running helper scripts
* Repetitive desktop workflows
* “I do this every day, why am I still clicking?” tasks

---

### 📋 Clipboard Manager

A simple, no-nonsense clipboard tool built directly into neko.

* Read current clipboard content
* Clipboard history
* Re-copy previous entries with one click
* Optional persistence between sessions

Useful when you want clipboard history **without running a heavy background app**.

---

## 🪟 UI Behavior

* Always-on-top floating window
* Expand / collapse the UI (`Ctrl + P`)
* Multiple tool modes inside a single window
* Compact, fast, and unobtrusive

---

## 💡 Use Cases

* Keep a clipboard history without installing a full clipboard manager
* Launch scripts or commands instantly
* Trigger repetitive actions from one place
* Replace multiple tiny helper apps with one compact window
* Build your own tools inside neko as you need them

---

## 📸 Example Workflows

### Automation

* Bind a button to open a project folder
* Run a Python script with one click
* Execute a startup sequence with delays
* Open multiple apps in order

### Clipboard

* Copy text or code
* Open neko to view clipboard history
* Click an entry to copy it again

---

## 📦 Requirements

* **Python 3.9+**
* **Windows**

Python packages:

* `keyboard`
* `psutil`
* `pygame`
* `pyperclip`

> Tkinter is included with most Python installations on Windows.

---

## 🚀 Installation

```bash
git clone https://github.com/YOUR_USERNAME/neko.git
cd neko
pip install keyboard psutil pygame pyperclip
```

Run the app:

```bash
python neko.pyw
```

> The `.pyw` extension runs neko without opening a console window.

---

## 🗂 Project Structure

```
neko.pyw        # Main application entry point
/               # Internal modules for UI, clipboard, and automation
```

---

## 🧪 Philosophy

neko is:

* Small
* Always available
* Easy to extend
* Focused on real desktop productivity

If it feels like a **floating toolbox you slowly customize over time**, it’s working.

---

If you want next steps, I can:

* Add **badges** (Python version, platform, license)
* Rewrite this in a more **chaotic hacker tone**
* Help you design a **plugin / module system**
* Make a short **“Why neko exists”** section

Just say the word 😼
