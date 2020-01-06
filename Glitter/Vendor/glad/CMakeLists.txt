cmake_minimum_required(VERSION 3.0)

INCLUDE_DIRECTORIES(
	include
)
SET(GLAD_SRCS
	src/glad.c
)

SET(GLAD_HDRS
	include/glad/glad.h
)

ADD_LIBRARY(glad ${GLAD_SRCS} ${GLAD_HDRS})