cmake_minimum_required(VERSION 3.11)

project(EAMS
    VERSION
        0.0.1
    DESCRIPTION
        "Extensible Aeronautical Modelling System."
)

enable_testing()

add_subdirectory(docs)
add_subdirectory(config)
add_subdirectory(include)
add_subdirectory(src)
add_subdirectory(test)