cmake_minimum_required(VERSION 4.0)
project(Architecture_Proyecto_1 C)

set(CMAKE_C_STANDARD 11)

add_executable(OpSystems_Proyecto1
        user/sh.c
        user/utils.h
        user/parser.c
        user/parser.h
        user/commands.c)
