# Lox Interpreter

![C++](https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white)

A modular and lightweight interpreter for the Lox programming language, written from scratch in Modern C++. This project demonstrates a deep understanding of compiler construction, specifically focusing on system software engineering and front-end compiler phases such as lexical analysis, tokenization, and language abstraction.

## ✨ Technical Highlights

This project is built with a strong focus on the core principles of compiler engineering and performance:

- **Compiler Front-End Architecture:** Implements a robust `Scanner` and `Token` system to break down raw source code into manageable abstract tokens, handling lexical errors gracefully.
- **Strong C/C++ Foundation:** Built entirely in C++ leveraging the Standard Template Library (`std::vector`, `std::string`, file streams), demonstrating robust memory management and performant system software abstractions.
- **Language Abstractions:** Showcases a practical understanding of how programming languages are parsed, how syntax errors are managed, and how execution environments are simulated (REPL vs. File Execution).
- **Extensible Design:** The architecture is decoupled and designed to easily integrate further compiler phases (Optimizer, Bytecode Generation, and Virtual Machine execution), mirroring the modularity required in production-grade compilers and linkers.

## ⚙️ Architecture

Currently, the interpreter implements the following frontend components:

- **Lox Runtime Environment (`lox.cpp`):** Manages the execution context, supporting both file-based script execution and an interactive REPL (Read-Eval-Print Loop) prompt.
- **Lexical Analyzer (`Scanner.cpp`):** Reads raw source code and translates it into a sequence of meaningful tokens, ignoring whitespace and comments.
- **Token Representation (`Token.cpp`):** Defines the structure for tokens, storing their lexemes, types, and source locations for precise error reporting.

## 🚀 Getting Started

### Prerequisites
- CMake (3.10 or higher)
- A modern C++ compiler (GCC, Clang, or MSVC)

### Building and Running
You can compile the project using CMake:
```bash
mkdir build
cd build
cmake ..
cmake --build .
```

Run the interpreter in REPL mode:
```bash
./lox
```

Run a Lox script:
```bash
./lox path/to/script.lox
```

## 👨‍💻 Author

**Vasu Goel** ([@vasug27](https://github.com/vasug27))
