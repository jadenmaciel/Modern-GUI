# Modern GUI Login System

This project provides a modern and user-friendly graphical user interface (GUI) for a simple login system. Built with the `customtkinter` library in Python, it offers a sleek, dark-themed interface with standard login functionalities.

## Problem Statement/Motivation

Many basic login interfaces can appear outdated or lack visual appeal. This project aims to demonstrate how to create a more engaging and modern-looking login form using the `customtkinter` library, enhancing the user experience for simple authentication tasks.

## Features Implemented

* **Clean and Modern UI:** Utilizes the `customtkinter` library for a visually appealing dark-themed interface.
* **Username and Password Fields:** Standard input fields for users to enter their credentials.
* **Password Masking:** The password field obscures the input for security.
* **Login Button:** Triggers the login functionality (currently prints "Test" to the console).
* **"Remember Me" Checkbox:** Provides an option for users to have their login information remembered (functionality not fully implemented in this version).

## Technologies Used

* **Python:** The primary programming language.
* **Customtkinter:** A Python UI library based on Tkinter, providing modern widgets and themes.

## Setup and Installation Instructions

1.  **Install Python:** Ensure you have Python 3.6 or higher installed on your system. You can download it from [python.org](https://www.python.org/).
2.  **Install `customtkinter`:** Open your terminal or command prompt and run the following command:
    ```bash
    pip install customtkinter
    ```
3.  **Save the Code:** Save the provided Python code as a `.py` file (e.g., `login_gui.py`).
4.  **Run the Application:** Navigate to the directory where you saved the file in your terminal or command prompt and run:
    ```bash
    python login_gui.py
    ```
    This will launch the login window.

## Usage/Examples

Upon running the script, you will see a login window with the title "Login System".

1.  Enter your desired username in the "Username" field.
2.  Enter your password in the "Password" field (the characters will be hidden).
3.  Click the "Login" button. Currently, this will print "Test" to your console.
4.  You can also check or uncheck the "Remember Me" checkbox.

## Live Demo Link

N/A (This is a local GUI application and not deployed online.)

## Challenges & Learnings

One challenge encountered was understanding the layout management within `customtkinter` to ensure the elements were positioned correctly and scaled appropriately within the window. Learning to use the `pack()` geometry manager with `pady`, `padx`, `fill`, and `expand` was key to achieving the desired layout. Additionally, exploring the different widget options and customization possibilities offered by `customtkinter` broadened the understanding of modern GUI development in Python.