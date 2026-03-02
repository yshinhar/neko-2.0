# neko
## the cutest window assistant

```
╱|
(˚˕ 。7
|、˜〵
じしˍ,)ノ
```

**neko** is a small, always-on-top desktop window assistant written in **Python**.  
It’s a lightweight container for **standalone power tools** like automation launchers, clipboard history, calculator, and quick utilities — all inside a single floating window.

The goal: **maximum usefulness, minimum space**.

---

## ✨ Core Features

### ⚙️ Automation (Main Feature)

```
╱|    
(`ˎ - 7
|、˜〵
じしˍ,)ノ
```

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

```
     |╲
 < 。˕˚)
  / ˜  |
ヽ(,ˍりり
```

A simple, no-nonsense clipboard tool built directly into neko.

* Read current clipboard content
* Clipboard history
* Re-copy previous entries with one click
* Optional persistence between sessions

Useful when you want clipboard history **without running a heavy background app**.

---

### 🧮 Calculator

```
╱|    
(`˕ 。7
|、˜〵
じしˍ,)ノ
```

A quick calculator right inside neko:

* Instant calculations
* No extra windows
* Conversion mode
* Always accessible

---

## 🪟 Non-Distracting / Friendly Behavior

```
     zZ
╱|    
(-ㅅ- 7
(ˍ,     ˜ˍ,)ノ
```

neko is **designed to stay out of your way** while still being alive and interactive:

* Becomes **semi-transparent** when idle  
* Can be **hidden / shown** with **`Ctrl + P`**  
* **Small and unobtrusive** — never blocks your work  
* Moves to your **mouse when you shake it quickly**  
* Can be **dragged anywhere on the screen**  
* **Bounces off window edges and borders** for a playful feel  
* Idle animations keep him alive, blinking and shifting slightly

> Neko is noticeable only when you want him to be, making him cute without annoying.

---

## 🎨 UI & Liveliness

```
╱|    
(`˕ 。7
|、˜〵
じしˍ,)ノ
```

The UI emphasizes **minimalism and charm**:

* **Minimalist layout** with only the essential controls  
* **Black, gray, and white color palette** — clean and modern  
* Loads of **cute expressions** — idle, looking, pressed, sleepy  
* **Liveliness** — jumps, looks at the mouse, reacts to movement  
* Animations make neko feel like a **tiny creature on your desktop**  

> A small, cute, and responsive assistant that adds personality without clutter.

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

```
╱|    
(˚˕ 。7
|、˜〵
じしˍ,)ノ
```

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
neko.pyw            # Main application entry point
neko_utils/         # Internal modules for UI, clipboard, calculator, automation
```

---
