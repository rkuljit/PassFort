PassFort Documentation 🔐

Overview

PassFort is a Python-based tool designed to test and enhance password security. It evaluates passwords against essential security criteria and provides real-time feedback, empowering users to create stronger and more resilient passwords.

Table of Contents

Features

Installation

Usage

Password Strength Criteria

Example Output

Future Enhancements

Contributing

License

Features

Strength Evaluation: Checks for lowercase, uppercase, digits, special characters, and length.

Real-Time Feedback: Instant feedback on password strength.

Simple CLI Interface: Lightweight and easy to run locally.

Installation

Clone the repository:

git clone https://github.com/yourusername/PassFort.git
cd PassFort

Set up a virtual environment (optional but recommended):

python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate

Run the script:

python src/main.py

Usage

Run the Python script.

Enter a password when prompted.

View the strength score and improvement suggestions.

Password Strength Criteria

PassFort evaluates passwords against five criteria:

Lowercase Letters: At least one lowercase character.

Uppercase Letters: At least one uppercase character.

Digits: At least one number.

Special Characters: At least one special symbol (e.g., @, $, !).

Minimum Length: At least 8 characters.

Example Output

Enter your password: P@ssw0rd

Password Strength: 5/5
Strong password! ✅

Enter your password: hello123

Password Strength: 2/5
Weak password. Consider adding uppercase letters, special characters, and increasing the length. 🔐

Future Enhancements

GUI Version: Add a graphical user interface with Tkinter.

Breach Check: Integrate with Have I Been Pwned API to check for compromised passwords.

Custom Policies: Allow users to define custom password policies.

Web App Integration: Build a web version with Flask or Django.

Contributing

Contributions are welcome! If you'd like to improve PassFort, please fork the repository, make your changes, and submit a pull request.

Fork the project.

Create a feature branch (git checkout -b feature-name).

Commit your changes (git commit -m 'Add feature').

Push to your branch (git push origin feature-name).

Open a pull request.

