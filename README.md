# The CSize CLI
## Easily get the size of any C type

# Usage

### Simply run the executable `csize` with the name of the desired type
### if there are any other headers you want to check, just include their names after the initial argument
### e.g `csize FILE stdio.h`
### NOTE: csize by default includes the following header files:
    - stdio
    - ctype
    - time
    - math
    - stdlib
    - sys/stat


# Requirements
- llvm (clang + lli)

