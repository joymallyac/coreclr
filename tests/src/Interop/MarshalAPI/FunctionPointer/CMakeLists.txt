cmake_minimum_required (VERSION 2.6)
project (FunctionPointerNative)
include_directories(${INC_PLATFORM_DIR})
set(SOURCES FunctionPointerNative.cpp)

# add the executable
add_library (FunctionPointerNative SHARED ${SOURCES})

# add the install targets
install (TARGETS FunctionPointerNative DESTINATION bin)


