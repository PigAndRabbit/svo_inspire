# svo_inspire

The newest commit cannot be successed run, because of exposure time jacobian not right,
but it could be success compiled. 20181107

SVO is a good opensorce visual odometry, it's fast enough to be deploied on UAV.
This version will add some other ideas, such as the strategy of svo_edgelet, faster depth filter, etc.

Build

mkdir catkin_svo

cd catkin_svo

mkdir src

cd src

git clone https://github.com/LamyZee/svo_inspire.git

cd ..

caktin_make


Run

source $(FULL_SVO_PATH)/devel/setup.bash

open three Terminals, and execute the following commands one by one.

roslaunch svo_ros euroc.launch

roslaunch svo_ros svo_rviz.launch

rosbag play $(FULL_DATABAG_PATH)/MH_03_medium.bag


Now, it's not finished. will be updated at untime.
