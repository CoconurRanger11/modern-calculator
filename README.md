# 🧮 Modern Calculator

A sleek **web-based calculator** built using **HTML, CSS, and JavaScript**.
This project demonstrates core front-end development concepts such as **DOM manipulation, event handling, and responsive UI design**.

The calculator performs basic arithmetic operations while maintaining a clean and modern interface.

---

## ✨ Features

* ➕ Addition, ➖ Subtraction, ✖️ Multiplication, ➗ Division
* 🔢 Numeric and decimal input
* 🧹 **Clear (C)** button to reset the display
* ⌫ **CE** button to delete the last character
* 🟦 Large **equals button** for quick evaluation
* ⚠️ Error handling for invalid expressions
* 🎨 Modern calculator UI with button press effects
* 📱 Centered layout that works across screen sizes

---

## 🛠️ Technologies Used

| Technology                  | Purpose                                      |
| --------------------------- | -------------------------------------------- |
| **HTML5**                   | Structure of the calculator                  |
| **CSS3**                    | Styling, layout, shadows, and button effects |
| **JavaScript (Vanilla JS)** | Calculator functionality and DOM interaction |

---

## 📂 Project Structure

```
modern-calculator
│
├── index.html     # Calculator layout
├── style.css      # Styling and UI design
├── script.js      # Calculator logic
└── README.md      # Project documentation
```

---

## ⚙️ How It Works

1. Each calculator button contains a `data-button` attribute.
2. JavaScript detects which button is clicked.
3. The value is added to the display input.
4. When `=` is pressed, the expression is evaluated using JavaScript.
5. Errors are caught and displayed as **Invalid Entry**.

---

## ▶️ Running the Project

### 1️⃣ Clone the repository

```
git clone https://github.com/your-username/modern-calculator.git
```

### 2️⃣ Navigate into the project

```
cd modern-calculator
```

### 3️⃣ Open the project

Simply open **index.html** in your browser.

No installation or dependencies are required.

---

## 🎯 Learning Objectives

This project was created to practice:

* JavaScript **DOM manipulation**
* Handling **user input**
* Implementing **event listeners**
* Using **CSS Grid for layouts**
* Building **interactive UI components**

---

## ⚠️ Important Note

This calculator uses JavaScript's `eval()` function to evaluate expressions.

While it works well for simple learning projects, `eval()` is **not recommended for production applications** because it can execute arbitrary code.

---

## 🚀 Possible Improvements

Future enhancements could include:

* Keyboard input support
* Scientific calculator functions
* Dark/light mode toggle
* Expression history
* Safer math parser instead of `eval()`
* Mobile-optimized layout

---

## 👨‍💻 Author

Built as a learning project to practice **front-end web development and JavaScript fundamentals**.

---

⭐ If you like this project, consider starring the repository.
