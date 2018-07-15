# C-Wrapper around C++ library

Checkout to the /tmp directory:

~~~~
vbaggiol@laptop:/tmp$ git clone https://github.com/vbaggiol/c-wrapper.git
Cloning into 'c-wrapper'...
remote: Counting objects: 29, done.
remote: Compressing objects: 100% (26/26), done.
remote: Total 29 (delta 3), reused 29 (delta 3), pack-reused 0
Unpacking objects: 100% (29/29), done.
Checking connectivity... done.
~~~~

and build:
~~~~
vbaggiol@laptop:/tmp$ cd c-wrapper
vbaggiol@laptop:/tmp/c-wrapper$ mkdir build && cd build
vbaggiol@laptop:/tmp/c-wrapper/build$ cmake ..
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
-- Build files have been written to: /tmp/c-wrapper/build
vbaggiol@laptop:/tmp/c-wrapper/build$ 

~~~~

This example is inspired from https://www.teddy.ch/c++_library_in_c/ - many thanks!
