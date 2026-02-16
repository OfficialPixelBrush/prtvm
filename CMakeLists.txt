cmake_minimum_required(VERSION 3.16.0)
project(prtvm VERSION 0.1.0)

include_directories(
    "${PROJECT_SOURCE_DIR}/src/"
)

add_executable(
    prtvm
    src/main.cpp
)