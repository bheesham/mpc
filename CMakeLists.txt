cmake_minimum_required(VERSION 3.9)

project(mpc
    VERSION 0.8.8
    LANGUAGES C)

add_library(mpc STATIC
    mpc.h
    mpc.c)
