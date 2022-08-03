## My Gazebo Experiments

- Building a Mobile Robot from Scratch
- Adding Sensors
- Autonomous navigation of the robot using ROS navigation Stack
- Script for Obstacle Avoidance

A PDF presentation is included to understand the code.  

# Instructions for building the package

- Download / clone the repository in your home directory

```
$ git clone https://github.com/swagatk/gazebo_expts.git
```

- Copy the folder '~/gazebo_expts/skbot/' to your `~/catkin_ws/src` folder  and run catkin_make

```
$ cp ~/gazebo_expts/skbot ~/catkin_ws/src
$ cd ~/catkin_ws
$ catkin_make
$ source devel/setup.bash
```

Now you should be able to navigate into various folders using ROS
commands such as `roscd` or `rosed`. 
