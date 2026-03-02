neko

neko is a small always-on-top desktop window assistant written in Python.
It acts as a container for simple standalone tools like a clipboard manager, automation launcher and calculator.

The focus is on being lightweight, jam packed with utility and easy to extend.

Features

Always-on-top floating window

Expand / collapse UI (ctrl+p)

Multiple tool modes inside one window

Clipboard

Read current clipboard content

Clipboard history

Re-copy previous entries

Optional persistence

Automation

Run scripts or system commands

Keyboard shortcuts

Simple delays and sequences

Useful for repetitive desktop tasks

Utilities

Open files and folders

Open URLs

Keyboard input hooks

Basic system information

Optional sound feedback

Basic Use Cases

Keep a clipboard history without running a heavy background app

Launch small scripts or commands quickly

Trigger repetitive actions from one place

Use a compact helper window instead of multiple separate tools

Examples
Clipboard

Copy text or code

Open neko and see clipboard history

Click an entry to copy it again

Automation

Bind a button to open a folder

Run a Python script with one click

Trigger a sequence with delays (for setup tasks)

Requirements

Python 3.9+

Windows

Installation
Clone the repository
git clone https://github.com/YOUR_USERNAME/neko.git
cd neko
Install dependencies
pip install keyboard psutil pygame pyperclip

Tkinter is included with most Python installations on Windows.

Running
python neko.pyw

The .pyw extension runs the app without opening a console window.

Project Structure

neko.pyw — main application

Internal modules handle UI, clipboard, and automation logic
