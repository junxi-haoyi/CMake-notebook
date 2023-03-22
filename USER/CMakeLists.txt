include_directories(${PROJECT_SOURCE_DIR}/API)#添加头文件搜索路径
add_executable(hello main.c)#将main.c生成可执行文件
target_link_libraries(hello API)#将静态库或动态库文件链接到hello执行文件