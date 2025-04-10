# 🔐 Password Generator

A modern and responsive password generator built with HTML, CSS, and JavaScript. It allows users to generate secure passwords based on customizable criteria like length, character type, and more.

## 🚀 Features

- ✅ Adjustable password length (1 to 20 characters)
- 🔠 Includes:
  - Uppercase letters
  - Lowercase letters
  - Numbers
  - Symbols
- 🎯 Password strength indicator (Weak, Medium, Strong)
- 🔁 Randomized password using Fisher-Yates shuffle
- 📋 Copy to clipboard with tooltip feedback
- 🌈 Clean UI with animated slider and gradient background



## 💻 How to Use

1. Clone the repository:
```bash
git clone https://github.com/your-username/password-generator.git
cd password-generator


Open index.html in your browser.

Set the password options (length, character types), click Generate Password, and then Copy it using the button.

📈 Password Strength Logic
✅ Strong: Includes uppercase, lowercase, and number/symbol, and is 8+ characters

⚠️ Medium: At least 2 types and 6+ characters

❌ Weak: Anything less

Color-coded indicator:

🟢 Green = Strong

🟡 Yellow = Medium

🔴 Red = Weak


🔧 Built With
HTML5

CSS3 (Flexbox, custom properties)

Vanilla JavaScript

Clipboard API

📌 To-Do / Improvements
 Add light/dark mode toggle

 Option to avoid similar characters (e.g., l, 1, I)

 Save password history

 Keyboard accessibility
