# ackermann-vehicle-exploration-with-3D-LiDAR
终极缝合怪

1. launch the gazebo of ackermann vehicle and lidar:

roslaunch ackermann_vehicle_gazebo ackermann_vehicle.launch

2. launch the SLAM method using A-LOAM or LeGO-LOAM:

A-LOAM:

roslaunch aloam_velodyne aloam_velodyne_HDL_32.launch

LeGO-LOAM:

roslaunch lego_loam run.launch

3. launch the navigation using DWA local planner:

roslaunch ackermann_navigation navigation.launch

4. launch the exploration:

roslaunch explore_lite explore.launch
