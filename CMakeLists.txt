# logc/CMakeLists.txt
add_library(logc STATIC src/log.c)

target_include_directories(logc
    PUBLIC ${CMAKE_CURRENT_SOURCE_DIR}/src
)
