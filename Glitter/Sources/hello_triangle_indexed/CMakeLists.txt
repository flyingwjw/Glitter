cmake_minimum_required(VERSION 3.0)

set(TARGET hello_triangle_indexed)

set(SOURCES hello_triangle_indexed.cpp)

add_executable(${TARGET} ${SOURCES})
target_link_libraries(${TARGET} glfw glad)