# 指定所需的最低版本
cmake_minimum_required(VERSION 3.10.2)

# 定义项目名称
project(HelloWorld CXX)

# 添加可执行文件目标，第一个参数是生成的可执行文件名，后面是源文件
add_executable(HelloWorld hello.cpp)
