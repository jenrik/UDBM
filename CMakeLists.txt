CMAKE_MINIMUM_REQUIRED(VERSION 3.10)
PROJECT(udbm VERSION 1.0)

#CONFIGURE_FILE(include/config.h.in include/config.h)

set(CMAKE_C_STANDARD 99)
set(CMAKE_CXX_STANDARD 98)

ADD_SUBDIRECTORY(base)
ADD_SUBDIRECTORY(dbm)
ADD_SUBDIRECTORY(debug)
ADD_SUBDIRECTORY(hash)
ADD_SUBDIRECTORY(io)

ADD_LIBRARY(udbm STATIC ${base_source} ${dbm_source} ${debug_source} ${hash_source} ${io_source})

TARGET_INCLUDE_DIRECTORIES(udbm PUBLIC "include")