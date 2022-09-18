cmake_minimum_required(VERSION 3.18)
project(diameter)

find_package(igraph REQUIRED)

add_executable(diameter diameter.c)
target_link_libraries(diameter PUBLIC igraph::igraph)
