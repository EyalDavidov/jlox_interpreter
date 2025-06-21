# Lox Language Interpreter

This is a personal implementation of the Lox programming language interpreter, based on the book [Crafting Interpreters](https://craftinginterpreters.com/) by Bob Nystrom. The goal of this project is to deepen my understanding of interpreters, language design, and Java — and to showcase it as part of my software development portfolio.

## 📚 About the Project

Lox is a dynamically-typed, object-oriented language with syntax similar to JavaScript. This interpreter is written in **Java**, following the structure and guidance of the "Crafting Interpreters" book.

The project includes:

- A scanner (lexer) that tokenizes source code.
- A parser that builds an abstract syntax tree (AST).
- An interpreter that executes the code.
- Error handling and a basic REPL (interactive prompt).

This implementation is focused on the tree-walk interpreter approach.

## 🚀 Getting Started

### Prerequisites
- Java 11 or higher
- Git (for cloning the repo)
- A terminal or IDE that supports Java

### Clone and Run
```bash
git clone https://github.com/eyaldavidov/lox-interpreter.git
cd lox-interpreter
javac -d out src/com/craftinginterpreters/lox/*.java
java -cp out com.craftinginterpreters.lox.Lox
