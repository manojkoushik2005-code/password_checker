# 🔐 Password Strength Checker

A Python-based command-line application that evaluates password strength using regular expressions and standard security criteria. The tool analyzes passwords against multiple requirements and provides actionable feedback to help users create stronger, more secure passwords.

## Overview

Strong passwords are a critical component of cybersecurity. This project demonstrates how Python and regular expressions can be used to assess password quality by checking for common security requirements.

The Password Strength Checker evaluates a password based on:

* Minimum length requirements
* Presence of uppercase letters
* Presence of lowercase letters
* Presence of numeric digits
* Presence of special characters

Based on the evaluation, the password is classified as:

* **Strong**
* **Moderate**
* **Weak**

The application also provides detailed suggestions for improving password security when requirements are not met.

## Features

✅ Password length validation (minimum 8 characters)

✅ Uppercase letter detection

✅ Lowercase letter detection

✅ Numeric digit detection

✅ Special character validation

✅ Password strength classification

✅ User-friendly feedback and improvement suggestions

✅ Lightweight and easy-to-understand code structure

## Technologies Used

* Python 3
* Regular Expressions (`re` module)

## Project Structure

```text
password_checker/
│
├── password_checker.py
├── README.md
├── LICENSE
└── .gitignore
```

## Installation

### Clone the Repository

```bash
git clone https://github.com/your-username/password_checker.git
cd password_checker
```

### Requirements

Ensure Python 3 is installed on your system.

Check your Python version:

```bash
python --version
```

or

```bash
python3 --version
```

## Usage

Run the application:

```bash
python password_checker.py
```

### Example 1

Input:

```text
Password123
```

Output:

```text
Password Strength: Moderate

Suggestions to improve:
Password should contain at least one special character (!@#$...).
```

### Example 2

Input:

```text
P@ssword123
```

Output:

```text
Password Strength: Strong
```

## Password Evaluation Criteria

| Requirement       | Description                          |
| ----------------- | ------------------------------------ |
| Length            | At least 8 characters                |
| Uppercase Letter  | At least one A–Z character           |
| Lowercase Letter  | At least one a–z character           |
| Number            | At least one digit (0–9)             |
| Special Character | At least one symbol such as !@#$%^&* |

### Strength Levels

| Score | Rating   |
| ----- | -------- |
| 5/5   | Strong   |
| 3–4/5 | Moderate |
| 0–2/5 | Weak     |

## Learning Objectives

This project is suitable for beginners who want to learn:

* Python functions
* Conditional statements
* User input handling
* Regular expressions
* String validation
* Basic cybersecurity concepts
* Command-line application development

## Future Enhancements

Potential improvements include:

* Password entropy calculation
* Detection of common passwords
* Dictionary-word checks
* Minimum length of 12+ characters
* Graphical User Interface (GUI)
* Password generation feature
* Integration with password breach databases
* Real-time password strength meter

## Security Note

This tool is intended for educational and learning purposes. While it helps identify common password weaknesses, it should not be considered a complete security auditing solution.

## Contributing

Contributions are welcome.

If you would like to improve this project:

1. Fork the repository
2. Create a new branch
3. Make your changes
4. Commit your updates
5. Open a Pull Request

## License

This project is licensed under the MIT License. See the LICENSE file for more information.

## Author

Developed using Python as a demonstration of password validation and security best practices.
