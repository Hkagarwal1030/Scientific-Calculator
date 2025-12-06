# Scientific-Calculator
🧮 Scientific Calculator (Rad/Deg)










A modern, beautifully designed Scientific Calculator featuring Rad/Deg angle mode, trigonometry, logarithms, factorials, power operations, and more.
Built using pure HTML, CSS, and JavaScript, it includes animations, a neon–glass UI, and accurate math functions.


✨ Features
🎨 Modern Glassmorphism UI

Neon glow effects

Gradient background

Smooth hover transitions

Dark-themed elegant look


🧠 Scientific Functions

sin, cos, tan (with Rad/Deg toggle)

log, ln

π, e constants

Square root

Percentage (%)

Factorial (n!)

Power (xʸ)

Parentheses support



🔢 Standard Calculator Operations

Addition, subtraction, multiplication, division

Decimal support

Backspace

Clear (AC)


🧭 Rad/Deg Switch

Toggle between Radians and Degrees instantly using the mode button.


📂 Project Structure
/scientific-calculator
│── index.html
│── README.md



🛠️ Technologies Used
Technology	Purpose
HTML5	Structure of UI & button layout
CSS3	Glassmorphism, animations, responsive styles
JavaScript (ES6)	Calculator logic, trig mode toggle, evaluation engine


🚀 Getting Started
1️⃣ Clone the repository
git clone https://github.com/Hkagarwal1030/Scientific-Calculator.git

2️⃣ Open the project
index.html


This calculator is fully client-side. No backend required.

📸 Screenshot (Add later)


<img width="614" height="610" alt="image" src="https://github.com/user-attachments/assets/f6506005-0d67-481d-88e8-d2ffcc0d43b3" />



🧪 Core Logic Highlights
✔ Trigonometry with Mode Toggle
function trigFunc(fn, angle) {
    if (isDeg) angle = angle * Math.PI / 180;
    switch (fn) {
        case 'sin': return Math.sin(angle);
        case 'cos': return Math.cos(angle);
        case 'tan': return Math.tan(angle);
    }
}

✔ Expression Parsing with Safe Replacements

Converts %, sin, cos, tan, log, ln, √, factorial, powers, etc.

Evaluated using eval() only after transformation.


📌 Future Enhancements

🖥 Full history panel

📱 Mobile-optimized layout

🎤 Voice input

🧭 Scientific keyboard support

💾 LocalStorage memory functions (M+, MR)



🤝 Contributing

Contributions are welcome!

Fork this repo

Create a new branch

Commit your changes

Open a pull request



📄 License

This project is licensed under MIT License.



⭐ Support

If you found this project useful, consider giving it a star on GitHub! ⭐
