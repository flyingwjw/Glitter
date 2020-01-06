cmake_minimum_required(VERSION 3.0)

set(TARGET shaders_interpolation)

set(SOURCES shaders_interpolation.cpp)

add_executable(${TARGET} ${SOURCES})
target_link_libraries(${TARGET} glfw glad)