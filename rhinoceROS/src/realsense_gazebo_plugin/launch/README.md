## Contents: 

[depth node](https://github.com/leander-dsouza/Gazebo/tree/master/rhinoceROS/src/realsense_gazebo_plugin/launch/depth_proc.launch) - Launches a node which generates depth topics (required to be launched if pointcloud needs to accessed in the RealSense)

[empty world](https://github.com/leander-dsouza/Gazebo/tree/master/rhinoceROS/src/realsense_gazebo_plugin/launch/empty_world.launch) - Launches an empty world 

[mapviz](https://github.com/leander-dsouza/Gazebo/tree/master/rhinoceROS/src/realsense_gazebo_plugin/launch/mapviz.launch) - A tuned mapviz launch file chosen to match URC and workshop GPS coordinates

[spawn my bot](https://github.com/leander-dsouza/Gazebo/tree/master/rhinoceROS/src/realsense_gazebo_plugin/launch/spawn_my_bot.launch) - Launches the multipurpose bot into an empty world

[stereo vision](https://github.com/leander-dsouza/Gazebo/tree/master/rhinoceROS/src/realsense_gazebo_plugin/launch/start_stereovision.launch) - Maps left and right camera images to generate a stereo image (used only for rover dual cam) 

[disparity image](https://github.com/leander-dsouza/Gazebo/tree/master/rhinoceROS/src/realsense_gazebo_plugin/launch/start_stereovision_disparityimage.launch) - Generates a disparity map (used only for rover dual cam and to be launched after start_stereovision.launch)

[rviz](https://github.com/leander-dsouza/Gazebo/tree/master/rhinoceROS/src/realsense_gazebo_plugin/launch/rover_rviz.launch) - Launches rviz with the multipurpose bot in the frame

[URC](https://github.com/leander-dsouza/Gazebo/tree/master/rhinoceROS/src/realsense_gazebo_plugin/launch/urc_world.launch) - Launches a world containing parameters of the URC competition site


