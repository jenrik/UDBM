FILE(GLOB dbm_source "*.c" "*.cpp" "*.h")

INCLUDE_DIRECTORIES("../include")

ADD_LIBRARY(dbm ${dbm_source})

ADD_SUBDIRECTORY(tests)
