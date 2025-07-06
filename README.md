# SCT_CS_4
Basic Keylogger for Educational Purposes

Overview

This project is a simple Python keylogger developed as part of an internship task in the education field. It demonstrates the use of the pynput library to capture and log keystrokes to a file (keylog.txt) with timestamps. The program is designed for learning purposes, showcasing event handling, file I/O, and ethical considerations in software development.

Note: This keylogger is intended for educational use only. Always obtain explicit user consent and adhere to ethical guidelines when working with keylogging software.

Features





Logs keystrokes with timestamps in the format YYYY-MM-DD HH:MM:SS.



Handles special keys (e.g., Space, Enter, Tab, Backspace) with clear labels.



Stops logging when the Esc key is pressed.



Writes logs to keylog.txt in the project directory.



Includes error handling to prevent crashes during logging.

Prerequisites





Python 3.x



pynput library (pip install pynput)

Installation





Clone this repository:

git clone https://github.com/your-username/keylogger.git



Navigate to the project directory:

cd keylogger



Install the required library:

pip install pynქ

Usage





Run the script:

python keylogger.py



Press keys to log them. Special keys are labeled (e.g., "SPACE", "ENTER").



Press Esc to stop the program.



Check keylog.txt for the logged keystrokes.

Example Output

--- Keylog started at 2025-07-06 22:30:23 ---
[2025-07-06 22:30:24] h
[2025-07-06 22:30:24] e
[2025-07-06 22:30:25] l
[2025-07-06 22:30:25] l
[2025-07-06 22:30:25] o
[2025-07-06 22:30:26] SPACE
[2025-07-06 22:30:27] ESC

Ethical Considerations





This project is for educational purposes only.



Keyloggers can be misused, so always ensure explicit user consent and comply with legal and ethical standards.



Do not use this software to capture keystrokes without permission.

License

This project is licensed under the MIT License. See the LICENSE file for details.

Acknowledgments





Built using the pynput library for keyboard input handling.



Developed as part of an internship task to explore event-driven programming and file handling in Python.
