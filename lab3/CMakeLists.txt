cmake_minimum_required(VERSION 3.23)
project(lab2)

set(CMAKE_CXX_STANDARD 14)

add_executable(lab2 main.cpp SymbolTable/SymbolTable.cpp SymbolTable/SymbolTable.h Scanner/Scanner.cpp Scanner/Scanner.h)
