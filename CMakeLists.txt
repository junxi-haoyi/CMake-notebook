cmake_minimum_required(VERSION 3.10)

project(HELLO)

add_subdirectory(USER)#告诉cmake去这两个文件寻找新的cmake文件，并解析它
add_subdirectory(API)




