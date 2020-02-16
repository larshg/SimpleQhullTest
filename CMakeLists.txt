cmake_minimum_required(VERSION 3.16)

project (TestQhull)

find_package(Qhull CONFIG REQUIRED)

add_executable (TestQhull demo.cpp)

target_link_libraries(TestQhull Qhull::qhull_p)