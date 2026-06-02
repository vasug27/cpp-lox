# Lox Interpreter

![C++](https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white)

A modular and lightweight interpreter for the Lox programming language, written from scratch in Modern C++. This project focuses on the interpreter frontend, including lexical analysis and tokenization, with a simple CMake-based build.

## ⚙️ Architecture

The interpreter currently includes:

- **`lox.cpp`:** The program entrypoint that runs the scanner and supports file-based execution.
- **`Scanner.cpp`:** A lexical scanner that reads source text and produces tokens.
- **`Token.cpp`:** Token and literal representations with token type names.

## 🚀 Building

### Prerequisites
- CMake 3.10 or higher
- A modern C++ compiler (MSVC, GCC, or Clang)

### Build steps
```bash
mkdir build
cd build
cmake ..
cmake --build .
```

### Run
```bash
./lox
```

To execute a Lox script:
```bash
./lox path/to/script.lox
```

## Notes

- This implementation does not require external libraries such as Boost.
- The project is intentionally kept simple with direct source inclusion and minimal file dependencies.

## Author

**Vasu Goel** ([@vasug27](https://github.com/vasug27))
