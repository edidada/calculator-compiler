cmake_minimum_required(VERSION 3.12)
project(calculator-compile)

set(CMAKE_CXX_STANDARD 11)

add_executable(calculator ${CMAKE_SOURCE_DIR}/src/calculator.c)
