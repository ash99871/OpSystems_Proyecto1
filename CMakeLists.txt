cmake_minimum_required(VERSION 4.0)
project(Architecture_Proyecto_1 C)

set(CMAKE_C_STANDARD 11)

add_executable(OpSystems_Proyecto1
        sh.c
        utils.h
        parser.c
        parser.h
        commands.c)
