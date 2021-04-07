FILE(GLOB dbm_source "*.c" "*.cpp" "*.h")
SET(dbm_source ${dbm_source} PARENT_SCOPE)

INCLUDE_DIRECTORIES("../include")

ADD_LIBRARY(dbm ${dbm_source})

ADD_SUBDIRECTORY(tests)
