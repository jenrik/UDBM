FILE(GLOB base_source "*.c" "*.cpp" "*.h")

INCLUDE_DIRECTORIES("../include")

ADD_LIBRARY(base ${base_source})

#ADD_SUBDIRECTORY(tests)
