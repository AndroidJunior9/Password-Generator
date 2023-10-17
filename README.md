# Password Generator

This is a simple password generator built with Python and Tkinter. It allows you to generate a random password of a given length.

## Features
- Generate a random password of a given length.
- The generated password includes ASCII letters, digits, and punctuation.
- The application has a simple and user-friendly interface.

## How to Use
1. Run the script.
2. Enter the desired length of the password in the input field.
3. Click on the 'Generate Password' button.
4. The generated password will be displayed on the screen.

## Code Explanation
The script uses the `random` and `string` modules to generate a random password. The `tkinter` module is used to create the graphical user interface.

The `generate_password(length)` function generates a random password of the given length. It checks if the length is a digit and then generates a password using ASCII letters, digits, and punctuation.

The `validate_length(text)` function validates that the text is a positive integer. If the text is empty, it returns True. If the text is a digit, it checks if it's greater than 0.

The `invalid_length()` function displays an error message if the text is not a positive integer.

The script then creates a window using Tkinter, adds labels, an entry field, and a button to the window. The entry field is validated using the `validate_length(text)` function. When the button is clicked, it calls the `generate_password(length)` function with the text from the entry field as an argument.

## Requirements
- Python 3.x
- Tkinter module

## Demo

https://github.com/AndroidJunior9/Password-Generator/assets/111723283/2875a751-4819-4478-ab9a-81d99d8c2366

