# CodeView-A-C-Compiler-Visualizer-with-Multi-Phase-Analysis
## 🌟 Project Overview

**CodeView** is a lightweight C compiler visualizer built entirely in HTML, CSS, and JavaScript. It demonstrates the compilation process through three major phases:

1. **Lexical Analysis** – Tokenization of C source code.
2. **Syntax Analysis** – Parse tree construction based on grammar rules.
3. **Intermediate Code Generation** – Generation of Three Address Code (TAC).

This tool helps students and developers understand how source code is transformed internally by a compiler.
## 🛠️ Features

- 🧾 Lexical Analyzer – Tokenizes input and categorizes lexemes.
- 🌲 Syntax Analyzer – Visualizes parse tree structures using recursive descent parsing.
- ⚙️ Intermediate Code Generator – Converts code to Three Address Code (TAC).
- 💻 CodeMirror integration for rich code editing experience.
- 📊 Real-time visualization of each compiler phase.
- 🎨 Responsive and clean UI using Bootstrap & Flexbox.
- 📂 Modular architecture with separate files for each compiler phase.

---

## 📁 Project Structure
📦 CodeView/
├── index.html # Main HTML page
├── style.css # Styling for the UI
├── lexer.js # Lexical analysis logic
├── parser.js # Syntax analysis logic
├── intermediate.js # Intermediate code generation logic
├── semantic.js # Semantic analysis (in progress)
├── assets/ # Images, icons, etc.

---

## 🧑‍💻 Technologies Used

- HTML5, CSS3, JavaScript (ES6)
- [CodeMirror](https://codemirror.net/) – Code Editor
- [D3.js](https://d3js.org/) – Visualization of parse trees
- Bootstrap – Responsive layout

---

## 🚧 Current Status

- ✅ Lexical Analyzer – Complete
- ✅ Syntax Analyzer – Complete
- ⚠️ Intermediate Code – Basic working (loops under development)
- ⚙️ Semantic Analyzer – Work in progress
- 📘 Documentation – Finalizing

---

## 🧪 Testing

| Component            | Status      | Notes                                      |
|---------------------|-------------|--------------------------------------------|
| Lexical Analysis     | ✅ Pass     | Works with various C input patterns        |
| Syntax Analysis      | ✅ Pass     | Handles nested structures and conditionals |
| Intermediate Code    | ⚠️ Partial | Loop support not fully integrated          |
| UI Interaction       | ✅ Pass     | Fully responsive and interactive           |
| Performance Test     | ✅ Pass     | Supports files up to 500 lines             |

---

## 📖 How to Run Locally

Open the folder in a code editor.
Launch index.html in any modern web browser.

No backend or build tools required. This is a 100% frontend-based application.
