# password-generator







This Python program creates a simple password generator using the Tkinter library for the GUI. It allows users to specify the desired password length (between 8 and 32 characters) using a Spinbox widget. Upon clicking the "GENERATE PASSWORD" button, the program generates a random password consisting of uppercase letters, lowercase letters, digits, and punctuation. To ensure security, the code includes at least one character from each type if the length is 4 or greater. The generated password is displayed in a text field and can be copied to the clipboard using the "COPY TO CLIPBOARD" button with the help of the `pyperclip` module.
