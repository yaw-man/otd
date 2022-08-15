cmake_minimum_required(VERSION 3.11)
project(otd)
add_executable(otd Source.cpp)
set_target_properties(otd PROPERTIES COMMON_LANGUAGE_RUNTIME "pure")