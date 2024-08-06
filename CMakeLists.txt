cmake_minimum_required(VERSION 3.27)
project(cpp_scripting_language)

set(CMAKE_CXX_STANDARD 14)

add_executable(cpp_scripting_language
        main.cpp
        generation.hpp
        parser.hpp
        arena.hpp
        tokenization.hpp
)