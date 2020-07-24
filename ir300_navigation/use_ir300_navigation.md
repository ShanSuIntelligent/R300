# Use_ir300_navigation

## setup_1

+ If you want to use this function, you need to do the following.
  + create ros_workwpeace
  + install following this ros_package
  
  ```bash
  sudo apt-get install ros-kinetic-nav*
  sudo apt-get install ros-kinetic-dwa-local-planner
  sduo apt-get install ros-kinetic-map*
  ```
  
## setup_2

+ clone this package in your ros_workspeace;
+ this package in you_workspeace/src;

```bash
git clone https://github.com/Sunspeed-Robotics/R300/ir300_navigation.git
```

## make this package

+ in you_workspeace

```bash
catkin_make
```

+ source you_workspeace

```bash
source devel/setup.bash
```

## run gmaping map

```bash
roslaunch ir300_navigation gmaping.launch
```

## run navigation

```bash
roslaunch ir300_navigation ir100_navigation.launch
```
