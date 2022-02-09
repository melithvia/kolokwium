cmake_minimum_required(VERSION 3.16)
project(myProgram)
install(DESTINATION ../kody)
add_executable(zad2
        address.cpp
        address.h
        employee.cpp
        employee.h
        main.cpp)
