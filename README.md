# SpeedTypingTest
A console-based speed typing test application built using the Python curses library. The program measures the user's typing speed in words per minute (WPM) by having them type out a randomly selected text.

Features

Displays a welcome screen with instructions.
Randomly selects a line of text from a file for the typing test.
Measures typing speed in words per minute (WPM).
Highlights correct and incorrect characters as the user types.
Ends the test once the user completes typing the target text.
Allows the user to exit the program by pressing the Escape key.
Installation

Clone the repository:

bash
Copy code
git clone https://github.com/yourusername/speed-typing-test.git
cd speed-typing-test
Ensure you have Python installed (version 3.6 or higher).

(Optional) Create and activate a virtual environment:

bash
Copy code
python3 -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
Install the required dependencies:

bash
Copy code
pip install -r requirements.txt
Usage

Create a text.txt file in the same directory as the program. This file should contain multiple lines of text that will be used for the typing tests.

Run the program:

bash
Copy code
python typing_test.py
Follow the on-screen instructions to start the typing test. Your WPM will be displayed as you type. The test will end once you complete typing the target text.

Example text.txt

plaintext
Copy code
The quick brown fox jumps over the lazy dog.
A journey of a thousand miles begins with a single step.
To be, or not to be, that is the question.
All that glitters is not gold.
Code Structure

typing_test.py: The main program file containing all the logic for the typing test.
requirements.txt: The file for listing dependencies (if any).
Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your changes.

License

This project is licensed under the MIT License. See the LICENSE file for details.
