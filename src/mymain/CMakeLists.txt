add_library(myLibWrapper MyWrapper.cpp MyWrapper.h)

#add_executable(wrapperDemo MyMain_c.c MyWrapper.cpp MyWrapper.h)

target_link_libraries(myLibWrapper LINK_PUBLIC myLib)