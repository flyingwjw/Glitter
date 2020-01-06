cmake_minimum_required(VERSION 3.0)

set(TARGET shaders_uniform)

set(SOURCES shaders_uniform.cpp)

add_executable(${TARGET} ${SOURCES})
target_link_libraries(${TARGET} glfw glad)