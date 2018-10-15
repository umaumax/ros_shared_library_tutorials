# ros_shared_library_tutorials

他のパッケージに開示する情報
```
catkin_package(
  INCLUDE_DIRS include
  LIBRARIES ros_shared_library_tutorials_add
#  CATKIN_DEPENDS roscpp std_msgs
#  DEPENDS system_lib
)
```

```
add_library(${PROJECT_NAME}_add
   src/${PROJECT_NAME}/ros_shared_library_tutorials_add.cpp
)
```

[Building and installing C\+\+ libraries and headers — catkin 0\.6\.19 documentation]( http://docs.ros.org/jade/api/catkin/html/howto/format2/building_libraries.html )

----

## FYI
init gen command
```
catkin_create_pkg ros_shared_library_tutorials std_msgs roscpp
```
