# 声明要求的 cmake 最低版本
cmake_minimum_required(VERSION 2.8)
# 声明一个 cmake 工程
project( stack )

add_executable( stack use_stack.cpp stack.cpp )
