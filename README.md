
##CMakeLists中文件如下  
cmake_minimum_required(VERSION 2.8)  
project( DisplayImage )  
find_package( OpenCV REQUIRED )  
add_executable( DisplayImage DisplayImage.cpp )  
target_link_libraries( DisplayImage ${OpenCV_LIBS} )
##int main(int argc,char** argv)  
在opencv中常用的方法，其中   
* argc : 输入参数个数  
* argv 可执行文件路径  
  
  该例中 ./DisplayImage image  
  
   argc = 2;
   arcv[0] = DisplayImage;   
   
  argv[1] = 图像路径
