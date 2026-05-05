# Password Generator

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Project Type](https://img.shields.io/badge/Type-CLI%20Tool-green)
![License](https://img.shields.io/badge/License-MIT-yellow)

A Python-based command-line tool that generates strong and memorable passwords using user-provided words combined with secure randomness.

---

## Disclaimer

This tool is developed strictly for educational and awareness purposes only.

It is designed to help users create strong passwords for their own use. This tool must not be used for any unauthorized or illegal activities.

By using this tool, you agree that:

- You will use it only for learning and personal security purposes  
- You will not engage in any unauthorized or illegal activities  
- You understand that misuse may lead to legal consequences  

The author shall not be held responsible for any misuse or damage caused by this tool.

---

## Introduction

Password Generator is a simple yet practical CLI tool that helps users generate secure and easy-to-remember passwords.

Instead of completely random passwords, this tool allows users to input two favorite words. These words are then modified and combined with random digits and symbols to create a strong password.

---

## Features

- Generates strong and memorable passwords  
- Uses user-provided words for better recall  
- Applies character substitutions (e.g., a → @, e → 3)  
- Adds random digits and special characters  
- Recommends secure password length (12+ characters)  
- Interactive command-line interface  
- Uses Python’s `secrets` module for better security  

---

## Prerequisites

- Python 3

Check your version:

```bash
python --version
```

---

## Installation

```bash
git clone https://github.com/your-username/password-generator.git
cd password-generator
```

---

## Usage

```bash
python password_generator.py
```

---

## Example Output

```
Hello, Welcome to Password Generator

Recommended: 12+ characters for strong security

Enter the length of the password: 14

Enter your first favorite word: apple
Enter your second favorite word: sky

Generated Password: @ppl3sky#92!
```

---

## Important Note

- This tool does not store or transmit any data  
- All processing is done locally  
- Avoid using real or sensitive passwords while testing  

---

## Future Enhancements

- Password strength checker integration  
- Option to include/exclude symbols  
- Uppercase/lowercase randomization  
- GUI or web-based version  

---

## Author

Tanishka Gupta


Secure Today. Safe Tomorrow.