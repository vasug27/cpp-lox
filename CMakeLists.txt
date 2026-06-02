cmake_minimum_required(VERSION 3.10)
project(LoxInterpreter VERSION 1.0.0 LANGUAGES CXX)

# Require C++17
set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED True)

add_executable(lox
    lox.cpp
)