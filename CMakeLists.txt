# CMake file for BMP5 api library

SET(libname BMP5_lib)

# Create lib
add_library(${libname}
    bmp5_defs.h
    bmp5.h
    bmp5.c
)