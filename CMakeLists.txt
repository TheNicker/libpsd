cmake_minimum_required (VERSION 3.8)

file(GLOB_RECURSE sourceFiles
    "./src/*.h"
    "./src/*.c"
)

add_library (libpsd ${sourceFiles} )
include_directories(./include)