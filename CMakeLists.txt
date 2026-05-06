cmake_minimum_required(VERSION 3.16)
project(ray-tracing)

add_executable(ray-tracing main.cpp)

target_include_directories(ray-tracing PRIVATE
    ${CMAKE_SOURCE_DIR}
    ${CMAKE_SOURCE_DIR}/external
)