project (component1)

add_library(${PROJECT_NAME} src/component1.cpp)
add_library(poc::comp1 ALIAS ${PROJECT_NAME})

target_include_directories( ${PROJECT_NAME}
    PUBLIC ${PROJECT_SOURCE_DIR}/include
)
