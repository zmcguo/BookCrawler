#项目名称
PROJECT(zmcc)
#声明要求的最小版本
cmake_minimum_required(VERSION 2.6)

SET(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -g -Wall -O2")
SET(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -g -Wall -O2")
#添加参与编译的子目录 我理解为：添加下一个CMakeLists.txt
add_subdirectory(utils)
add_subdirectory(src)
