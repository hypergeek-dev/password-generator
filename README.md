# Cyber-Forge: Advanced Password Generator

![Screenshot of the program](cipher-forge.png)

## Repository
https://github.com/hypergeek-dev/cipher-forge

Live at:
https://cipher-forge.herokuapp.com/

## Introduction
In today's digital age, strong passwords are crucial for safeguarding your sensitive information. Meet Cyber-Forge, an advanced password generator designed to help you create robust passwords that adhere to the best practices of password security.

## How to Use Cyber-Forge
Common Password Validation: Cyber-Forge checks if your password is a commonly known password and suggests changing it if necessary.

Enter a password to test its commonness.
Receive feedback on whether the password is commonly known or not.
Password Generation: If you want a new password suggestion, Cyber-Forge can generate a strong and unique password for you.

Choose whether to generate a new password suggestion.
A strong and unique password will be generated and displayed.
Password Uniqueness: Cyber-Forge calculates the number of possible combinations for the generated password, giving you an idea of its uniqueness.

## Getting Started
Prerequisites
Make sure you have the following installed:

Python (version 3.7 or above)
colorama library (pip install colorama)
humanize library (pip install humanize)
Usage
Clone this repository and navigate to the project directory.

Run the following command to start the password generator:

python password_generator.py
Follow the on-screen instructions to validate your password and generate a new one if desired.

## Project Requirements
This project is the third of five milestone projects that need to be completed to obtain the Full Stack Development Diploma from Code Institute. The required technology for this project is Python.

## Features
Password Validation
Cyber-Forge validates your password against a list of commonly known passwords.

### Enter a password to test its commonness.
Receive feedback on whether the password is commonly known or not.
### Password Generation
Cyber-Forge can generate a strong and unique password for you.

### Choose whether to generate a new password suggestion.
A strong and unique password will be generated and displayed.
Password Uniqueness
Cyber-Forge calculates the number of possible combinations for the generated password, giving you an idea of its uniqueness.

## Technologies Used
Python
colorama library
humanize library
Testing
The code has been tested using PEP8 Online to ensure compliance with Python style guidelines.

## Development and Deployment
The development environment used for this project was GitPod. Regular commits and pushes to GitHub were conducted to track the development stage and handle version control.

The live version of the project was deployed using Heroku.

## Testing
First run through, on CI Python Linter on https://pep8ci.herokuapp.com/ gave following results:

6: E302 expected 2 blank lines, found 1
17: E302 expected 2 blank lines, found 1
43: E501 line too long (100 > 79 characters)
57: E305 expected 2 blank lines after class or function definition, found 1
57: E501 line too long (103 > 79 characters)
58: E501 line too long (106 > 79 characters)
59: E501 line too long (160 > 79 characters)
60: E501 line too long (100 > 79 characters)
67: E501 line too long (105 > 79 characters)
69: E501 line too long (96 > 79 characters)
94: E501 line too long (92 > 79 characters)
100: E501 line too long (136 > 79 characters)

## Credits
For code inspiration, help, and advice, the following resources were used:

Author
Cyber-Forge was developed by Dennis Jensen.
