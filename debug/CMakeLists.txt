FILE(GLOB debug_source "*.c" "*.cpp" "*.h")

INCLUDE_DIRECTORIES("../include")

ADD_LIBRARY(debug ${debug_source})

#ADD_SUBDIRECTORY(tests)
