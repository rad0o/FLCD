cmake_minimum_required(VERSION 3.23)
project(lab5)

set(CMAKE_CXX_STANDARD 14)

add_executable(lab5 main.cpp Grammar.cpp Grammar.h Production.cpp Production.h DescendentRecursiveParser.cpp DescendentRecursiveParser.h Configuration.cpp Configuration.h Tests/Tests.cpp Tests/Tests.h)
