cmake_minimum_required (VERSION 3.8)

file(GLOB_RECURSE sourceFiles
    "./*.h"
    "./*.c"
)

add_library (libpsd ${sourceFiles} )
include_directories(./include)