# SET(EXECUTABLE_OUTPUT_PATH ${PROJECT_BINARY_DIR}/bin)
# SET(LIBRARY_OUTPUT_PATH ${PROJECT_BINARY_DIR}/lib)
# add_executable(hello main.c)

add_library(sayhello SHARED hello.c)
