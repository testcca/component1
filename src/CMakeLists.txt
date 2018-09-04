cmake_minimum_required(VERSION 2.8.12)
project(Component1)

add_library(${PROJECT_NAME} component1.cpp)

target_include_directories( ${PROJECT_NAME}
    PUBLIC ${PROJECT_SOURCE_DIR}/include
)
