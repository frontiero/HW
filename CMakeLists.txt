cmake_minimum_required(VERSION 3.30)

project(HelloWorld)

set(CMAKE_EXPORT_COMPILE_COMMANDS ON)

add_library(HW
    src/HW.c
)

add_executable(main
    src/main.c
)

target_link_libraries(main HW)

target_include_directories(main PRIVATE include)

