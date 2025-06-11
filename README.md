# 🛠️ Mini-Compiler

A mini C++ compiler built using **Lex** (Flex) and **Yacc** (Bison), designed to parse and translate a subset of C-like language constructs. This project demonstrates core principles of compiler design including lexical analysis, parsing, syntax tree generation, and semantic checking.

---

## 🔧 Tools & Technologies

- **Lex (Flex)**: Lexical analyzer generator
- **Yacc (Bison)**: Syntax parser generator
- **C++**: For actions, symbol tables, and semantic logic
- **Makefile**: For easy build and testing

---

## ✅ Language Constructs Supported

The following constructs are implemented and parsed correctly:

1. **Conditional Statements**
   - `if` / `if-else`
   - Ternary operator (`? :`)
2. **Loops**
   - `while` loop
   - `for` loop (with initialization, condition, increment)

---

## 🧱 Features

- **Lexical Analysis**
  - Tokenizes keywords, identifiers, literals, operators, and symbols
- **Syntax Parsing**
  - Grammar rules for control-flow structures
- **Semantic Actions**
  - Intermediate representation and evaluation
- **Error Handling**
  - Basic syntax error detection with line info
- **Symbol Table (optional)**
  - Support for storing and tracking declared variables (if implemented)

---

## 📂 Project Structure


