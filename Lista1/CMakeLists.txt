cmake_minimum_required(VERSION 3.10)

project(lista3 LANGUAGES CXX)
set(CMAKE_CXX_STANDARD 17)


set (CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fsanitize=address")

add_executable(zad1 Zad1.cpp)
add_executable(zad2 Zad2.cpp)
add_executable(zad3 Zad3.cpp)

