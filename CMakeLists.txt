cmake_minimum_required(VERSION 3.20)
project(stb_image_write)
add_library(stb_image_write "src/stb_image_write.c")
target_include_directories(stb_image_write PUBLIC "include")