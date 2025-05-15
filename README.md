# 🔬 Scientific Calculator (No Libraries Edition)

Welcome to the **Scientific Calculator Challenge** – a project designed for **intermediate software engineering students** working in **pairs** with **5-minute rotations**.

This is a console-based calculator where all mathematical functions must be **implemented from scratch**. That means no importing `math`, `numpy`, or similar libraries. Your calculator will do everything from the ground up.

---

## 🎯 Objectives

- Implement a powerful scientific calculator with no external libraries.
- Reinforce understanding of:
  - Arithmetic operations
  - Trigonometry, exponents, and logarithms
  - Parsing and evaluating expressions
  - Memory storage and user-defined functions
- Practice clean coding, version control, and **pair programming**.

---

## 👥 Pair Programming Rules

- Use **5-minute driver/navigator rotations**.
- Switch roles consistently.
- Driver types; navigator guides, asks questions, and suggests improvements.
- Use meaningful commits after each session.

---

## 🧮 Features to Implement

| Category         | Functionality                             |
|------------------|--------------------------------------------|
| 🔢 Arithmetic     | `+`, `-`, `*`, `/`, `%`, `^`               |
| 📐 Trigonometry   | `sin(x)`, `cos(x)`, `tan(x)`              |
| 📈 Logarithms     | `log(x, base)`, `ln(x)`                   |
| 🧮 Exponents      | `exp(x)`, `x^n`                           |
| √ Roots          | `sqrt(x)`, `cbrt(x)`                      |
| 🎯 Constants      | `pi`, `e`                                 |
| 🧠 Memory         | `store`, `recall`, `clear`, `Ans`         |
| 📦 Variables      | `x = 2`, then use `sin(x)`                |
| 🧪 Functions      | `f(x) = x^2 + 3`, then call `f(2)`         |
| 🔁 Undo           | Go back one step in history               |
| 📜 History        | Show past expressions                     |
| 🔄 Angle Mode     | Switch between degrees and radians        |

> ⚠️ **Do not use the `math` module or any built-in math functions.**  
> Implement all functionality from scratch using series expansions, loops, and your own logic.

---

## 🧪 Example Input & Output

```text
> pi
=> 3.14159...

> sin(pi/2)
=> 1.0

> x = 5
> x^2 + 2*x + 1
=> 36

> f(x) = x^3 - x
> f(3)
=> 24

> undo
=> Undid last step

> store
=> Value stored in memory

> recall
=> 24

---

Resource	                            | Description
Explorable Explanations	              | A collection of interactive math and logic explorations. Excellent for intuition-based learning on concepts like sine waves, exponentials, etc.
Khan Academy – Precalculus & Calculus |	Bite-sized lessons with examples and practice. Great for understanding how sin, cos, log, e, etc. behave mathematically. No full code, just formulas and visuals.
BetterExplained.com                   |	Focuses on the “why” behind math. Excellent resource for series expansions and ideas like Euler’s number, pi, etc. No code — just intuition and formulas.
CalculatorSoup – Math Formulas        |	Lists common math formulas (quadratic, logs, trig, etc.) in a very W3Schools-like format. No code, just expressions and definitions.
Desmos Graphing Calculator	          | Ideal for visually verifying what a formula should look like (e.g., sin(x) graph). Students can use it to see patterns in series approximations.
OpenStax Math Textbooks (Free)        |	Clean, open-access textbooks. Look up functions like logarithms, trigonometry, and exponents for in-depth ideas with examples. Still beginner-friendly.
Symbolab – Formula Sheet              |	Shows simplified versions of trig, exponent, and log rules. Think of it like “W3Schools for Math Formulas.”
