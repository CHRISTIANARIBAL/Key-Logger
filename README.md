Simple Keylogger - Python
This is a simple keylogger script written in Python that records every key you press on your keyboard and logs them into a file called keylog.txt. It is for educational purposes only. Please use it responsibly and only on your own systems or in authorized ethical hacking labs.

Features
Captures every key pressed.

Logs the keys into a file called keylog.txt.

It logs both printable characters and special keys (e.g., Shift, Enter).

Requirements
To run this keylogger, you'll need to install the pynput Python library, which allows us to monitor the keyboard.

Install pynput:

pip install pynput

Usage:
Clone or download the script to your local machine.

git clone https://github.com/CHRISTIANARIBAL/Key-Logger.git

Open the command line or terminal and navigate to the directory where the script is saved.

Run the script with:

python keylogger.py

The script will start capturing your keyboard input and logging each key press to the keylog.txt file.

To stop the keylogger, you can press Ctrl + C in the terminal.

How It Works
The keylogger uses the pynput library to listen to keyboard events.

It records each key press and appends it to the file keylog.txt.

Non-printable keys (like Shift or Enter) are logged as their string representation, so the logger knows if special keys were pressed.


keylogger.py     # Python script that runs the keylogger
keylog.txt       # The file where the keystrokes are logged
README.md        # This is README file

Disclaimer
This script is intended for educational purposes only. Unauthorized use of a keylogger to monitor someone's keystrokes without their knowledge is illegal and unethical.

Always use this script responsibly and only on machines you own or have explicit permission to monitor.

Misuse of this script could lead to criminal charges, including violations of privacy and cybercrime laws.
