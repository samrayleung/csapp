project(CSAPP)
set(CMAKE_CXX_FLAGS   "-Wall") 
set(CMAKE_CXX_FLAGS_DEBUG "${CMAKE_CXX_FLAGS_DEBUG} -Wall")
cmake_minimum_required(VERSION 3.8)
add_subdirectory(io)
add_subdirectory(src)
add_subdirectory(link)
add_subdirectory(opt)
add_subdirectory(ecf)
add_subdirectory(mem)
add_subdirectory(netp)
include_directories(${CSAAP_SOURCE_DIR}/include)
