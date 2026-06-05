# Password Generator

## Overview

This Password Generator is a simple web application built using HTML, CSS, and JavaScript. It allows users to generate secure and random passwords according to their preferences, including password length and character types such as uppercase letters, lowercase letters, numbers, and symbols. The generated password can be copied to the clipboard with a single click, making it convenient for immediate use.

---

## Features

### Customizable Password Length

Users can specify the length of the generated password using an interactive slider.

### Selectable Character Types

Users can choose which character types to include in the password:

* Uppercase Letters (A-Z)
* Lowercase Letters (a-z)
* Numbers (0-9)
* Symbols (!@#$%^&*)

### Random Password Generation

The application generates highly randomized passwords based on the selected criteria.

### Copy to Clipboard

Users can easily copy the generated password to their clipboard with a single click.

### Password Strength Indicator

A color-coded strength indicator helps users understand the strength of the generated password.

### Responsive Design

The application is designed to be responsive and compatible with various screen sizes, including desktops, tablets, and mobile devices.

---

## How to Use

### Open the Application

Open the Password Generator website or run the project locally in your browser.

### Adjust Password Length

Use the slider labeled **Password Length** to specify the desired password length.

### Select Character Types

Choose the character types you want to include:

* Include Uppercase Letters
* Include Lowercase Letters
* Include Numbers
* Include Symbols

### Generate Password

Click the **Generate Password** button to create a password based on your selected options.

### Copy Password

Click the **Copy** button to copy the generated password directly to your clipboard.

### Check Password Strength

The strength indicator changes color based on the password's complexity:

* Green – Strong Password
* Yellow – Medium Password
* Red – Weak Password

### Generate Another Password

Modify the settings and click **Generate Password** again to generate a new password.

---

## JavaScript Functions

### generateRandomInteger()

Generates a random integer between 0 and 9.

### generateLowerCase()

Generates a random lowercase alphabet character.

### generateUpperCase()

Generates a random uppercase alphabet character.

### generateSymbols()

Selects a random symbol from the predefined symbols list.

### calculateStrength()

Calculates the strength of the generated password based on selected criteria and updates the strength indicator.

### copyContent()

Copies the generated password to the clipboard using the Clipboard API and displays a success or failure message.

### handleSlider()

Updates the displayed password length and adjusts the slider styling.

### handleCheckBoxChange()

Tracks selected checkboxes and ensures that the password length remains valid.

### shufflePassword(array)

Uses the Fisher-Yates Shuffle Algorithm to randomize the generated password characters.

---

## JavaScript Variables

### password

Stores the generated password.

### passwordLength

Represents the selected password length.

### checkCountor

Stores the count of selected character categories.

### symbols

Contains the predefined symbols used during password generation.

---

## Technologies Used

* HTML5
* CSS3
* JavaScript (ES6)

---

## Learning Outcomes

This project helped in understanding:

* DOM Manipulation
* Event Handling
* JavaScript Functions
* Random Number Generation
* Clipboard API
* Fisher-Yates Shuffle Algorithm
* Password Security Concepts
* Responsive Web Design

---

## Credits

This project was developed by **Keerthi Busireddy** as part of a web development learning journey. The project was inspired by concepts taught in web development tutorials and was built to strengthen skills in JavaScript, DOM manipulation, and responsive UI design.

---
