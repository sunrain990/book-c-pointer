cmake_minimum_required(VERSION 3.6)
project(book_c_pointer)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES main.c)
add_executable(book_c_pointer ${SOURCE_FILES})