FILE(GLOB io_source "*.c" "*.cpp" "*.h")
SET(io_source ${io_source} PARENT_SCOPE)

INCLUDE_DIRECTORIES("../include")

ADD_LIBRARY(io ${io_source})

# ADD_SUBDIRECTORY(tests)
