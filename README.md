# Go chase it (ROS)
In this project, I learned the fundamentals of ROS by making a ball chasing robot that uses a camera feed to figure out and compute the ball's location and moves the robot towards it. 

![Project image](./img.png)


# Technologies used

- Gazebo 
- RViz 
- URDF 
- Lidar plugin 
- Camera plugin 
- roscpp 

<br><br>

---
# Run project 

Make sure the you are in the base directory and run the following in terminal

```
$ catkin_make
$ source devel/setup.bash 
$ roslaunch my_robot world.launch
```
In another terminal window run the following

```
$ source devel/setup.bash
$ roslaunch ball_chaser ball_chaser.launch
```
If you want to see the robot's camera feed run this in a seprate terminal window

```
$ source devel/setup.bash
$ rosrun rqt_image_view rqt_image_view  
```
---