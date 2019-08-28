cmake_minimum_required(VERSION 3.14)

project(tinyhttp)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

include_directories(
    ${CMAKE_CURRENT_SOURCE_DIR}
)

#aux_source_directory(${CMAKE_CURRENT_SOURCE_DIR} srcs)

#add_executable(example ${srcs})
add_executable(example example.cpp)