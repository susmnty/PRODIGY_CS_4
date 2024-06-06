# PRODIGY_CS_4
Simple Keylogger

This Python Simple keylogger program records every key pressed on the keyboard and saves them to a file named 'keylog.txt.' using the pynput library, it monitors and logs keystrokes. The program first imports the necessary classes from 'pynput'. It specifies 'keylog.txt' as the log file to store the keystrokes. The 'on_press' function handles key press events, opening 'keylog.txt' in append mode to add new keystrokes. It writes the character of each key pressed to the file, handling special keys like space, enter, and tab by writing appropriate representations. Other special keys are logged in square brackets. An optional 'on_release' function stops the keylogger when the escape key is pressed. The listener is set up to call on_press for key presses and 'on_release' for key releases, and it runs until stopped. To use the program, save the code to a file (e.g - keylogger.py) & run it with Python. The program will log keystrokes to keylog.txt until stopped. Ethical use is crucial: only run the program on computers where you have explicit permission. Inform users that their keystrokes are being logged and ensure the log file is kept secure. This tool is meant for educational purposes, such as learning about keylogging or monitoring your own computer use. Always use it responsibly and legally.

Instruction to use the code - 

1. Run the pip install first so that it collects its files.
2. Then Run the main code.

Notice - You can use Jupyter Notebook for better clear results. 
