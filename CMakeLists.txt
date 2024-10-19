cmake_minimum_required(VERSION 3.29)
project(C___learning_codes)

set(CMAKE_CXX_STANDARD 17)

add_executable(C___learning_codes main.cpp)

add_executable(add_using Chapter_03/add_using.cpp)
add_executable(arrayScores Chapter_03/arrayScores.cpp)
add_executable(c_type Chapter_03/c_type.cpp)
add_executable(char_repl Chapter_03/char_repl.cpp)
add_executable(c_string Chapter_03/c_string_hdr.cpp)
add_executable(get_line Chapter_03/get_line.cpp)
add_executable(square Chapter_03/square.cpp)

add_executable(capacity Chapter_09/capacity.cpp)
add_executable(erase01 Chapter_09/erase01.cpp)
add_executable(erase02 Chapter_09/erase02.cpp)
add_executable(erase03 Chapter_09/erase03.cpp)
add_executable(find_str Chapter_09/find_str.cpp)
add_executable(find_ops Chapter_09/find_ops.cpp)