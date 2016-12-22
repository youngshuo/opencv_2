#opencv_2  
#CMakeLists中文件如下  
cmake_minimum_required(VERSION 2.8)  
project( DisplayImage )  
find_package( OpenCV REQUIRED )  
add_executable( DisplayImage DisplayImage.cpp )  
target_link_libraries( DisplayImage ${OpenCV_LIBS} )
