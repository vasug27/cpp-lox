cmake_minimum_required(VERSION 3.10)
project(LoxInterpreter VERSION 1.0.0 LANGUAGES CXX)

# Require C++17
set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED True)

# Add the executable
# Note: Since lox.cpp currently includes Scanner.cpp and Token.cpp directly,
# we only need to specify lox.cpp as the source file to avoid multiple definition errors.
add_executable(lox
    lox/lox.cpp
)
