add_library(screenhack STATIC
    screenhack.c
    xdbe.c)
target_include_directories(screenhack PRIVATE ../include)
target_link_libraries(screenhack comctl32 common)
