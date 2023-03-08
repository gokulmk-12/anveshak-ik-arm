# Anveshak-IK-Arm
This repository has all the necessary scripts and launch files to make the Anveshak Arm move using a Joystick. The Joystick controls the movement of the End Effector and an IK Solver calculates the respective joint angles and moves the entire arm with respect to the end effector.

Steps to Work with the Repo
1) cd ~/catkin_ws/src
2) git clone https://github.com/gokulmk-12/anveshak-ik-arm.git
3) cd ../
4) catkin_make
5) roslaunch ik_pkg joy.launch

In a new terminal after sourcing the workspace, 

6) roslaunch ik_pkg ik_arm.launch

