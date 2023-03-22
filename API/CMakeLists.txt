add_library(API SHARED hello.c)#生成动态库文件 可以使用STATIC生成静态库文件
set_target_properties(API PROPERTIES OUTPUT_NAME "hello")#将动态库文件API输出名称改为hello