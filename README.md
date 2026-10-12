# 🔐 Password Security Analyzer

A Python-based password security analyzer that evaluates password strength, identifies security weaknesses, and provides recommendations to improve password security.

This project was developed to practice **Object-Oriented Programming (OOP)** concepts while applying basic cybersecurity principles.

---

## 📌 Overview

Password security is an important part of cybersecurity. Weak passwords are one of the most common causes of security breaches.

This tool analyzes a password based on multiple security factors and provides:

- A security score
- Password strength level
- Identified weaknesses
- Suggestions for improvement

---

## 🚀 Features

### 🔍 Password Analysis

The analyzer checks:

- Password length
- Lowercase letters
- Uppercase letters
- Numbers
- Special characters
- Common passwords
- Repeated character patterns


### 📊 Password Strength Classification

Passwords are classified into:

| Score | Strength |
|---|---|
| 0 - 2 | Very Weak |
| 3 - 4 | Weak |
| 5 - 6 | Medium |
| 7 - 8 | Strong |
| 9 | Very Strong |


### ⚠️ Weakness Detection

The program can detect:

- Passwords that are too short
- Missing lowercase letters
- Missing uppercase letters
- Missing numbers
- Missing special characters
- Commonly used passwords
- Repeated character patterns


### 💡 Security Suggestions

The analyzer provides recommendations such as:

- Adding uppercase letters
- Adding numbers
- Adding special characters
- Avoiding common passwords
- Increasing password length

---

## 🛠️ Technologies Used

- Python 3
- Object-Oriented Programming (OOP)
- Lists
- Loops
- Conditional Statements

---

## 📂 Project Structure


password-security-analyzer/
│
├── main.py
└── README.md

---

## ▶️ How to Run

### Clone the repository

```bash
git clone https://github.com/your-username/password-security-analyzer.git

Navigate to the project directory
cd password-security-analyzer

Run the program
python3 main.py

```

## 💻 Example Output

```
Enter a password: 123456

Password Security Report
------------------------
Score: 2 /9
Strength: Very Weak

Weaknesses:
- Password is too short
- Missing lowercase letter
- Missing uppercase letter
- Missing special character
- Common Password Found

Suggestions:
+ Use at least 8 characters
+ Add lowercase letters
+ Add uppercase letters
+ Add special characters
+ Avoid using common passwords

```
## 🧠 Concepts Practiced
This project helped practice:
- Classes and Objects
- Constructors
- Encapsulation
- Object interaction
- Code organization
- Input validation
- Debugging
- Testing
## 🔒 Security Checks
| Security Check | Description |
|---|---|
| Length Check | Ensures password has minimum characters |
| Lowercase Check | Detects lowercase letters |
| Uppercase Check | Detects uppercase letters |
| Number Check | Detects numerical digits |
| Special Character Check | Detects special symbols |
| Common Password Check | Detects commonly used passwords |
| Pattern Check | Detects repeated characters |


## 🧪 Testing
The application was tested with different password types:
| Password Example | Result |
|---|---|
| `123456` | Very Weak |
| `aaa123` | Weak |
| `hello123` | Medium |
| `Abcd1234` | Strong |
| `Abcd1234!Xyz` | Very Strong |

## 🔮 Future Improvements
Possible future improvements:
- Add password entropy calculation
- Add stronger password database
- Add password generator
- Add graphical user interface (GUI)
- Add unit testing
- Add configuration support
- Improve password analysis algorithms


## 👨‍💻 Author
Niketh
