cmake_minimum_required(VERSION 3.11)
project(uthash VERSION 0.1.0 LANGUAGES C)

add_library(uthash INTERFACE)
target_include_directories(uthash INTERFACE src)
