cmake_minimum_required(VERSION 3.25)
project(Tree LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 23)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

if(MSVC)
	add_compile_options(/utf-8 /W4)
endif()

add_executable(tree src/main.cpp)