## subversion-tools
A build script inspired by [i686-elf-tools](https://github.com/lordmilko/i686-elf-tools) that downloads subversion and its prerequisites and builds them into a self-contained pacakge.

### Required Packages (Linux)

 * binutils, gcc, g++, etc...
 * git
 * cmake
 * curl
 * python 2

### Build
```
./build_libsvn.sh
```
Output will be in build_libsvn/lib_output