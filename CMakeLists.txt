# Copyright (C) 2018 Tomasz Gałaj

cmake_minimum_required(VERSION 3.9.2 FATAL_ERROR)
project(Breakout VERSION 0.1)

set(THIRDPARTY_DIR "${CMAKE_CURRENT_SOURCE_DIR}/thirdparty")

# add thirdparties
include(thirdparty/thirdparty.cmake)

# subdirectories
add_subdirectory(src)