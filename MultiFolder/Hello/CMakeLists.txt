add_library(Hello hello.c)

target_include_directories(Hello PUBLIC $CMAKE_CURRENT_SOURCE_DIR)
