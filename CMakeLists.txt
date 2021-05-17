cmake_minimum_required(VERSION 3.10)

project(oppai C)

add_library(oppai
    oppai.c
)

target_compile_definitions(oppai PRIVATE OPPAI_IMPLEMENTATION)
target_include_directories(oppai PUBLIC .)
