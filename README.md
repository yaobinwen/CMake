# Study Notes

## 1. Overview

The original `README` file is `README.rst`.

The directories and files:
- `Help`: Help documentation
  - `guide/tutorial`: The tutorial.
- `Source`: All the source files
  - `cmakemain.cxx`: The `main` function.

## 2. How to Build (with Documentation)

To build with `CMake` (see `README.rst`, section `Building CMake with CMake`):
- Install `sphinx`.
- `mkdir build`
- `cd build`
- `cmake -DSPHINX_HTML=ON ..`
- `cmake --build .`
