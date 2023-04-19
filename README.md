# Libra

This is a compiler for a project.

# Usage
Run the executable from the command line/terminal/shell with a path to the source code you want to compile as the only argument. Currently, we print out the furthest progress we are able to make. Eventually, we will output compiled source code.

Example (if it's in the sys path)
```shell
librc example.libsrc
```

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