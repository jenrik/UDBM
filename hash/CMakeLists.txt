FILE(GLOB hash_source "*.c" "*.cpp" "*.h")
SET(hash_source ${hash_source} PARENT_SCOPE)

INCLUDE_DIRECTORIES("../include")

ADD_LIBRARY(hash ${hash_source})

#ADD_SUBDIRECTORY(tests)
