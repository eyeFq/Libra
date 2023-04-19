# Libra

This is a compiler for a project.

## Building

NOTE: Shell commands shown assume a working directory of this repository.

Dependencies:

- CMake >= 3.14 (you can get CMake [here](https://cmake.org/) )

- Any C Compiler (I recommend [GCC](https://gcc.gnu.org/))

First, generate a build tree using CMake.
```shell
    cmake -G
```

Finally, build an executable from the build tree.
```shell
    cmake --build build
```