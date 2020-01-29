cmake_minimum_required(VERSION 3.16)

project (HELLO)

find_package(Qhull CONFIG REQUIRED)

add_executable (${HELLO} demo.cpp)