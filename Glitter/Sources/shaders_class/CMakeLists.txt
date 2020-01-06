cmake_minimum_required(VERSION 3.0)

set(TARGET shaders_class)

set(SOURCES shaders_class.cpp)

add_executable(${TARGET} ${SOURCES})
target_link_libraries(${TARGET} glfw glad)