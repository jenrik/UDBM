FILE(GLOB hash_source "*.c" "*.cpp" "*.h")

INCLUDE_DIRECTORIES("../include")

ADD_LIBRARY(hash ${hash_source})

#ADD_SUBDIRECTORY(tests)
