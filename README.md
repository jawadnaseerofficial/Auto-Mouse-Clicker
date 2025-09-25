#🖱️ Auto Mouse Clicker 
An easy-to-use AutoClicker built with Python, Tkinter, and pynput.
It allows you to automate mouse clicks with customizable settings, hotkeys, and a simple GUI.

#✨ Features

🔘 Choose Click Type – Single or Double click.

⏱️ Custom Delay – Set time between clicks (default: 0.1s).

♾️ Infinite or Limited Clicks – Run forever or stop after a set number of clicks.

🎛️ Simple Tkinter GUI – User-friendly controls.

⌨️ Hotkeys Support

F6 → Start/Stop clicking

F7 → Pause/Resume

ESC → Exit program

#🚀 Installation

Clone this repo:

Create a virtual environment (optional but recommended):

python -m venv .venv
source .venv/bin/activate   # On Linux/Mac
.venv\Scripts\activate      # On Windows


Install dependencies:

pip install -r requirements.txt

#🖥️ Usage

Run the script:

python autoclicker.py


Set delay (time between clicks).

Choose click type (single or double).

Choose number of clicks (-1 = infinite).

Use GUI buttons or hotkeys to control clicking.

#📦 Requirements

Python 3.8+

Tkinter (comes with Python)

pynput

Install missing packages manually:

pip install pynput
