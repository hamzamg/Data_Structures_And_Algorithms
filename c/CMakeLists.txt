cmake_minimum_required(VERSION 3.10)

project (DSA)

add_executable(${CMAKE_PROJECT_NAME} 
    src/main.c 
    src/util.c 

    src/algorithm/sort.c
    src/algorithm/search.c

    src/data_structure/array_list.c

    src/abstract_data_type/stack.c
)