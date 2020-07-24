# using_this_package

## setup_1 

+ creat_ros_workspeace

```bash
mkdir -p ~/catkin_ws/src
cd catkin_ws/src
catkin_init_workwpeace
cd ..
catkin_make
```
## setup_2

+ clone this package in you ros_workspeace

```bash
cd  catkin_ws/src
git clone https://github.com/Sunspeed-Robotics/R300/ir300_description.git
```

## setup_3

+ make this package

```bash
cd ..
catkin_make
```

## setup_4

+ source ros_workspeace 

```bash
source devel/setup.bash
```

## run this package,and useing wath robot module in rviz

```bash
roslaunch ir300_description display.launch
```

+ in rviz choose RobotModule,and choose the appropriate topic
