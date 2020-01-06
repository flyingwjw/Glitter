cmake_minimum_required(VERSION 3.0)

set(TARGET hello_triangle)

set(SOURCES hello_triangle.cpp)

add_executable(${TARGET} ${SOURCES})
target_link_libraries(${TARGET} glfw glad)