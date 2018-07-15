# C-Wrapper around C++ library

Inspired by an example here: https://www.teddy.ch/c++_library_in_c/

To build:
~~~~
vbaggiol@laptop:~/CLionProjects/c-wrapper$ mkdir build && cd build
vbaggiol@laptop:~/CLionProjects/c-wrapper/build$ cmake ..
-- The C compiler identification is GNU 5.4.0
-- The CXX compiler identification is GNU 5.4.0
-- Check for working C compiler: /usr/bin/cc
-- Check for working C compiler: /usr/bin/cc -- works
-- Detecting C compiler ABI info
-- Detecting C compiler ABI info - done
-- Detecting C compile features
-- Detecting C compile features - done
-- Check for working CXX compiler: /usr/bin/c++
-- Check for working CXX compiler: /usr/bin/c++ -- works
-- Detecting CXX compiler ABI info
-- Detecting CXX compiler ABI info - done
-- Detecting CXX compile features
-- Detecting CXX compile features - done
-- Configuring done
-- Generating done
-- Build files have been written to: /home/vbaggiol/CLionProjects/c-wrapper/build
vbaggiol@laptop:~/CLionProjects/c-wrapper/build$ make
Scanning dependencies of target myLib
[ 20%] Building CXX object src/mylib/CMakeFiles/myLib.dir/MyClass.cpp.o
[ 40%] Building CXX object src/mylib/CMakeFiles/myLib.dir/MyWrapper.cpp.o
[ 60%] Linking CXX static library libmyLib.a
[ 60%] Built target myLib
Scanning dependencies of target wrapperDemo
[ 80%] Building C object src/mymain/CMakeFiles/wrapperDemo.dir/MyMain_c.c.o
[100%] Linking CXX executable wrapperDemo
[100%] Built target wrapperDemo
vbaggiol@laptop:~/CLionProjects/c-wrapper/build$ ./src/mymain/wrapperDemo 
3
 

~~~~