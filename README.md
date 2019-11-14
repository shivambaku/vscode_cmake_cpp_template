# vscode_cpp_template
 Minimal boilerplate code to run C++ project using Visual Studio Code and CMake on Windows, MacOS, and Linux.
 
## Requirements
- Visual Studio Code (With C++ Extension by Microsoft)
- CMake v3.5+
- C++ compiler and debugger (On Windows uses MinGW)
- make (On Windows uses mingw32-make)

## Windows
In MinGW install mingw32-base and mingw32-gcc-g++ package.

Set the MinGW bin directory in the environment variable Path.  
Default directory is C:\MinGW\bin.

Set the CMake bin directory in the environment variable Path if not done during installation.  
Default directory is C:\Program Files\CMake\bin.
