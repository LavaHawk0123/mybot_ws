# Mystique Rover
Named so for the particular color scheme chosen, This repository contains the package for an out-of-the-box testing environment for all your simulation needs. The bot comes equipped with a LiDAR(Hokuyo), A Stereocamera(Kinect), an IMU and a GPS module. 

![Mystique-Isometric](https://user-images.githubusercontent.com/75236655/182896597-44ff61b8-47bc-4f9b-94f5-ccf09e7247aa.gif)
<h2> instructions to Install <h2>

### Open your catkin workspace in the terminal and run
```
git clone https://github.com/LavaHawk0123/mystique-rover.git
```
  
### Open the terminal and run
```
cd catkin_ws
source /opt/ros/noetic/setup.bash
catkin build
```

### Then run:
```
rosrun {insert your workspace name} rgbgrowing
```

### In a new terminal run:
```
rosrun {insert your workspace name} rgbgrowing
```
### In a new terminal run Rviz and visualize the pointcloud:
```
rosrun rviz rviz
```
### Rover :
![gazebo_rover](https://user-images.githubusercontent.com/75236655/106312727-21af9d00-628d-11eb-9653-eb89e99aa957.png)

### Camera Plugin:
![camera_edited](https://user-images.githubusercontent.com/75236655/106312616-f462ef00-628c-11eb-8995-7c6f85c26dfa.png)

### GPS Plugin:
![gps](https://user-images.githubusercontent.com/75236655/106312694-13618100-628d-11eb-96eb-25bcdadf9dd1.png)

### IMU Plugin:
![imu](https://user-images.githubusercontent.com/75236655/106312786-39872100-628d-11eb-843a-56cf267b9fd5.png)

### Kinnect Plugin:
![kinnect](https://user-images.githubusercontent.com/75236655/106312808-41df5c00-628d-11eb-9ce4-34887fca36ac.png)

### Laser Scanner Plugin:
![laser_scan](https://user-images.githubusercontent.com/75236655/106312845-4dcb1e00-628d-11eb-93c8-553b8595c57c.png)

### Ultrasonic Sensor Plugin:
![Ultrasonic Sensor](https://user-images.githubusercontent.com/75236655/106313208-d649be80-628d-11eb-8f2b-4c83bd65cc1b.jpeg)



