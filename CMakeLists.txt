cmake_minimum_required(VERSION 2.8.2)
project(alex)

include_directories(src)

add_subdirectory(src)
add_subdirectory(test)
add_subdirectory(lib/googletest)

