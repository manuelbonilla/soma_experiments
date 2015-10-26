roslaunch soma_experiments test.launch

rosbag play --loop --clock manuelb_ws/src/soma_experiments/soma_bags/14_1_.bag

roslaunch soma_experiments scene_filter.launch