cmake_minimum_required(VERSION 2.8)
project( Feature )
find_package( OpenCV REQUIRED )
add_executable( bin/Feature src/ShiFeat.cpp )
target_link_libraries( bin/Feature ${OpenCV_LIBS} )
