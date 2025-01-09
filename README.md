Scientific Calculator in React

Objective

The goal of this project is to assess front-end development skills, state management, and the ability to replicate a sophisticated UI/UX using React. The objective is to build a web-based clone of the macOS Scientific Calculator with a responsive design and full mathematical functionalities.

Features

UI/UX

Mimics the macOS Scientific Calculator's look and feel.

Responsive design.

Uses Roboto font.

Clear display for input and result.

Functionalities

Basic Operations:

Addition (+), Subtraction (-), Multiplication (*), Division (/).

Percentage (%).

Sign toggle (+/-).

Advanced Functions:

Trigonometry: sin, cos, tan (radians and degrees).

Logarithms: ln (natural log), log10 (log base 10).

Exponents and roots: x², x³, x^y, e^x, 10^x, square root (√x), cube root (∛x), y-root (y√x).

Factorial (x!).

Constants: π (pi), e (Euler's number).

Scientific notation (EE).

Hyperbolic functions: sinh, cosh, tanh.

Random number generation (Rand).

Parentheses for grouped expressions.

Memory functions: MC (clear memory), M+ (add to memory), M- (subtract from memory), MR (recall memory).

Special Feature

Confetti explosion occurs when 99 and 33 are used in an operation (e.g., 99 + 33 or 99 * 33).

State Management

Handles user input, operations, and results efficiently.

Supports clear, delete, and reset functionalities.

Allows result chaining (using the previous result as an operand for new calculations).

Edge Case Handling

Division by zero.

Large number calculations.

Installation and Setup

Clone the repository:

git clone <repository-url>
cd scientific_calculator

Install dependencies:

npm install

Start the development server:

npm run dev

Open the app in your browser:

http://localhost:5173/

Technologies Used

React.js

Vite

CSS (for styling)

React-Confetti-Explosion (for special effects)

Output Screenshot
![image](https://github.com/user-attachments/assets/823a5d1d-0140-41d1-bdc2-580344d5136b)


