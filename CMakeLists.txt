cmake_minimum_required(VERSION 3.10)

project(SimpleShell)

set(CMAKE_CXX_STANDARD 17)

include_directories(include)

add_executable(shell
    src/main.cpp
    src/parser.cpp
    src/executer.cpp
    src/builtins.cpp
)

