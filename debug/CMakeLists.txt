FILE(GLOB debug_source "*.c" "*.cpp" "*.h")
SET(debug_source ${debug_source} PARENT_SCOPE)

INCLUDE_DIRECTORIES("../include")

ADD_LIBRARY(debug ${debug_source})

#ADD_SUBDIRECTORY(tests)
