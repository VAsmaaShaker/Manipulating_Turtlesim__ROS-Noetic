# Manipulating_Turtlesim__ROS-Noetic
Learn how to run and control the Turtlesim package in ROS Noetic for simulating and manipulating a turtle in a 2D environment.

ROS (Robot Operating System) provides a powerful framework for robotics software development. Turtlesim is a simple simulator in ROS that allows us to control a turtle in a 2D environment. In this tutorial, we will explore how to manipulate the turtlesim package to control the turtle's movement.

## Step1: Start ROS Core.
- Open a new terminal and start the ROS core:
     ```
     roscore
     ```
![image](https://github.com/VAsmaaShaker/Manipulating_Turtlesim__ROS-Noetic/assets/174564364/4a73e684-7a09-4a37-a527-8fa09806e93a)

## Step2: Launch Turtlesim.
- Open another terminal to run the turtlesim node and copy this code and paste:
     ```
     rosrun turtlesim turtlesim_node
     ```
![image](https://github.com/VAsmaaShaker/Manipulating_Turtlesim__ROS-Noetic/assets/174564364/5b59d764-b61b-4317-b85c-875be51a8f22)

## Step3: Control the Turtle.
   - Open a third terminal and copy this code and paste:
     ```
     rosrun turtlesim turtle_teleop_key
     ```
     This node allows you to control the turtle's movement using the keyboard arrow keys.
![image](https://github.com/VAsmaaShaker/Manipulating_Turtlesim__ROS-Noetic/assets/174564364/b70a747d-9577-48b5-a253-0fb1b4955666)



![image](https://github.com/VAsmaaShaker/Manipulating_Turtlesim__ROS-Noetic/assets/174564364/f2279f52-9aba-4296-be3c-97f86eb45ffd)
