# 🔐 Secure Password Generator

A powerful and customizable web utility designed to generate strong, unique passwords instantly. This project demonstrates advanced **JavaScript logic**, focusing on array manipulation, random character selection, and real-time user interface updates.

## 🚀 Key Features

* **Customizable Security:** Allows users to define password length and include/exclude uppercase letters, numbers, and special symbols.
* **Security Strength Indicator:** Built-in logic to ensure the generated passwords meet modern security standards.
* **One-Click Copy:** Integrated "Copy to Clipboard" functionality for a seamless user experience.
* **Real-Time Generation:** Instantly updates the password string as parameters are adjusted.
* **Modern UI/UX:** A clean, dark-themed interface built with responsive CSS.

## 🛠 How It Was Built

This application was developed using a "Logic-First" approach to ensure both security and performance:

1.  **Character Sets:** Defined multiple string constants (lowercase, uppercase, numeric, and symbols) to serve as the data source.
2.  **Randomization Engine:** Utilized the `Math.random()` and `Math.floor()` methods to pick indices from a combined character pool based on user selection.
3.  **State Management:** Employed JavaScript variables to track active checkboxes and range sliders for the password length.
4.  **Clipboard API:** Used the `navigator.clipboard.writeText()` method to enable secure copying of the generated string.
5.  **Event Listeners:** Implemented `input` and `click` listeners to trigger the generation logic dynamically without page reloads.
