FILE(GLOB base_source "*.c" "*.cpp" "*.h")
SET(base_source ${base_source} PARENT_SCOPE)

INCLUDE_DIRECTORIES("../include")

ADD_LIBRARY(base ${base_source})

#ADD_SUBDIRECTORY(tests)
