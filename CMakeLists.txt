cmake_minimum_required(VERSION 3.9)
project(ObjTest)
set_property(GLOBAL PROPERTY USE_FOLDERS ON)

file(GLOB_RECURSE SRC_FILES ${CMAKE_CURRENT_SOURCE_DIR}/*.cpp)
file(GLOB_RECURSE HEADER_FILES ${CMAKE_CURRENT_SOURCE_DIR}/*.hpp)
add_executable(ObjPBRMtlTest ${SRC_FILES} ${HEADER_FILES})