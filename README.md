# 🧮 Simple Web Calculator

A responsive and interactive web-based calculator built using **HTML**, **CSS**, and **JavaScript**. This project demonstrates DOM manipulation, event handling, and basic arithmetic logic in a clean, functional UI.

---

## 📁 Project Structure

calculator/
│
├── index.html # Main HTML structure of the calculator
├── css/
│ └── calculator.css # Styling and layout of the calculator
└── scripts/
└── calculator.js # JavaScript logic and functions

---

## 🔧 Features

- Perform **basic arithmetic operations**: addition, subtraction, multiplication, division
- Additional operations: **square**, **percentage**, **plus/minus toggle**
- **Clear all (AC)** functionality
- Supports **decimal point input**
- Minimalist UI with a gradient background and responsive layout

---

## 🚀 How to Run

1. Clone or download this repository.
2. Open the `index.html` file in your browser.
3. Use the calculator interface to perform operations.

---

## 💻 Technologies Used

- **HTML5** – for content and structure  
- **CSS3** – for styling and layout  
- **JavaScript (Vanilla)** – for interactive functionalities  

---

## 📷 Screenshot

<sub>*Add a screenshot named `screenshot.png` in the root directory to display here.*</sub>

---

## 📝 How it Works

- Input values are stored in hidden `<input>` fields: `operand`, `operation`, `equivalent`, and `decimalVar`
- Button click events trigger JavaScript functions to:
  - Capture and compute numeric inputs
  - Manage selected operations and display results
  - Handle decimal and special inputs like square and percentage

---

## ⚠️ Known Issues

- Typo in JavaScript: `opeartion` should be `operation` in the `decimalPoint()` function
- UI may not scale optimally on very small screens

---

## 📌 Future Improvements

- Add support for keyboard input
- Improve error handling (e.g., divide-by-zero detection)
- Add memory functions (MC, M+, M-)

---

## 🙌 Acknowledgements

This calculator is ideal for beginners exploring:

- JavaScript DOM manipulation
- HTML/CSS layout structuring
- Web project organization and styling
