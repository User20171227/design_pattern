cmake_minimum_required(VERSION 2.8)

project(abstract_factory_pattern)

set(OUTPUTNAME abstract_factory_pattern)
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wall -g -O2 -std=c++14")

aux_source_directory(. DIR_SRCS)
add_executable(${OUTPUTNAME} ${DIR_SRCS})

