# Libra

This is a compiler for a project.

** Building

NOTE: Shell commands shown assume a working directory of this repository.

Dependencies:

- CMake >= 3.14 (you can get CMake [[https://cmake.org/] [here])

- Any C Compiler (I recommend [[https://gcc.gnu.org/][GCC])

First, generate a build tree using CMake.
```shell
    cmake -G
```

Finally, build an executable from the build tree.
```shell
    cmake --build build
```