FILE(GLOB io_source "*.c" "*.cpp" "*.h")

INCLUDE_DIRECTORIES("../include")

ADD_LIBRARY(io ${io_source})

# ADD_SUBDIRECTORY(tests)
