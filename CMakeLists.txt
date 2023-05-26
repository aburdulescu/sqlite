cmake_minimum_required(VERSION 3.10)

project(sqlite)

add_library(sqlite src/sqlite3.c)
target_include_directories(sqlite PUBLIC src)
